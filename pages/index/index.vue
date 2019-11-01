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
			<!-- 牛汽介绍 -->
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
			<!-- 牛汽产品 -->
			<view class="m-bd">
				<view class="title">
					<view class="u-tit">
						牛汽产品
					</view>
					<view class="u-stit">
						Niuqi Product
					</view>
					<view class="u-line">
						line
					</view>
				</view>
				<view class="g-product">
					<view class="i-product">
						<view class="">
							<view class="pro-img">
								<image src="../../static/img/index/icon-p1.png" mode=""></image>
								<!-- <text>牛汽商城</text> -->
							</view>
						</view>
						<view class="pro-con">
							<view class="pro-tit">
								牛汽商城
							</view>
							<view class="pro-desc">
								让汽配买卖更透明，多、快、好、省的解决您的养车和修车问题!
							</view>
							<view class="btn-detail">
								查看详情 >>
							</view>
						</view>
					</view>
					<view class="i-product">
						<view class="">
							<view class="pro-img">
								<image src="../../static/img/index/icon-p2.png" mode=""></image>
							</view>
						</view>
						<view class="pro-con">
							<view class="pro-tit">
								牛家店
							</view>
							<view class="pro-desc">
								牛汽在线下为客户建立的社区级消费终端，有车人可就近享受优质服务！
							</view>
							<view class="btn-detail">
								查看详情 >>
							</view>
						</view>
					</view>
					<view class="i-product">
						<view class="">
							<view class="pro-img">
								<image src="../../static/img/index/icon-p3.png" mode=""></image>
							</view>
						</view>
						<view class="pro-con">
							<view class="pro-tit">
								车险白条
							</view>
							<view class="pro-desc">
								车险白条是牛汽合作伙伴，买车险分10期免息，0利息0手续费！
							</view>
							<view class="btn-detail">
								查看详情 >>
							</view>
						</view>
					</view>
				</view>
			</view>
			<!-- 服务案例 -->
			<view class="m-bd">
				<view class="title">
					<view class="u-tit">
						服务案例
					</view>
					<view class="u-stit">
						Service Case
					</view>
					<view class="u-line">
						line
					</view>
				</view>
				
				<view class="g-service">
					<view class="i-service">
						<image class="img-case" src="../../static/img/index/img-case1.jpg" mode=""></image>
						<view class="u-mask">
							<view class="name">
								某集团王总-英菲尼迪维修案例
							</view>
							<view class="cont">
								王总的英菲尼迪维修养护4S店报价<text>52000元</text>，通过牛汽养车平台下单全面维修，花费<text>17000元</text>，立省<text>35000元</text>
							</view>
						</view>
					</view>
					<view class="i-service">
						<image class="img-case" src="../../static/img/index/img-case2.jpg" mode=""></image>
						<view class="u-mask">
							<view class="name">
								某公司张先生-奥迪Q5维修案例
							</view>
							<view class="cont">
								张先生的奥迪Q5变速箱油冷却阀断路，发动机控制单元的转速不可信信号，由于离合器温度造成扭矩受限，变速箱油冷却阀对正极短路，冷却油阀电气故障。奥迪4S店报价<text>32000元</text>，，牛汽养车仅仅花费<text>13800元</text>
							</view>
						</view>
					</view>
				</view>
			</view>
			
			<!-- 新闻动态 -->
			<view class="m-bd">
				<view class="title">
					<view class="u-tit">
						新闻动态
					</view>
					<view class="u-stit">
						Niuqi News
					</view>
					<view class="u-line">
						line
					</view>
				</view>
				<view class="g-news">
					<view class="i-news">
						<view class="tit">
							恭贺牛汽配帮购中心“牛大帮购”成立
						</view>
						<view class="img-news">
							<image src="../../static/img/index/img-news.jpg" mode=""></image>
						</view>
						<view class="btn-more">
							MORE +
						</view>
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
			// #ifdef MP-WEIXIN
				// 小程序--云数据库使用
				const db = wx.cloud.database();
				db.collection('banner').get({
					success: res => {
						console.log('返回成功')
						console.log(res)
					},
					fail: err => {
						console.log('错误')
					}
				});
			// #endif
		},
		methods: {

		}
	}
</script>

<style lang="scss">
	@import './index.scss'
</style>
