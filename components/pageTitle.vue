<template>
  <div v-if="pageNameJa !== 'ページタイトル'" class="page-title-wrapper py-12">
    <h1 class="page-title text-6xl text-center">{{ pageNameJa }}</h1>
    <p class="text-center">{{ pageNameEn }}</p>
  </div>
  <div v-else class="page-title-wrapper py-12">
    <h1 class="page-title en_title text-6xl text-center">{{ pageNameEn }}</h1>
  </div>
</template>

<style lang="scss" scoped></style>

<script>
export default {
  props: {
    pageNameJa: {
      type: String,
      default: "ページタイトル"
    },
    pageNameEn: {
      type: String,
      default: "Page Title"
    }
  }
};
</script>
