<template>
     <div>
         <div>
            {{numero}}
         </div>
         <button @click="adicionar">adicionar</button>
     </div>
</template>

<script>
export default {
    data() {
        return {
             numero: 0
        }
    },
    methods: {
        adicionar() {
            this.numero += 1
        }
    }
}
</script>

<style>

</style>