<template>
   <div id="app">
       <div v-for="item in estados" :key="item">
		   {{item.dizer}}

	   </div>
       <!--<button @click="usar">alterar</button>-->
   </div>
</template>

<script>
export default {
	name: 'app',
	data() {
		return {
			estados : [{dizer: 'olá'}, 'sp', 'rj', 'mg', {dizer: 'como vai...'}, 'rs']
		}
    },
	methods: {
		usar() {
			this.estados = 'mudou'
		}
	}
}
</script>

<style>
    
</style>