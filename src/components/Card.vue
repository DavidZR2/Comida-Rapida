<template>
    <grid>
        <img v-bind:src="url" :alt="nombre">
        <h2>{{nombre}}</h2>
        <h5>{{descripcion}}</h5>
        <h4>{{precio}}</h4>
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default{
    props: {
        url: {
            String
        },
        nombre: {
            String
        },
        descripcion: {
            String
        },
        precio: {
            String
        },
    },
    components: { Grid }
}
</script>

<style scoped>
    img{
        width: 20rem;
        height:20rem;
        padding: 0.5rem;
        background-color: snow;
    }
    a{
        text-decoration: none;
        color: snow;
        background-color: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>