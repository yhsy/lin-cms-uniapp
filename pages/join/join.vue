<template>
	<view class="g-box">
		<view class="g-hd">
			<view class="m-video">
				<video 
				src="https://niuqipei-video.oss-cn-hangzhou.aliyuncs.com/xuanchuan700.mp4" 
				class="u-video"
				controls></video>
			</view>
			<!-- 			
				<view class="m-banner">
					<image src="../../static/img/join/ban-join.jpg" mode=""></image>
				</view>
			-->
		</view>
		<view class="g-bd">
			
		</view>
		<i-footer></i-footer>
	</view>
</template>

<script>
	import iFooter from '../../components/footer/footer.vue'
	
	export default {
		components: {
			iFooter
		},
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
@import './join.scss'
</style>
