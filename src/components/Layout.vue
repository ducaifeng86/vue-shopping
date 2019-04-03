<template>
	<div>
		<header>
			<ul>
				<li>退出</li>
				<li>登录</li>
				<li>注册</li>
				<li>关于</li>
			</ul>
		</header>
		<section>
			<keep-alive>
				<router-view></router-view>
			</keep-alive>
		</section>
		<footer>
			底部
		</footer>
	</div>
</template>

<script>
	export default{
		
	}
</script>

<style>
	
</style>