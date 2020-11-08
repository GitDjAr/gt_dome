<template>
	<view class="container">
		<mytop/>
	</view>
</template>


<script>
	import mytop from '@/pages/alltools/top_bar.vue'
	export default {
		components:{
			mytop,
		},
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui'
			}
		},
		methods: {

		},
		onPageScroll:{
			
		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
