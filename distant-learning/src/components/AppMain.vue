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
    <div class="subscribe">
        <div class="text-title">
            <div class="title">Subscribe <span>Newsletters</span></div>
            <p>
              Enter your email address to register to our nesletter subscription 
              delivered on a regular basis!
            </p>
        </div>
        <div class="bar-email">
            <input type="email" placeholder="Enter your email">
            <div class="button">
                <a href="#">Subscribe </a>
            </div>
        </div>
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
  .subscribe{
    padding-top: 100px;
    text-align: center;
    // display: flex;
    // flex-direction: column;

  }
  .button a{
	color:white;
	background-color: #1fad95;
	width: max-content;
	border: 1px solid #1fad95;
	border-radius: 2px;
	padding-top: 10px;
	padding-bottom: 10px;
	padding-left: 10px;
	padding-right: 10px;
	font-size: 10px;
}
.bar-email{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 45px;
  margin-bottom: 25px;
  input{
    width: 400px;
    height: 35px;
    background-color:#f5f5f5;
    border: none;
		resize: none;
		outline: none;
    font-size: 10px;
    padding-left: 15px;
  }
}
.text-title{
  .title{
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 20px;
    span{
      color:#1fad95;
    }
  }
  p{
    font-size: 16px;
    color: #6c6c6b;
    padding-left: 30%;
    padding-right: 30%;
  }
}

</style>