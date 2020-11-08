<template>
  <header class="header">
      <div class="header-inner">
          <h1 class="header-ttl">portfolio</h1>
          <ul class="header-nav">
            <li><router-link to="/">home</router-link></li>
            <li><router-link to="/about">about</router-link></li>
            <li><router-link to="/contact">contact</router-link></li>
          </ul>
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .header{
        display: flex;
        align-items: center;
        width: 100%;
        height: 80px;
        background: #3C3838;

        &-inner{
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 80%;
            margin: 0 auto;
        }

        &-ttl{
            color: #fff;
            font-size: 2rem
        }

        &-nav{
            display: flex;

            a{
                display: inline-block;
                margin-left: 20px;
                color: #fff;
                font-size: 1.6rem
            }

        }
    }
</style>
