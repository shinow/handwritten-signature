<template>
	<view class="container">
		<image :src="src">
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
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
