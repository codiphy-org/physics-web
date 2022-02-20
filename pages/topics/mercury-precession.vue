<template>
  <v-card elevation="2">
    <v-card-title>Precession of Mercury's orbit</v-card-title>
    <v-card-subtitle>Newtonian 2-body central force</v-card-subtitle>
    <v-card-text>
      Lagrangian in spherical coordinates
      <mathjax>
        $$\mathscr{L} = \frac{1}{2}(m \dot{r}^2 + m r^2 \dot{\theta}^2) +
        \frac{GMm}{r} \tag{1}$$
      </mathjax>
      <mathjax
        >$$\frac{\partial \mathscr{L}}{\partial r} = m r \dot{\theta}^2 -
        \frac{GMm}{r^2} \tag{2}$$</mathjax
      >
      <mathjax
        >$$\frac{\partial \mathscr{L}}{\partial \dot{r}} = m \dot{r}
        \tag{3}$$</mathjax
      >
      <mathjax
        >$$\frac{\partial \mathscr{L}}{\partial \theta} = 0 \tag{4}$$</mathjax
      >
      <mathjax
        >$$\frac{\partial \mathscr{L}}{\partial \dot{\theta}} = m r^2
        \dot{\theta} \tag{5}$$</mathjax
      >

      <mathjax
        >$$0 = \frac{\partial \mathscr{L}}{\partial r} -
        \frac{d}{dt}(\frac{\partial \mathscr{L}}{\partial \dot{r}}) = r
        \dot{\theta}^2 - \frac{GM}{r^2} -\ddot{r}$$</mathjax
      >
      <mathjax
        >$$\longrightarrow \ddot{r} = r \dot{\theta}^2 - \frac{GM}{r^2}
        \tag{6}$$</mathjax
      >

      <mathjax
        >$$0 = \frac{\partial \mathscr{L}}{\partial \theta} -
        \frac{d}{dt}(\frac{\partial \mathscr{L}}{\partial \dot{\theta}}) = r
        \dot{\theta}^2 - \frac{GM}{r^2} -\ddot{r}$$</mathjax
      >
      <mathjax>$$\longrightarrow L = m r^2 \dot{\theta} \tag{7}$$</mathjax>
    </v-card-text>
  </v-card>
</template>
