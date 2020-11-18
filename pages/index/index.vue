<template>
	<view class="container">
		<view class="content">
			<!-- 顶部搜索框 -->
			<view class="searchInput">
				<uni-icons color="#999999" size="18" type="search" />
				<input type="text" value="" placeholder="网上办事指南" placeholder-class="placeholder" bindinput="handleChange" />
			</view>
			<view class="contentList1">
				<ul >
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>交通违法</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
					<li class="">
						<image src="../../static/images/logo.png" mode=""></image>
						<p>社保</p>
					</li>
				</ul>
			</view>
		</view>
		<view class="content">
			<div class="imgList">
				<p>部门服务</p>
			</div>
			<div class="imgList">
				<p>部门服务</p>
			</div>
			<div class="imgList">
				<p>部门服务</p>
			</div>
			<div class="imgList">
				<p>部门服务</p>
			</div>
		</view>
		
		<view class="content">
			<div class="notice">
				<i class="icon-tongzhi"></i>
			</div>
		</view>

	</view>
</template>

<script>
	export default {
		components: {},
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

<style lang="less" scoped>
	page {
		background-color: #f4f4f4;
	}

	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.content {
		width: 100%;
		background-color: #FFFFFF;
		margin-bottom: 20rpx;
		padding: 20rpx;
	}

	/* 顶部搜索框 */
	.searchInput {
		position: relative;
		height: 60rpx;
		line-height: 60rpx;
		background: #F2F2F2;
		border-radius: 10rpx;
		margin: 20rpx;
		padding-left: 10rpx;
	}

	.searchInput input {
		position: absolute;
		top: 0;
		right: 0;
		width: 90%;
		height: 60rpx;
		line-height: 60rpx;
	}

	.searchInput .searchIcon {
		position: absolute;
		left: 10rpx;
		font-size: 30rpx;
	}

	.contentList1 {
		ul {
			padding: 40rpx;
			li {
				width: 120rpx;
				display: inline-block;
				margin: 20rpx;
				image{
					width: 120rpx;
					height: 120rpx;
					margin: 0 auto;
					border-radius: 100%;
				}
				p{
					text-align: center;
				}
			}

		}
	}
	.imgList{
		display: inline-block;
		width: 320rpx;
		height: 200rpx;
		background:url(../../static/images/example.jpg) 100%;
		border-radius: 20rpx;
		margin: 10rpx 26rpx;
		p{
			width: 100%;
			height: 100%;
			text-align: center;
			line-height: 200rpx;
			color: #FFFFFF;
			background: rgba(0,0,0,.5);
			border-radius: 20rpx;
			font-size: 40rpx;
			font-weight: 500;
		}
	}
	.notice{
		width: 100rpx;
		height: 100rpx;
		background-color: #3285FF;
		color: #FFFFFF;
		text-align: center;
	}
</style>
