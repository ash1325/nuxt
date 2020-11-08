<template>
  <footer class="footer" v-scroll-to="'.header'">
    <div class="footer-inner">
        <p class="footer-copy">copyright</p>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .footer{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 65px;
        background: #3C3838;
        cursor: pointer;

        &-copy{
            color: #fff;
            font-size: 1.4rem;
        }
    }
</style>
