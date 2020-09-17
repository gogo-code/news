<template>
	<view class="content">
		<navbar></navbar>
		<view v-for="(item,index) in 100" :key="index">
			nidajl
		</view>
	</view>
</template>

<script>
	export default {
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

<style>
	
</style>
