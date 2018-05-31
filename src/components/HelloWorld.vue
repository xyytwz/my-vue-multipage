<template>
	<div class="hello">
		<h3>主页</h3>
		<ul>
			<li>
				<a href="./login.html">
					登陆
				</a>
			</li>
			<li>
				<a href="./user.html">
					用户中心
				</a>
			</li>
		</ul>
	</div>
</template>

<script>
	export default {
		name: 'HelloWorld',
		data() {
			return {
				
			}
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	h3 {
		font-weight: normal;
		text-align: center;
	}
	
	ul {
		list-style-type: none;
		padding: 0;
	}
	
	li {
		margin: 0 10px;
		text-align: center;
	}
	
	a {
		color: #42b983;
		text-decoration: none;
	}
</style>