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
						<div> <a href=""><strong>View all &RightArrow;</strong></a></div>	
				</div>
			</div>

			<div class="image width-class">
				<div class="posizione caratteristiche">

				</div>		
			</div>
		</div>
	
  </div>
</template>

<script>

export default {
  name: 'TestimonialCard',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.information{
		width: 100%;
		display: flex;
		justify-content: center;
		padding-top: 50px;
	}
	.width-class{
		width: calc(100% / 2 - 15%);
		// height: 500px;		
		// width: 500px;	
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
				color: black;
				}
				
			}

	}
	.image{
		// display: flex;
		// align-items: center;
		height: 500px;
		background-color: #1fad95;
		position: relative;
		.posizione{
			position:absolute;
			top: 50%;
			right: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
		}
		.caratteristiche{
			width: 120%;
			height: 75%;
			background-color: blueviolet;
		}
	}

</style>