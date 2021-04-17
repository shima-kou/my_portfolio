<template>
  <h1 v-if="$route.name === 'index'" id="site_title" class="en_title text-5xl">
    Everday Web
  </h1>
  <p v-else id="site_title" class="en_title text-5xl">
    Everday Web
  </p>
</template>

<style lang="scss" scoped>
#site_title {
  font-size: 18px;
}
</style>
