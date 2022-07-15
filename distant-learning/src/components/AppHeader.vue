<template>
	<div>
		<div class="container-header">	

			<!--list-->
			<div class="list-branding">
				<ul>
					<li v-for="link, index in menuList" :key="index">
						<a href="#">{{ link.text }}</a>
					</li>									
				</ul>
			</div>

			<div class="logo">
				<img src="../assets/img/dark-logo.png" alt="logo">
			</div>

			<div class="utent-app">
				<div class="car">
					<img src="../assets/img/Carrello.svg" alt="car">
				</div>
				<div class="user">
					<img src="../assets/img/utent.svg" alt="user">
				</div>
				<div class="search">
					<div>
						<input type="text">
					</div>
					<div class="lente">
						<img src="../assets/img/search.svg" alt="search">
					</div>
				
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		name: "AppHeader",
		data(){
			return{
				menuList:[
					{
						text:'Home',
						url: '#',
						current: true
					},
						{
						text:'Pages',
						url: '#',
						current: true
					},
						{
						text:'Courses',
						url: '#',
						current: true
					},
						{
						text:'Features',
						url: '#',
						current: true
					},
						{
						text:'Blog',
						url: '#',
						current: true
					},
						{
						text:'Shop',
						url: '#',
						current: true
					},
						
				]
			}
		}
  }

</script>

<style lang="scss">

.list-branding{
	a{
		color: black;		
	}
	ul{
		display: flex;		
	}
	li{
		// padding-right: 20px;
		font-size: 16px;
		margin-right: 10px;
	}
}
.utent-app{
	display: flex;
	align-items: center;
}
.car{
	width: 20px;
	margin-right: 10px;
}
.user{
	width: 20px;
	margin-right: 10px;
}
.logo{
	width: 120px;	
}
.lente{
	width: 15px;
	padding: 1px;
}

.search{
	display: flex;
	align-items: center;
	background-color: #e2e2e0;
	input{
		background-color: #e2e2e0;
		border: none;
		resize: none;
		outline: none;
		padding: 2px;
	}
}
.container-header{
	padding-top: 15px;
	padding-bottom: 15px;
	display: flex;
	align-items: center;
	justify-content: space-around;
}
</style>