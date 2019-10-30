<template>
	<view class="g-box">
		<!-- 头部 -->
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
		<!-- 内容区域 -->
		<view class="g-bd">
			<view class="m-bd">
				<view class="title">
					<view class="u-tit">
						牛汽介绍
					</view>
					<view class="u-stit">
						About Niuqi
					</view>
					<view class="u-line">
						line
					</view>
				</view>
				<view class="i-about">
					<view class="img-box">
						<image class="img-about" src="../../static/img/index/img-about.jpg"></image>
					</view>
					<view class="about-con">
						浙江特浦科技有限公司成立于2016年，总部位于浙江省杭州市拱墅区，主要经营汽车保养套餐、常用件（事故件），拥有庞大的云数据库系统。牛汽是浙江特浦科技有限公司旗下一家互联网汽车后市场服务商，旨在结合移动互联网、 区块链、 大数据和人工智能等前沿技术，构建一个打通汽配供应链、 人才培训、 汽车保险、 汽车金融、 线上汽配APP和线下实体汽车养护中心为一体的新型车后服务平台，以全新的模式服务有车人！让汽配买卖变得更透明、便捷！
					</view>
					<view class="btn-more">
						MORE +
					</view>
				</view>
			</view>
			
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
