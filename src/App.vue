<script>
  export default{
    data: () => ({
      contador : 10,
    }),
    methods: {
      saludar(){
        console.log("Hola 10A")
      },
      incrementar(){
        this.contador++;
      },
      decrementar(){
        this.contador--;
      },
      resetear(){
        this.contador=10;
      }
    }
  };
</script>

<template>
  <div class="window-notice" id="window-notice">
    <div class="content">
        <div class="content-text">SERGIO MARTINEZ MENDEZ 10A
        
    </div>
</div>
</div>
  <img src ="./assets/logo.svg" alt="logo VUE"
  width="135" heigth="135">
  <div class="container">
    
    <h4>Sergio Martinez Mendez 10A</h4>
    <h1>Hola desde VUE.js</h1>
  <hr>
  <h2>Contador {{contador}}</h2>
  <button @click="incrementar()">+1</button>
  
  <button @click="decrementar()">-1</button>
  <button @click="resetear()">Reset</button>
  </div>
</template>

<style scoped>
  .container{
  text-align:center;
  }
  small{
    color:#666
  }
  h1{
    font-weight: bolder;
  }
  h2{
    font-size: 2.5rem;
  }
  button{
    cursor: pointer;
    font-size: 1.5rem;
    margin: 0px 8px;
  }
  .window-notice{
    background: rgba(10, 12, 10, .20);
    left: 0;
   text-align: center;
    right: 0;
    top: 0;
    display: flex;
    position: fixed;
    z-index: 99;
}

</style>