<template>
  <section class="section-article">
      <div class="section-article__inner">
        <div class="section-article__thm">
        </div>
        <div class="section-article__detail">
          <h2 class="section-article__ttl">
            <slot name="article-title">記事タイトル</slot>
          </h2>
          <p class="section-article__txt">
            <slot name="article-txt">ダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミーダミー</slot>
          </p>
        </div>
      </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss">
  .section-article{
    width: 100%;
    margin-bottom: 30px;

    &__inner{
      display: flex;
      align-items: center;

    }

    &__thm{
      width: 200px;
      height: 150px;
      flex: 0 0 200px;
      background: #dedede;
    }

    &__detail{
      margin-left: 50px;
    }

    &__ttl{
      padding-left: 12px;
      margin-bottom: 10px;
      font-size: 2rem;
      border-left: 5px solid #F7CB37;
    }

    &__txt{
      font-size: 1.4rem;
      line-height: 1.5;
    }
  }
</style>
