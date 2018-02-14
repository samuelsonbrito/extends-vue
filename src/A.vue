<template>
	<h1>{{ titulo }}</h1>
</template>

<script>
	export default{
		data(){ return { titulo: 'meu titulo'} },
		mounted(){ this.titulo = this.titulo.toUpperCase() }
	}
</script>