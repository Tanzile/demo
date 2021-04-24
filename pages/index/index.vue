<template>
	<view class="box">
		<view class="nr">
			<view class="bt">
				<view class="active">
					全部
				</view>
				<view>
					待下单
				</view>
				<view>
					待结算
				</view>
				<view>
					已结算
				</view>
				<view>
					已作废
				</view>
			</view>
			<view class="list">
				<view class="list_bt">
					<view class="list_left">
						<image src="../../static/comein.png" mode=""></image>
						<text>cdf会员购北京</text>
						<image src="../../static/5V3)UBFEOA4H(EH0X4EWODX.png" mode=""></image>
					</view>
					<view class="list_r">
						<image src="../../static/3S%5B@K)$J%25TG1AA_G287HBH9.png" mode=""></image>
					</view>
				</view>
			</view>
			<view class="list_box">
				<view class="img">
					<image src="../../static/(ITPZGL%7BR8_Q%60ANST)5D2@M.png" mode=""></image>
				</view>
				<view class="text">
					<view class="text1">肌肤之钥光凝前霜37ML×2</view>
					<view class="text2">创建时间:2020-09-01 17:22:03</view>
					<view class="text2">锁单时间:2020-09-0117:22:03</view>
					<view class="text3">
						<text class="text2">支付时间:</text>
						<text class="but">去支付订单></text>
					</view>
				</view>
				<view class="jg">
					￥178.00
				</view>
				<view class="zl">
					再来一单
				</view>
				<view class="jf">
					分享得500积分
				</view>
			</view>
			<view class="list_box">
				<view class="img">
					<image src="../../static/(ITPZGL%7BR8_Q%60ANST)5D2@M.png" mode=""></image>
				</view>
				<view class="text">
					<view class="text1">肌肤之钥光凝前霜37ML×2</view>
					<view class="text2">创建时间:2020-09-01 17:22:03</view>
					<view class="text2">锁单时间:2020-09-0117:22:03</view>
					<view class="text3">
						<text class="text2">支付时间:</text>
						<text class="but">去支付订单></text>
					</view>
				</view>
				<view class="jg">
					￥178.00
				</view>
				<view class="zl">
					再来一单
				</view>
				<view class="jf">
					分享得500积分
				</view>
			</view>
			<view class="list_box">
				<view class="img">
					<image src="../../static/(ITPZGL%7BR8_Q%60ANST)5D2@M.png" mode=""></image>
				</view>
				<view class="text">
					<view class="text1">肌肤之钥光凝前霜37ML×2</view>
					<view class="text2">创建时间:2020-09-01 17:22:03</view>
					<view class="text2">锁单时间:2020-09-0117:22:03</view>
					<view class="text3">
						<text class="text2">支付时间:</text>
						<text class="but">去支付订单></text>
					</view>
				</view>
				<view class="jg">
					￥178.00
				</view>
				<view class="zl">
					再来一单
				</view>
				<view class="jf">
					分享得500积分
				</view>
			</view>
			<view class="list">
				<view class="list_bt">
					<view class="list_left">
						<image src="../../static/comein.png" mode=""></image>
						<text>cdf会员购北京</text>
						<image src="../../static/5V3)UBFEOA4H(EH0X4EWODX.png" mode=""></image>
					</view>
					<view class="list_r">
						<image src="../../static/3S%5B@K)$J%25TG1AA_G287HBH9.png" mode=""></image>
					</view>
				</view>
			</view>
			<view class="list_box">
				<view class="img">
					<image src="../../static/(ITPZGL%7BR8_Q%60ANST)5D2@M.png" mode=""></image>
				</view>
				<view class="text">
					<view class="text1">肌肤之钥光凝前霜37ML×2</view>
					<view class="text2">创建时间:2020-09-01 17:22:03</view>
					<view class="text2">锁单时间:2020-09-0117:22:03</view>
					<view class="text3">
						<text class="text2">支付时间:</text>
						<text class="but">去支付订单></text>
					</view>
				</view>
				<view class="jg">
					￥178.00
				</view>
				<view class="zl">
					再来一单
				</view>
				<view class="jf">
					分享得500积分
				</view>
			</view>
		</view>
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

		}
	}
</script>

<style>
	page {
		background: #ccc;
	}

	.box {
		width: 100%;
		height: 100%;
	}

	.bt {
		width: 100%;
		display: flex;
		height: 47px;
		line-height: 47px;
		justify-content: space-evenly;
		background: #fff;
	}

	.list {
		position: relative;
		margin: 0 auto;
		margin-top: 10px;
		width: 355px;
		height: 50px;
		border: 1px solid #ccc;
		background: #fff;
		border-radius: 8px 8px 0 0;
	}

	.list_left {
		position: absolute;
		width: 100%;
		height: 50px;
		line-height: 50px;
		border-bottom: 1px solid #ccc;
		display: flex;
	}

	.list_left>image:nth-child(1) {
		width: 20px;
		height: 20px;
		margin-top: 15px;
		margin-left: 10px;
		margin-right: 5px;

	}

	.list_left>text {
		font-size: 13px;
	}

	.list_left>image:nth-child(3) {
		width: 20px;
		height: 25px;
		margin-top: 12px;
		margin-left: 3px;
	}

	.list_r {
		position: absolute;
		right: 20px;
	}

	.list_r>image {
		width: 60px;
		height: 50px;
	}

	.active {
		border-bottom: 4px solid #F0AD4E;
		border-radius: 1px;
		color: #F0AD4E;
	}

	.list_box {
		position: relative;
		margin: 0 auto;
		width: 355px;
		height: 190px;
		border: 1px solid #ccc;
		background: #fff;
		border-radius: 0 0 8px 8px;
	}

	.img>image {
		width: 80px;
		height: 80px;
	}

	.text1 {
		font-size: 13px;
	}

	.text2 {
		font-size: 12px;
		color: #ccc;
		margin-top: 5px;
	}

	.text3 {
		margin-top: 5px;
		font-size: 12px;
	}

	.but {
		padding: 3px;
		background-color: #DD524D;
		border-radius: 11px;
		color: pink;
		margin-left: 3px;
	}

	.img {
		position: absolute;
		top: 10px;
		left: 15px;
	}

	.text {
		position: absolute;
		top: 15px;
		left: 104px;
	}

	.jg {
		position: absolute;
		font-size: 14px;
		font-weight: bold;
		right: 10px;
		top: 15px;
	}

	.zl {
		position: absolute;
		width: 80px;
		height: 30px;
		text-align: center;
		line-height: 30px;
		border-radius: 15px;
		border: 2px solid #000;
		top: 130px;
		left: 140px;
	}

	.jf {
		position: absolute;
		width: 120px;
		height: 30px;
		text-align: center;
		line-height: 30px;
		border-radius: 15px;
		border: 2px solid #F0AD4E;
		color: #F0AD4E;
		top: 130px;
		left: 230px;
	}
</style>
