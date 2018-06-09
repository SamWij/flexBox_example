<template>
    <div class='nav-bar'>
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>

export default {
  data () {
    return {
      msg: 'Welcome to my flexbox demo'
    }
  }
}
</script>

<style lang='scss'>
    .nav-bar {
        background-color: chartreuse;
        margin: 0;
        color: hotpink;
        display: flex;
    }
</style>
