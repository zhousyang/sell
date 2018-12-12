<template>
	<div id="app">
		<div class="header" @click='devClick'>
			 I am header
		</div>
		<chart></chart>
	</div>
</template>

<script>
	import chart from './components/charts'
	export default{
		 data(){
			  return{
					
				}
		 },
		 components:{
			 chart:chart
		 },
		 methods:{
			 devClick:function(){
				  $('.header').addClass('turnRed');
			 }
		 }
	}
</script>

<style>
	 .turnRed{
		  background:red;
	 }
</style>
