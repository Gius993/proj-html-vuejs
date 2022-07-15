<template>
  <div>
		<div class="information">
			<div class="text width-class">
				<div class="sub-title">
					Evertyng in 
					<span>MACCOACH</span>
				</div>
				<div class="title">
					<h2>
						Leard About our
						<span>Word Culture</span>
						at MaxCoach
					</h2>
				</div>
				<div class="testo">					
						Spend some time to visit our website or head office and discover our current couses, 
						enoliment procedure and registration 
						deadline.we're opening new classes e
						beginning of each month
						<div>have questions? <a href=""><strong>Get Free Guide</strong></a></div>	
				</div>
			</div>

			<div class="image width-class">

			</div>
		</div>
		<div class="dati">

		</div>
  </div>
</template>

<script>
export default {
  name: 'CardAtipe',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.information{
		width: 100%;
		display: flex;
		justify-content: center;
	}
	.width-class{
		width: calc(100% / 2);
		height: 500px;
		width: 500px;
		// background-color: aquamarine;
		border: 1px solid red;
	}
	.text{
		padding: 80px;
		.sub-title{
			font-size: 16px;
			color: #e2e2e0;
			margin-bottom: 20px;
			span{
				color:#6c6c6b;
			}
		}
		.title{
			font-size: 25px;
			margin-bottom: 20px;
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
				color: #1fad95;
				}
				
			}

	}
</style>