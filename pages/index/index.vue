<template>
	<view class="g-box">
		<view class="g-hd">
			<swiper class="m-banner" 
				:indicator-dots="swiper.indicatorDots" 
				:indicator-color="swiper.indicatorColor"
				:indicator-active-color="swiper.indicatorActiveColor"
				:autoplay="swiper.autoplay" 
				:interval="swiper.interval" 
				:duration="swiper.duration"
			>
				<swiper-item class="swiper-item">
					<image src="../../static/img/index/ban-index1.jpg" mode=""></image>
				</swiper-item>
				<swiper-item class="swiper-item">
					<image src="../../static/img/join/ban-join.jpg" mode=""></image>
				</swiper-item>
				<swiper-item class="swiper-item">
					<image src="../../static/img/job/ban-job.jpg" mode=""></image>
				</swiper-item>
			</swiper>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				// 轮播图配置
				swiper:{
					// 是否显示面板指示点
					indicatorDots: true,
					// 指示点颜色
					indicatorColor: "#333",
					// 当前选中的指示点颜色
					indicatorActiveColor: "#fff",
					// 是否自动切换
					autoplay: true,
					// 自动切换时间间隔
					interval: 2000,
					// 滑动动画时长
					duration: 500
				}
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
