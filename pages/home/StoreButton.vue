<template>
	<view class="container" @click="goToStore">
		<view class="option">store</view>
	</view>
</template>

<script setup lang="ts">
	import { Pages } from "@/utils/url";
	const goToStore = () =>{
		uni.navigateTo({
			url: Pages.Store
		})
	}
</script>

<style scope lang="scss">
	.container{
		background-color: #237823;
		width: 100px;
	}
</style>