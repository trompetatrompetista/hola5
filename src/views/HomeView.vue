<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
  <div class="parte1"> <div class="b"><img src="https://picsum.photos/id/300/300?grayscale"> <h1> Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus magni qui id, quaerat vel quis aliquam, laudantium sequi accusamus, earum quia ut quod est culpa aliquid. Voluptatum id dignissimos commodi.</h1></div><div class="c"><img src="https://picsum.photos/id/300/300?grayscale"><h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime dolorum corporis ratione enim labore sint quos, magnam minima molestias. Magnam ex accusamus nam odit ad, est minima debitis recusandae ducimus?</h1></div><div class="d"><img src="https://picsum.photos/id/300/300?grayscale"><h1>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quidem error nobis iste iusto nulla eaque voluptate, magnam recusandae. Et quisquam nemo omnis pariatur assumenda eveniet odio quos ratione impedit odit.</h1></div></div>
 
    

</template>

<style>
        
        

        img {
            /* Para que sea responsiva */
            width: 100%;
        }
        .parte1{
         display:flex; 
          justify-content: space-between;
        }
   h1{
    text-align: justify;
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
