<template>
	<div class="home">
		<nav-bar></nav-bar>
	    <router-view></router-view>
    </div>
</template>

<script>
	import NavBar from '@/components/nav.vue'

	export default {
		name: 'Home',
		components: {
			NavBar
		}
	}
</script>

<style type="text/css">
	
</style>