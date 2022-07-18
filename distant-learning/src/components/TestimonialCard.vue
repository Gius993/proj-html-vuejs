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
				<div class="text-a">
					<div><strong>The MaxCoach team realliy hard to ensure hight level of quality</strong>
						I am happy with their arrangement of lessons and subject they 
					</div>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum cum inventore quis quo at cumque. Labore molestias animi 
					laboriosam sequi quae! Consequuntur possimus suscipit nisi quaerat fugit repellat atque voluptas?

				</div>
				<div class="posizione caratteristiche">

				</div>		
				<div class="text-b">
					<div class="image-c">
						<img src="../assets/img/testimonial-avata-02.jpg" alt="inmg">
					</div>
					<div class="name">
						<h3>Mina Hollace</h3>
						<p>/Freelancer</p>
					</div>
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
		// opacity: 0.6;	
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
			background-color: rgba(255, 255, 255, 0.925);
		}
	}
.text-a{
	padding: 15px;
	opacity: 0.4;	
	div{
		// margin-bottom: 15px;
	}
}
.text-b{
padding-left: 3px;
padding-right: 3px;
position: absolute;
bottom: 0px;
display: flex;
opacity: 0.4;	

h3{
	font-size: 15px;
}
p{
	font-size: 10px;
	color:#747474;
}
}
.image-c{
	width: 40px;
	height: 40px;
	margin-right: 15px;
	border-radius: 50%;
	overflow: hidden;
	img{
	width: 100%;
	height: 100%;
	object-fit: cover;
	}
}
</style>