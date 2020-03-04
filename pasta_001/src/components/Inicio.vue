<template>
     <div>
           <div v-for="cor in cores" :key="cor.id">
              {{cor.id}}: {{cor.cor}} - {{cor.significado}} 
           </div>
     </div>
</template>

<script>
export default {
    props: {cores: Array},
    data() {
        return {
            cor: null
        }
    },
    methods: {
       
    }
}
</script>

<style>

</style>