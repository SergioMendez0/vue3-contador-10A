<template>
  <header>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
  
    
      <ul class="nav nav-tabs">
  <li class="nav-item">
    <a class="nav-link active" aria-current="page" href="#">Nuestros Platos</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Mi cuenta</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Blog </a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled">Disabled</a>
  </li>
  <h3>Sergio Martinez 10 A</h3>
</ul>
</header>

<div class="card text-center">
  <div class="card-header">
    <h5>Comida rapida</h5> 
  </div>
  <div class="card-body">
    
    <a href="#" class="btn btn-primary">Ensaladas</a>
    <a href="#" class="btn btn-primary">Pizzas</a>
    <a href="#" class="btn btn-primary">Hamburguesas</a>
    
  </div>
  <div class="card-footer text-muted">
    Pide ahora.
  </div>
</div>
  <hr/>
  <card-vue url="https://www.pequerecetas.com/wp-content/uploads/2020/07/ensalada-cobb-receta.jpg" width="8rem"
        height="8rem" nombre="Ensalada"/>
  <card-vue url="https://www.saborusa.com/wp-content/uploads/2019/12/origen-de-la-pizza-1.jpg" nombre="Pizza"/>
  <card-vue url="https://cdn.colombia.com/gastronomia/2011/08/25/pizza-margarita-3684.jpg" nombre="Pizzas"/>
  <card-vue url="https://d320djwtwnl5uo.cloudfront.net/recetas/share/pizza_Mh3H4eanyBKEsStv1YclPWTf9OUqIi.png" nombre="Pizzas"/>
  <card-vue url="https://images.hola.com/imagenes/cocina/noticiaslibros/20210528190401/dia-internacional-hamburguesa-recetas-2021/0-957-454/dia-hamburguesa-m.jpg" nombre="Hamburgesa"/>
  <card-vue url="https://www.recetasnestle.com.ec/sites/default/files/srh_recipes/4e4293857c03d819e4ae51de1e86d66a.jpg" nombre="Hamburgesas"/>
  <div class="footer">
  <p>Derechos de autor 2022©

Encuentranos en el Centro de la ciudad de tehuacan</p>
</div>
</template>

<script>
  import CardVue from './components/Card.vue';
  export default{
     components:{CardVue},
  };
</script>
<style scoped>

  ul{
    background: #288BA8;

  }
  h3{
    text-align: center;
  }
  h3{
    text-align: right;
    text-decoration: none;
        color: snow;
        
        padding: 0.3rem;
       
  }
  .footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: black;
  color: white;
  text-align: center;
}
 
</style>