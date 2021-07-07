<template>
  <main>
      <nav>

      </nav>
      <div class="content">
          <img alt="Vue logo" src="../assets/logo.png" />
      </div>
  </main>
</template>

<script>
export default {
    name: 'HelloWorld',
    props: {
        msg: String
    },
    data() {
        return {
            count: 0
        }
    },
    methods:{

    }
}
</script>
<style lang="stylus" scoped>
main{
    display flex
    width 100%
    height 100%
    nav{
        flex 0 0 auto
        width 200px
        background-color red
    }
    nav:after{
        background-color: #ccc;
        position: absolute;
        left: 0;
        width: 4px;
        height: 100%;
        cursor: w-resize;
    }
    .content{
        flex 1 1 auto
        background-color green
    }
}
</style>