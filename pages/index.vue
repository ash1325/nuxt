<template>
  <div class="container">
    <MainVisual />
    <PageArticle>
      <template #article-title>
        今日のランチ
      </template>
      <template #article-txt>
        福岡県のラーメンを食べてきました。<br>美味しかったですよ！
      </template>
    </PageArticle>
    <PageArticle>
      <template #article-title>
        私の趣味
      </template>
      <template #article-txt>
        最近はカフェ巡りと写真が趣味な私です。
      </template>
    </PageArticle>
    <PageArticle>
      <template #article-title>
        Nuxt.jsについて
      </template>
      <template #article-txt>
        Nuxt.jsって面白いんです。<br>おすすめです！
      </template>
    </PageArticle>
    <PageArticle>
      <template #article-title>
        ブログ開設しました！
      </template>
      <template #article-txt>
        ブログ開設！よろしくお願いします。
      </template>
    </PageArticle>
  </div>
</template>

<script>
import MainVisual from '@/components/MainVisual.vue'
import PageArticle from '@/components/PageArticle.vue'

export default {
  components: {
    MainVisual,
    PageArticle
  }
}
</script>

<style lang="scss">
  .container{
    max-width: 1000px;
    width: 80%;
    margin: 0 auto;
    padding: 40px 0;
  }
</style>
