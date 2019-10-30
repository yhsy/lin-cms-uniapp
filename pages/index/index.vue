<template>
	<view class="g-box">
		<view class="flex justify-start">
			<view class="text-area">
				<text class="title">{{title}}</text>
			</view>
		</view>
		<view class="flex justify-center">
			<image class="logo" src="/static/logo.png"></image>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style lang="scss">
	@import './index.scss'
</style>
