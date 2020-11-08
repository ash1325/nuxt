<template>
  <div class="container">
      <MainVisual>
          about page.
      </MainVisual>
  </div>
</template>

<script>
import MainVisual from '@/components/MainVisual.vue'
export default {
    components: {
        MainVisual
    }

}
</script>

<style lang="scss" scoped>
.container{
    max-width: 1000px;
    width: 80%;
    margin: 0 auto;
    padding: 40px 0;
}

.section-mv{
    background: #3aa;
  }
</style>