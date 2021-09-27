<template>
  <RouterLink
    to="/"
    class="logo">
    <span>OMDbAPI</span>.COM
  </RouterLink>
  <!-- RouterLink a태그 대신 쓰임 to="/" 메인페이지로 이동-->
</template>

<style lang="scss" scoped>
@import "~/scss/main.scss";

.logo{
  font-family: 'Oswald', sans-serif;
  font-size: 20px;
  color: $black;
  text-decoration: none;
  &:hover {
    color: $black;
  }
  span{
    color: $primary;

  }
}

</style>