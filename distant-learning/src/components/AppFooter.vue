<template>
<div class="container-footer">
	<div class="container-menu">
			<div class="address">
		<ul>
			<li>382 NE 191ist St# 97394 Miami, Fl 33179-3899</li>
			<li>+1(382)  33179-3899</li>
			<li>support@maxcoach.com</li>
		</ul>
		<div class="social">
			<ul>
				<li><img src="../assets/img/instagram-2-512.png" alt="img"></li>
				<li><img src="../assets/img//facebook-3-512.png" alt="img"></li>
				<li><img src="../assets/img/twitter-4-512.png" alt="img"></li>
				
			</ul>
		</div>
	</div>
	<!--list-->
  <div class="list-footer">
	<ul>
		<h3>Explore</h3>
		<li v-for="link, index in menuLista" :key="index">
			<a href="#">{{ link.text }}</a>
		</li>									
	</ul>
	<ul>
		<li v-for="two, index in menuListaB" :key="index">
			<a href="#">{{ two.text }}</a>
		</li>
	</ul>
	<ul>
		<h3>Information</h3>
		<li v-for="tree, index in menuListaC" :key="index">
			<a href="">{{ tree.text }}</a>
		</li>
	</ul>
   </div>
  </div>
	<div class="text-st">
		<p>@ 2020 Maxcoach. All rights Reserved</p>
	</div>
 </div>
</template>

<script>
	export default {
		name: "AppFooter",
		data(){
			return{
				menuLista:[
					{
						text:'Start here',
						url: '#',
						current: true
					},
						{
						text:'Blog',
						url: '#',
						current: true
					},
						{
						text:'About us',
						url: '#',
						current: true
					},
											
				],
				menuListaB:[
						{
						text:'Success story',
						url: '#',
						current: true
					},
						{
						text:'Coursess',
						url: '#',
						current: true
					},
						{
						text:'Contact us',
						url: '#',
						current: true
					},
				],
				menuListaC:[
						{
						text:'Membership',
						url: '#',
						current: true
					},
						{
						text:'Punchase guide',
						url: '#',
						current: true
					},
					{
						text:'Privacy Policy',
						url: '#',
						current: true
					},
					{
						text:'Team of service',
						url: '#',
						current: true
					},
				],
			}
		}
  }

</script>

<style lang="scss" scoped>
.container-footer{
	background-color: #171621;
	padding-top: 55px;
	padding-bottom: 55px;
	h3{
		color: white;
	}
	li{
		color: #9dabab;		
	}
}
.container-menu{
	display: flex;
	justify-content: space-evenly;
	align-items: center;
}
.social{
	margin-top: 25px;
	ul{
		display: flex;
		
	}
	li{
		width: 25px;
		margin-left: 20px;
	}
}
.list-footer{
	display: flex;
	align-items: center;
	a{
		color: #9dabab;		
	}
	li{
		// padding-right: 20px;
		font-size: 16px;
		margin-right: 10px;
		margin-top: 10px;
	}
	ul{
		margin-right: 35px;
	}
}
.address{
	text-align: start;
}
.text-st{
	color: #9dabab;
	text-align: center;
	font-size: 15px;
	margin-top: 25px;
}
</style>