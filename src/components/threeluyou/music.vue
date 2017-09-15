<template>
	<div>
		<div class="topss iconfont icon-xiangzuojiantou" @click="gos()">返回</div>
		<div class="box">这是music页面</div>
	</div>
</template>
<script>
export default {
	name:"music"
}

</script>
<style>
*{
	background: yellow;
	font-size: 30px;
}
.box{
	position: fixed;
	top: 0;
	left: 0;
	z-index: 10;
}

</style>