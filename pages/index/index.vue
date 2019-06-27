<template>
	<view class="index-page flex flex-direction justify-between">
		<view class="logo text-white flex-direction flex align-center">
			<text class="disapand-valo-cars" style="font-size: 96upx;"></text>
			<view class="logo-text margin-top"></view>
		</view>
		<view class="action-bar flex flex-direction align-center">
			<view class="flex">
				<view class="wx-btn bg-blue flex align-center justify-center bg-blue">
					<text class="disapand-qq margin-right" style="font-size: 44upx;"></text>
					<text style="font-size: 40upx;">QQ登录</text>
				</view>
				<view class="qq-btn bg-green flex align-center justify-center bg-green">
					<text class="disapand-wechat margin-right" style="font-size: 44upx;"></text>
					<text style="font-size: 40upx;">微信登录</text>
				</view>
			</view>
			<view class="flex align-center margin-30">
				<view class="line margin-right"></view>
				<view class="text-30">
					或者使用手机号/邮箱登录
				</view>
				<view class="line margin-left"></view>
			</view>
			<view class="phone-btn flex align-center justify-center text-white">
				手机号/邮箱登录
			</view>
		</view>
	</view>
</template>
<script>
export default {
	data() {
		return {};
	},
	methods: {}
};
</script>
<style scoped lang="scss">
.index-page {
	width: 100vw;
	height: 100vh;
	background: url(http://ptasjbugg.bkt.clouddn.com/Login.jpg);
	background-repeat: no-repeat;
	background-size: cover;
	overflow: hidden;

	.logo {
		margin-top: 238upx;
		.logo-text {
			height: 66upx;
			width: 380upx;
			background: url('http://ptasjbugg.bkt.clouddn.com/Vola Cars@2x.png');
			background-repeat: no-repeat;
			background-size: cover;
		}
	}
	
	.action-bar {
		margin-bottom: 70upx;
		.wx-btn, .qq-btn {
			width: 330upx;
			height: 110upx;
			border-radius: 2000upx;
			margin: 0 12upx;
		}
		
		.phone-btn {
			height: 110upx;
			width: 684upx;
			border-radius: 2000upx;
			border: solid 1px rgba(255, 255, 255, .3);
			background: rgba(0, 0, 0, .5)
		}
		
		.line {
			height: 2upx;
			width: 120upx;
			background: rgba(255, 255, 255, .3);
		}
		
		.text-30 {
			color: rgba(255, 255, 255, .3);
		}
		
		.margin-30 {
			margin: 60upx 0;
		}
	}
}
</style>
