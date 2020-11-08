<template>
	<view class="top_bar">
		<view class="top-l">
			<view class="">
				推荐
			</view>
			<view class="uipt">
				
				
			</view>
			<view class="image_">
				<image src="../../static/icon/paihangbang.png" mode="concv"></image>
			</view>
		</view>
	</view>
</template>

<script>
	
	export default {
		mounted:function(){
			console.log("肯定是看看")
		}
	}
</script>

<style land='sass'>
	.top_bar{
		width: 100%;
		border: 1rpx red solid;
	}
	.top-l{
		display: flex;
		justify-content: space-between;
		align-items: center;
		border: 1px solid #007AFF;
	}
	.image_{
		width: 100px;
		image{
		width: 100rpx;
		height: 100rpx;
		border: #1AAD19 solid 1rpx;
		}
	}
	.image_ image{
		width: 100rpx;
		height: 100rpx;
		border: #1AAD19 solid 1rpx;
	}
</style>
