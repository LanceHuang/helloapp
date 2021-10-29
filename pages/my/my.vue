<template>
	<view class="content">
		{{msg}}
	</view>
</template>

<script>
	export default {
		data() {
			return {
				msg: "Hello 我的"
			}
		},
	}
</script>

<style>
	.content {
		font-size: 20px;
		text-align: center;
	}
</style>
