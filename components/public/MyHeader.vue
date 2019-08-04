<template>
  <div class="header">
    <div class="header-container">
      <nuxt-link to="/">
        <div class="logo-container">
          <span>
            于高衡 de 博客
          </span>
        </div>
      </nuxt-link>
      <div class="nav-container">
        <div class="search">
          <el-input v-model="search" size="small" placeholder="搜索想要查找的关键词"></el-input>
        </div>
        <div class="category">
          <nuxt-link to="/">
            <div class="category-item active">
              <span>php</span>
            </div>
          </nuxt-link>
          <nuxt-link to="/">
            <div class="category-item">
              <span>vue</span>
            </div>
          </nuxt-link>
          <nuxt-link to="/">
            <div class="category-item">
              <span>小程序</span>
            </div>
          </nuxt-link>
          <nuxt-link to="/">
            <div class="category-item">
              <span>运维</span>
            </div>
          </nuxt-link>
          <nuxt-link to="/">
            <div class="category-item">
              <span>生活</span>
            </div>
          </nuxt-link>
          <nuxt-link to="/">
            <div class="category-item">
              <span>关于我</span>
            </div>
          </nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'MyHeader',
    data() {
      return {
        search: ''
      }
    }
  }
</script>

<style>
  .header {
    height: 70px;
    width: 100%;
    background: #fff;
  }

  .header-container {
    width: 1200px;
    margin: auto;
    height: 100%;
    line-height: 80px;
  }

  .logo-container {
    font-size: 24px;
    font-weight: bold;
    color: #409eff;
    opacity: .8;
    display: inline-block;
  }

  .nav-container {
    display: inline-block;
    width: 800px;
    float: right;
  }

  .search {
    width: 200px;
    display: inline-block;
  }

  .category {
    display: inline-block;
  }

  .category-item {
    height: 100%;
    padding: 0 22px;
    color: #1989fa;
    opacity: .5;
    display: inline-block;
  }

  .category-item:hover {
    opacity: 1;
  }

  .category-item.active {
    opacity: 1;
  }

  .category-item.active span {
    line-height: 58px;
    height: 58px;
    border-bottom: #1989fa solid 2px;
  }
</style>
