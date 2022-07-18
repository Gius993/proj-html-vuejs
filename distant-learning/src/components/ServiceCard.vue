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
				<div class="image">
					<img src="../assets/img/course-02-480x298.jpg" alt="img">
				</div>
				<div class="text">
					<div class="price">
						$40.00
					</div>
					<div class="description">
						Learning to Write as a Professional Author
					</div>
					<div class="class">
						<span>20 Leassons</span>
						<span>50 Student</span>
					</div>
				</div>
			</div>
			<div class="card">
				<div class="image">
					<img src="../assets/img/stock-full-hd-03-480x298.jpg" alt="img">
					<div class="free">
						FREE
					</div>
				</div>
				<div class="text">
					<div class="price">
						$0.00
					</div>
					<div class="description">
						Customer- centric-info-Tech Strategies
					</div>
					<div class="class">
						<span>24 Leassons</span>
						<span>750 Student</span>
					</div>
				</div>
			</div>
			<div class="card">
				<div class="image">
					<img src="../assets/img/stock-full-hd-04-480x298.jpg" alt="img">
				</div>
				<div class="text">
					<div class="price">
						$19.00
					</div>
					<div class="description">
						Open Programming Coursess for Everyone:Python
					</div>
					<div class="class">
						<span>17 Leassons</span>
						<span>62 Student</span>
					</div>
				</div>
			</div>
		</div>
		<div class="container-select">
			<div class="select">
			</div>
			<div class="select-grey">

			</div>
			<div class="select-grey">

			</div>
			<div class="select-grey">

			</div>
			<div class="select-grey">

			</div>
		</div>
		<div class="testo-finale">
			Control your prefernce setting to get notified appropiate
			cousess <strong>View all coursess &RightArrow;</strong>
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
	.free{
		width: 50px;
		height: 25px;
		background-color: #ee7455;
		color: white;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 10px;
		position: absolute;
		top: 0;
		right: 0;
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
			// height: 200px;
			margin-right: 25px;
			// background-color: blue;
			// border: 1px solid black;
			background-color: white;
			position: relative;
		}
		.card:hover{
			background-color: #e2e2e0;
		}
		.price{
			font-size: 30px;
			font-weight: bold;
			color: #1fad95;
			margin-top: 15px;
			margin-left: 20px;
		}
		.description{
			font-size: 20px;
			font-weight: 550;
			margin: 20px;
		}
.class{
			color: #6c6c6b;
			span{
				margin-left: 20px;
			}
}
.container-select{
	margin-top: 50px;
	display: flex;
	justify-content: center;
	align-items: center;
}
.select{
	width: 10px;
	height: 10px;
	border: 1px solid black;
	background-color: #000000;
	border-radius: 50%;
	margin-right: 15px;
}
.select-grey{
	width: 10px;
	height: 10px;
	border: 1px solid #d8d8d8;
	background-color: #d8d8d8;
	border-radius: 50%;
	margin-right: 15px;
}
.testo-finale{
	text-align: center;
	margin: 20px;
}
		// .image{
		// 	// width: 250px;
		// }
</style>