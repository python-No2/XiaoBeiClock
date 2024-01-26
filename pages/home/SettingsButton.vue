<template>
	<view class="container" @click="goToSettings">
		<view class="option">settings</view>
	</view>
</template>

<script setup lang="ts">
	import { Pages } from "@/utils/url";
	const goToSettings = () =>{
		uni.navigateTo({
			url: Pages.Settings
		})
	}
</script>

<style scope lang="scss">
	.container{
		background-color: #237823;
		width: 100px;
	}
</style>