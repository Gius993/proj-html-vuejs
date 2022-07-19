<template>
  <div class="container">
		<!-- <div class="sub-title">
			How we Wordk						
		</div> -->
		<div class="title">
			<h2>
				Laters From
				<span>Online Blogs</span>							
			</h2>
		</div>
		<div class="card-container">
			<div class="card">
				<div class="image">
					<img src="../assets/img/artist-blog-03-480x325.jpeg" alt="img">
				</div>
				<div class="text">
					<div class="price">
						Artist
					</div>
					<div class="description">
						Brush strokes energize trees in paintings
					</div>
					<div class="class">
						<span>May 15, 2020</span>
						<span>688 views</span>
					</div>
				</div>
			</div>
			<div class="card">
				<div class="image">
					<img src="../assets/img/artist-blog-01-480x325.jpg" alt="img">
					
				</div>
				<div class="text">
					<div class="price">
						Artist
					</div>
					<div class="description">
						Pocket-Sized notebooks hold miniature paintings
					</div>
					<div class="class">
						<span>May 15, 2020</span>
						<span>750 Views</span>
					</div>
				</div>
			</div>
			<div class="card">
				<div class="image">
					<img src="../assets/img/artist-blog-02-480x325.jpg" alt="img">
				</div>
				<div class="text">
					<div class="price">
						Artist
					</div>
					<div class="description">
						connection Between Self-Portaits and identity
					</div>
					<div class="class">
						<span>May 15, 2020</span>
						<span>397 Views</span>
					</div>
				</div>
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
		padding-bottom: 15px;
		padding-top: 150px;
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
			margin-right: 25px;		
			background-color: white;
		}
		.card:hover{
			background-color: #e2e2e0;
		}
		.price{
			font-size: 15px;
			// font-weight: bold;
			color: #6c6c6b;
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

</style>