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
					<img src="../assets/img/stock-full-hd-04-480x298.jpg" alt="img">
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
			// height: 200px;
			margin-right: 25px;
			// background-color: blue;
			// border: 1px solid black;
			background-color: white;
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

		// .image{
		// 	// width: 250px;
		// }
</style>