<template>
  <section class="section-mv">
      <p class="section-mv__txt">
        <slot>Welcome to My Portfolio.</slot>
      </p>
    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.section-mv{
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 1000px;
    height: 220px;
    margin-bottom: 40px;
    background: #F7CB37;

    &__txt{
      font-size: 3rem;
      font-weight: bold;
      @media screen and (max-width: 750px){
        font-size: 2.2rem;
      }
    }
  }
</style>
