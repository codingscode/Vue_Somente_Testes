<template>
   <div id="app">
       {{estados}}
       <button @click="usar">alterar</button>
   </div>
</template>

<script>
export default {
	name: 'app',
	data() {
		return {
			estados : ['sp', 'rj', 'mg', 'sc', 'rs']
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