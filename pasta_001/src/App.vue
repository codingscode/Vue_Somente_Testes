<template>
   <div id="app">
       <inicio :cores="[...cores]" />
   </div>
</template>

<script>
import Inicio from './components/Inicio'

export default {
	name: 'app',
	components: {Inicio},
	data() {
		return {
			cores: [
				{id: 1, cor: 'vermelho', significado: 'amor'},
				{id: 2, cor: 'verde', significado: 'natureza'},
				{id: 3, cor: 'branco', significado: 'paz'},
				{id: 4, cor: 'amarelo', significado: 'riqueza'},
				{id: 5, cor: 'azul', significado: 'infinito'},
			]
		}
	}
	
}
</script>

<style>
    
</style>