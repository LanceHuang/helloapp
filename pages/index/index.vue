<template>
	<view class="content">
		<!-- #ifdef H5 -->
		<image src="../../static/img1.png" mode="widthFix"></image>
		<!-- #endif -->
		
		<!-- #ifdef MP-WEIXIN -->
		<image src="../../static/img2.png" mode="widthFix"></image>
		<!-- #endif -->
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
	}
</script>

<style>
	.content {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
