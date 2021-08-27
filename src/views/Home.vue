<template>
    <div class="app size">
        <div class="head">
            <h3><a href="https://pt.wikipedia.org/wiki/Piet_Mondrian" target="_blank">Piet Mondrian</a>
            </h3>
            
        </div> 
        <div class="left"></div> 
        <div class="content">
            <Container msg="Este é container"/>
        </div> 
        <div class="right"></div> 
        <div class="foot">
            
            <h3><router-link to="/about">Sobre</router-link>
            
            </h3>
            
        </div> 
  </div>
</template>

<script>
// @ is an alias to /src
import Container from '@/components/Container.vue'


export default {
  name: 'Home',
  components: {
    Container
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