<template>
	<view class="navigation-bar">
		<SettingsButton />
		<StoreButton />
		<SummeryButton />
	</view>
</template>

<script setup lang="ts">
	import SettingsButton from "@/pages/home/SettingsButton.vue";
	import StoreButton from "@/pages/home/StoreButton.vue";
	import SummeryButton from "@/pages/home/SummeryButton.vue"
</script>

<style scoped lang = "scss">
	.navigation-bar{
		display: flex;
		flex-direction: column;
	}
</style>