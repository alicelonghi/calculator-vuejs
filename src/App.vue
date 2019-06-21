<template>
	<div id="app">
		<h1>Calculator in Vue </h1>
		<Calculator />
	</div>
</template>
<script>
	import Calculator from "./main/Calculator"
	export default {
		components: { Calculator }
	}
</script>


<style>
	@import url('https://fonts.googleapis.com/css?family=Oswald:300,400,500,600,700&display=swap');
	* {
		font-family: 'Oswald', sans-serif;
	}

	body {
		margin: 0;
	}

	#app {
		display: flex;
		flex-direction: column;
		height: 100vh;
		justify-content: center;
		align-items: center;
		text-align: center;
		color: #444;
		background: linear-gradient(to top, #fff1eb 0%, #ace0f9 100%);
	}
</style>