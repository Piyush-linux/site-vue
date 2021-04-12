<template>
    <div class="box">
    	<div class="is-block">
    		<span class="iconify" :data-icon="logo" data-inline="false"></span>
    	</div>
    	<h1 class="title mt-2"> {{ head }} </h1>
    	<p class="content">Lorem, ipsum dolor sit, amet consectetur adipisicing elit. Voluptates, deleniti?</p>
    </div>
</template>
<script>
export default {
    name: 'card',
    props:["logo","head"]
}
</script>
<style scoped>
/*@import '../assets/css/style.css';*/

.box .iconify{
	font-size: 2.3rem;
    color:#69c1a3;
}
.box .title{
    color:#323030 ;
    opacity: .9;
    font-size: 1.5rem;
}


</style>