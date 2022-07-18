<template>
  <div class="main">
    <div class="main-grey">
      <CardAtipe />
      <CardBtipe />
      <ServiceCard />
    </div>
    <TestimonialCard />
  </div>
</template>

<script>
import CardAtipe from './CardAtipe.vue';
import CardBtipe from './CardBtipe.vue';
import ServiceCard from './ServiceCard.vue';
import TestimonialCard from './TestimonialCard.vue'
export default {
  name: 'AppMain',
  components: {
    CardAtipe,
    CardBtipe,
    ServiceCard,
    TestimonialCard
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .main{
   
    // margin-top: 50px;
    // margin-left: auto;
    // margin-right: auto;
    // display: flex;
    // flex-direction: column;
    // align-items: center;
    background-color: #fff;
  }
  .main-grey{
    background-color: #f5f5f5;
  }
</style>