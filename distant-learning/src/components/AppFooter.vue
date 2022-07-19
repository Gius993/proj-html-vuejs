<template>
<div class="container">
	<!--list-->
  <div class="list-footer">
	<ul>
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
		<li v-for="tree, index in menuListaC" :key="index">
			<a href="">{{ tree.text }}</a>
		</li>
	</ul>
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
											
				],
				menuListaB:[
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
				],
				menuListaC:[
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
				],
			}
		}
  }

</script>

<style lang="scss">
.container{
	background-color: #171621;
	h3{
		color: white;
	}
}
.list-footer{
	a{
		color: #9dabab;		
	}
	li{
		// padding-right: 20px;
		font-size: 16px;
		margin-right: 10px;
	}
}
</style>