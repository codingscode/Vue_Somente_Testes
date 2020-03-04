<template>
   <div id="app">
       <inicio :cores="[...cores]" :cores2="[...cores2]" />
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
			],
			cores2: [
				{id: 6, cor: 'laranja', significado: 'alegria'},
				{id: 7, cor: 'marrom', significado: 'idade antiga'}
			]
		}
	}
	
}
</script>

<style>
    
</style>