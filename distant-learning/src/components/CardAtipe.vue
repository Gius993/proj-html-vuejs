<template>
  <div class="container-a">
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
				<div class="style-c">
					<img src="../assets/img/maxcoach-shape-02.png" alt="style">
				</div>
			</div>

			<div class="image width-class">
				<img src="../assets/img/stock-full-hd-10-ohki1ayywq3cqutettrncduujpoaorifqu4relt2ts.jpg" alt="img">
				<img  class="posizione" src="../assets/img/about-us-01-ohkia3qg98rq9vg3s0mn2hkflr1migdqdw370qnegc.jpg" alt="img2">
			</div>
		</div>
		<div class="dati">
			<div class="number">
				<div class="color-a"><strong>129+</strong></div>
				<div class="color-b">ENROLED LEARNS</div>
			</div>
			<div class="number">
				<div class="color-a"><strong>80</strong></div>
				<div class="color-b">FINISHED SESSIONS</div>
			</div>
			<div class="number">
				<div class="color-a"><strong>4%</strong></div>
				<div class="color-b">SATISFACTION RATE</div>
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
		padding-top: 50px;
	}
	.container-a{
		padding-bottom: 100px;

	}
	.style-c{
		width: 100px;
		position: absolute;
		bottom: 10%;
		left: 10%;
	}
	.width-class{
		// width: calc(100% / 2);
		width: 500px;
	
	}
	.text{
		padding: 80px;
		position: relative;
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
	.image{
		display: flex;
		align-items: center;
		position: relative;
		.posizione{
			width: 150px;
			border-radius: 10px;
			position:absolute;
			top: 0;
			right: -50px;
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