<template>
    <div class="app size">
        <div class="head">
            <h3><a href="https://pt.wikipedia.org/wiki/Piet_Mondrian" target="_blank">Piet Mondrian</a>
            </h3>
            
        </div> 
        <div class="left"></div> 
        <div class="content">
          <About />
        </div> 
        <div class="right"></div> 
        <div class="foot">
            
            <h4><router-link to="/">Home</router-link>
            
            </h4>
            
        </div> 
  </div>
</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'


export default {
  name: 'Sobre',
  components: {
       About
  }
}
</script>

<style lang="scss" >
@import 'src/styles/variables';
@import 'src/styles/mobile';
@import 'src/styles/mediumOne';
@import 'src/styles/mediumTwo';
@import 'src/styles/large';

.head{
  display: flex;
  align-items:center;
  justify-content: center;
}
.content{
  border: 2px solid white;
}
.foot{
  display: flex;
  align-items:center;
  justify-content: center;
}




</style>