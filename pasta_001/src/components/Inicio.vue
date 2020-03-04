<template>
     <div>
           <div v-for="cor in cores" :key="cor.id">
              {{cor.id}}: {{cor.cor}} - {{cor.significado}} 
           </div>
           <button @click="mudar">mudar</button>
     </div>
</template>

<script>
export default {
    props: {cores: Array, cores2: Array}, 
    data() {
        return {
            cor: null
        }
    },
    methods: {
       mudar() {
           this.cores = this.cores2
       }
    }
}
</script>

<style>

</style>