<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
  <div class="fila">
        <div class="columna">
            <img src="https://picsum.photos/800/600">
        </div>
        <div class="columna">
            <img src="https://picsum.photos/800/600">
        </div>
        <div class="columna">
            <img src="https://picsum.photos/800/600">
        </div>
    </div>
    <div class="fila">
        <div class="texto">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus fugit voluptatibus culpa. Dolor, eaque. In dolore nulla placeat. Ipsam deleniti ipsum iusto voluptatem expedita facilis illum quas consequatur saepe modi?
        </div>
        <div class="texto">
          
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum assumenda dolorum excepturi! Dolorum nesciunt veniam officiis architecto et, quos explicabo quod, iure nobis rem ducimus rerum? Debitis ut cumque nam!
        </div>
        <div class="texto">
 
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, quod asperiores consequatur voluptatibus suscipit temporibus ex illum dolore, at ut reprehenderit eius sint aspernatur placeat deserunt veritatis earum ducimus quibusdam!
        </div>
    </div>

</template>

<style>
        * {
            box-sizing: border-box;
        }

        .columna {
            float: left;
            width: 33%;
            padding-right: 5px;
        }
        .texto {
            float: left;
            width: 33%;
            padding-right: 5px;
            text-align: center;
            
        }

        .fila::after {
            content: "";
            clear: both;
            display: table;
        }

        img {
            /* Para que sea responsiva */
            width: 100%;
        }
    </style>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
