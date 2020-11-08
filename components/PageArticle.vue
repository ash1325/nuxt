<template>
  <section class="section-article">
    <router-link to="/">
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
    </router-link>
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

    a{
      display: block;
      color: #333;
    }

    &__inner{
      display: flex;
      align-items: center;
      @media screen and (max-width: 750px){
        display: block;
      }

    }

    &__thm{
      width: 200px;
      height: 150px;
      flex: 0 0 200px;
      background: #dedede;
      @media screen and (max-width: 750px){
        width: 100%;
        height: 200px;
      }
    }

    &__detail{
      margin-left: 50px;
      @media screen and (max-width: 750px){
        margin-left: 0;
        margin-top: 20px;
      }
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
