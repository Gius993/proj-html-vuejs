<template>
  <div class="container">
	<div class="text">
		<div class="text-a">
			<strong>Commerge Buisness</strong>
		</div>
		<div class="text-b">		
			<strong>Distant Mentornig Program</strong>
		</div>

	</div>	
   <div class="button">
		<a href="#">Download free guidebook </a>
   </div>
  </div>
</template>

<script>
export default {
  name: 'AppJumbo',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	
	/* eslint-disable */
	.container{
		background-repeat: no-repeat;	
		background-size: cover;
		background-position: center;
		background-image: url('../assets/img/home-3-hero-bg.jpg');
		color: white;
		text-align: center;
		padding: 150px 0;
	}
	.text-a{
		font-size: 40px;
	}
	.text-b{
		margin-top: 30px;
		font-size: 60px;
	}
	.button a{
		color:#1fad95;
		background-color: white;
		width: max-content;
		border: 1px solid white;
		border-radius: 5px;
		padding: 10px;
	}
	.button{
		margin-top: 40px;
		// margin-bottom: 50px;
	}
	.button a:hover{
		background-color: #1fad95;
		color:white;
		border: 1px solid #1fad95;
	}
</style>