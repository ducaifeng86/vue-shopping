<template>
	<div>
		<div>
			<h2>全部产品</h2>
			<template v-for="product in productList">
				<h3>{{product.title}}</h3>
				<ul>
					<li v-for="item in product.list">
						<a :href="item.urlVal">{{item.name}}</a>
					</li>
				</ul>
				<div class="hr" style="border: 1px solid red;"></div>
			</template>
		</div>
		<div>
			<h2>最新消息</h2>
			<ul>
				
			</ul>
		</div>
	</div>
</template>

<script>
	export default{
		data(){
			return {
				productList:{
					pc:{
						title:'PC产品',
						list:[
							{
								title:'',
								urlVal:''
							}
						]
					},
					app:{
						title:'应用类',
						list:[
							{
								title:'',
								urlVal:''
							}
						]
					}
				}
			}
		}
	}
</script>

<style>
</style>