<template>
	<div>
		<h1>{{ titulo }}</h1>
		<small>{{ descricao }}</small>	
	</div>
	
</template>

<script>

import SbA from './A.vue'

	export default{
		extends: SbA,
		data(){ return { descricao: 'meu titulo' } }
	}
</script>