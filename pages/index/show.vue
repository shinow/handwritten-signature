<template>
	<view class="container">
		<image class="sign" :src="src">
	</view>
</template>

<script>
	export default {
		onLoad: function(option) {
			this.src = option.src
			console.log(option.src)
		},
		data() {
			return {
				src: ''
			}
		},
		methods: {

		}
	}
</script>

<style>
	.container {
		padding-top: 20upx;
		padding-bottom: 100upx;
		box-sizing: border-box;
	}
	.sign {
		background-color: #DDDDDD;
		width: 700upx;
		margin: 0 25upx;
		height: calc(100vh - 140upx);
	}
</style>
