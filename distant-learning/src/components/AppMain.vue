<template>
  <div class="main">
    <div class="main-grey">
      <CardAtipe />
      <CardBtipe />
      <ServiceCard />
    </div>
    <TestimonialCard />
    <CardCtipe />
    <div class="main-grey">
      <CardDtipe />
    </div>
  </div>
</template>

<script>
import CardAtipe from './CardAtipe.vue';
import CardBtipe from './CardBtipe.vue';
import ServiceCard from './ServiceCard.vue';
import TestimonialCard from './TestimonialCard.vue'
import CardCtipe from './CardCtipe.vue'
import CardDtipe from './CardDtipe.vue'
export default {
  name: 'AppMain',
  components: {
    CardAtipe,
    CardBtipe,
    ServiceCard,
    TestimonialCard,
    CardCtipe,
    CardDtipe
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .main{
    background-color: #fdfdfd;;
  }
  .main-grey{
    background-color: #f5f5f5;
  }
</style>