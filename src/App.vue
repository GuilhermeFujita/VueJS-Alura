<template>
    <div>
        <h1>{{ titulo }}</h1>
        <img :src="foto.url" :alt="foto.titulo">
    </div>
</template>

<script>
export default {

    data(){

        return {
            titulo: 'Alurapic',
            foto: {
                url: 'http://tudosobrecachorros.com.br/wp-content/uploads/cachorro-independente.jpg',
                titulo: 'Cachorro'
            }
        }
    }
}

</script>

<style>

</style>
