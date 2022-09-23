<template>
    <grid>
  <img v-bind:src="url" alt="Ensalada">
  <h2>{{nombre}}</h2>
  <a :href="url" target="_blank">Comprar</a>
  <h4>20$</h4>
    </grid>
    
</template>
<script>
import Grid from "./Grid.vue";
    export default{
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        }
    },
    components: { Grid }
}
</script>

<style scoped>
    
    img{ 
        width: 15rem;
        height: 10rem;
        padding: 0.5rem;
        background: snow;
    }
    a{
        text-decoration: none;
        color: black;
        background-color: beige;
        padding: 0.3rem;
        border-radius: 5px;
        border:1px solid #fff
        
    }
</style>

