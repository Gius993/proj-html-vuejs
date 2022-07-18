<template>
  <div class="container">
		<!-- <div class="sub-title">
			How we Wordk						
		</div> -->
		<div class="title">
			<h2>
				Laters Online 
				<span>Cursess</span>							
			</h2>
		</div>
		<div class="card-container">
			<div class="card">

			</div>
			<div class="card">

			</div>
			<div class="card">

			</div>
		</div>
  </div>
</template>

<script>
export default {
  name: 'ServiceCard',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">	
	// /* eslint-disable */
	.container{
		width: 100%;
	
	}
	.sub-title{
		font-size: 16px;
		color: #e2e2e0;
		margin-bottom: 10px;
		span{
			color:#6c6c6b;
		}
	}
	.title{
			font-size: 25px;
			text-align: center;
			
			span{
				color: #1fad95;
			}
		}
			.testo{
				
				color: #6c6c6b;
				padding: 10px;
				div{
					margin-top: 40px;
				}
				strong{
				color: #000000;
				}
				
		}
		.card-container{
			margin-top: 50px;
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.card{
			width: calc(100% / 3 - 15%);
			height: 200px;
			margin-right: 25px;
			background-color: blue;
			border: 1px solid black;
		}
</style>