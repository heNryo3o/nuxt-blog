<template>
  <div>
    <my-header />
    <nuxt />
  </div>
</template>

<script>
  import MyHeader from "@/components/public/MyHeader.vue"
  export default {
    components: {
      MyHeader
    }
  }
</script>
<style>
  body {
    margin: 0;
    font-family: PingFang SC;
    background: #f8f8f8;
  }

  a {
    text-decoration: none;
  }

  span {
    display: inline-block;
    line-height: 1.5;
  }
</style>
