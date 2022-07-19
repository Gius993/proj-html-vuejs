<template>
  <div>
		<div class="information">
			
			<div class="image width-class">
				<img src="../assets/img/home-3-team-image.png" alt="img">
				<!-- <img  class="posizione" src="../assets/img/icon-youtube-play.png" alt="img2"> -->
			</div>
				<div class="style-a">
					<img src="../assets/img/maxcoach-shape-05.png" alt="style">
				</div>
				<div class="style-b">
					<img src="../assets/img/maxcoach-shape-07.png" alt="style">
				</div>
				<div class="text width-class">
					<div class="sub-title">
						How we Wordk
						
					</div>
					<div class="title">
						<h2>
							We're Here To
							<span>Transorm</span>
							You!
						</h2>
					</div>
					<div class="testo">					
							As learners,people can enjoy great companionship from MaxCoach mentors and educators.We help you develolop
							and grow at your beast.
							<div class="button"><a href="">Get Free Guide</a></div>	
					</div>
				</div>
		</div>
		
  </div>
</template>

<script>
export default {
  name: 'CardBtipe',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	.information{
		width: 100%;
		padding-bottom: 60px;
		display: flex;
		justify-content: center;
		position: relative;
	}
	.style-a{
		width: 100px;
		position: absolute;
		bottom: 0;
		left: 25%;
	}.style-b{
		width: 100px;
		position: absolute;
		right: 20%;
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
.button a{
	color:white;
	background-color: #1fad95;
	width: max-content;
	border: 1px solid #1fad95;
	border-radius: 5px;
	padding-top: 15px;
	padding-bottom: 15px;
	padding-left: 55px;
	padding-right: 55px;
	font-size: 10px;
}
</style>