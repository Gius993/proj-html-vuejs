<template>
  <div class="main">
      <CardAtipe />
  </div>
</template>

<script>
import CardAtipe from './CardAtipe.vue'
export default {
  name: 'AppMain',
  components: {
    CardAtipe
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .main{
 
    margin-top: 50px;
    // margin-left: auto;
    // margin-right: auto;
    // display: flex;
    // flex-direction: column;
    // align-items: center;
  }
</style>