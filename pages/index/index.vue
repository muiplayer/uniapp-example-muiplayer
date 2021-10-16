<template>
	<view class="content">
		<button type="primary" size="mini" @click="goto('/pages/about/about')">通过方法跳转到about页面</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		onLoad() {

		},
		methods: {
			goto(url) {
				uni.navigateTo({
					url:"../player/index"
				})
			}
		}
	}
</script>

<style>
	.content {
		display: flex;
		align-items: center;
		padding-top: 100rpx;
	}
</style>
