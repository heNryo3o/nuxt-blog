<template>
  <div class="index-container">
    <second-category />
    <div class="article-list">
      <nuxt-link to="/">
        <el-card shadow="hover" class="article-item">
          <el-image src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png"
            class="article-image" mode="contain" />
          <div class="info-part">
            <div class="title">使用nuxt写博客</div>
            <div class="summary">
              <span>使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容</span></div>
            <div class="article-bottom">
              <span class="article-bottom-item">2019年8月4日</span>
            </div>
          </div>
        </el-card>
      </nuxt-link>
      <nuxt-link to="/">
        <el-card shadow="hover" class="article-item">
          <el-image src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png"
            class="article-image" mode="contain" />
          <div class="info-part">
            <div class="title">使用nuxt写博客</div>
            <div class="summary">
              <span>使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容使用nuxt写博客内容,使用nuxt写博客内容,使用nuxt写博客内容</span></div>
            <div class="article-bottom">
              <span class="article-bottom-item">2019年8月4日</span>
            </div>
          </div>
        </el-card>
      </nuxt-link>
    </div>
    <!-- <div class="right-part">

    </div> -->

  </div>
</template>

<script>
  import SecondCategory from "@/components/public/SecondCategory.vue"
  export default {
    components: {
      SecondCategory
    },
    data() {
      return {

      }
    }
  }
</script>

<style>
  .index-container {
    width: 1200px;
    margin: auto;
    margin-top: 20px;
  }

  .article-list {
    display: inline-block;
    width: 750px;
    float: left;
    margin: 0 0 0 20px;
  }

  .article-item {
    height: 160px;
    margin-bottom: 25px;
    border-radius: 15px;
  }

  .article-image {
    width: 160px;
    height: 120px;
    line-height: 160px;
    float: left;
  }

  .info-part {
    display: inline-block;
    float: left;
    padding: 0 20px;
    width: 500px;
    height: 120px;
    position: relative;
  }

  .title {
    font-weight: bold;
    font-size: 15px;
    color: #303133;
  }

  .summary {
    padding-top: 10px;
    line-height: 15px;
    color: #5e6d82;
    font-size: 13px;
  }

  .article-bottom {
    height: 25px;
    position: absolute;
    bottom: 0;
  }

  .article-bottom-item {
    line-height: 25px;
    color: #303133;
    font-size: 13px;
  }

  .right-part {
    display: inline-block;
    width: 170px;
    height: 500px;
    background: #fff;
  }
</style>
