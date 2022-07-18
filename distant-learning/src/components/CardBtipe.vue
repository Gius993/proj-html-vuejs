<template>
  <div>
		<div class="information">
			
			<div class="image width-class">
				<img src="../assets/img/stock-full-hd-11-670x450.jpg" alt="img">
				<img  class="posizione" src="../assets/img/icon-youtube-play.png" alt="img2">
			</div>
				<div class="text width-class">
					<div class="sub-title">
						How we Wordk
						
					</div>
					<div class="title">
						<h2>
							Upgrade Your Skills
							<span>Upgrade Your Life</span>
							
						</h2>
					</div>
					<div class="testo">					
							Opening up more opportunites in front of youy to get the ticket to more enjoyable door in life. Getting equipped 
							with new skills for new set of insights into yoit career MaxCoach accompany learnes in every stage of learning
							<div><a href=""><strong>Download free guidebook</strong></a></div>	
					</div>
				</div>
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
		// width: calc(100% / 2);
		width: 500px;
	
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
				color: #000000;
				}
				
			}

	}
	.image{
		display: flex;
		align-items: center;
		position: relative;
		.posizione{
			width: 50px;
			position:absolute;
			top: 50%;
			right: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
		}
	}
	.dati{
		display: flex;
		justify-content: center;
		.number{
			margin-left: 50px;
			.color-a{
				color: #1fad95;
				font-size: 50px;
				text-align: center;
			}
			.color-b{
				margin-top: 10px;
				color: #6c6c6b;
			}
		}
	
	}
</style>