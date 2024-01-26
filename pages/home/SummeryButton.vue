<template>
	<view class="container" @click="goToSummery">
		<view class="option">summery</view>
	</view>
</template>

<script setup lang="ts">
	import { Pages } from "@/utils/url";
	const goToSummery = () => {
		uni.navigateTo({
			url: Pages.Summery
		});
	}
	
</script>

<style scope lang="scss">
	.container{
		background-color: #237823;
		width: 100px;
		margin-top: 20px;
	}
</style>