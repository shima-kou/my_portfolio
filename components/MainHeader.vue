<template>
  <header>
    <div class="header-inner flex justify-between py-8 px-10">
      <Logo />
      <nav>
        <ul>
          <li><nuxt-link to="/">Top</nuxt-link></li>
          <li><nuxt-link to="about">about</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: aqua;
  .header-inner {
    display: flex;
    justify-content: space-between;
  }

  ul {
    > li {
      display: inline-block;
      &:not(:last-child) {
        margin-right: 16px;
      }
    }
  }
}
</style>
