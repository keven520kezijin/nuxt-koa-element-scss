<template>
  <section class="container">
    <img src="../assets/img/logo.png" alt="Nuxt.js Logo" class="logo" />
    <h1 class="title">
      Universal Vue.js Application Framework
    </h1>
    <el-button type="primary">柯文我爱你</el-button>
    <br/>
    <br/>
    <nuxt-link class="button" to="/about">
      About page
    </nuxt-link>
  </section>
</template>

<style scoped>
.title
{
  margin: 50px 0;
}
</style>
