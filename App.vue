<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			// #ifdef MP-WEIXIN
				if(!wx.cloud){
					console.log('微信云服务错误')
				} else {
					console.log('进来了')
					wx.cloud.init({
						// traceUser:true,
						env: 'dev-fwi0n'
					})
				}
			// #endif

		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/* ColorUI */
    @import "colorui/main.css";
    @import "colorui/icon.css";
	
	/* 全局样式 */
	@import "static/app.css";
</style>
