<template>
	<view >
		 <view class="status_bar"> 
		            <view class="top_view">
						<web-view src="https://shop.youlinyoushe.cn/app/index.php?i=1&c=entry&m=ewei_shopv2&do=mobile&v=143545&version=1" :webview-styles="webviewStyles"></web-view>
					</view> 
		        </view> 
			</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				webviewStyles: {
					progress:false
				}
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.status_bar { 
	    height: var(--status-bar-height); 
	    width: 100%; 
	    background-color: #F8F8F8; 
		position: fixed;
		top:0;left:0;
	} 
	.top_view { 
	    height: var(--status-bar-height); 
	    width: 100%; 
	    position: fixed; 
	    background-color: #F8F8F8; 
	    top: 0; 
	    z-index: 999; 
	}
</style>
