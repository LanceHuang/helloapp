<template>
	<view class="container">
		<view class="content">{{msg}}</view>

		<navigator url="/pages/find/find" open-type="switchTab">
			<button type="primary">Click</button>
		</navigator>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				msg: "Hello 微信"
			}
		}
	}
</script>

<style>
	.content {
		font-size: 20px;
		text-align: center;
	}
</style>
