<template>
  <div class="contentGrid gridOne">
      <div class="sobre">
      <p>SPA desenvolvida em vue/sass como estudo e homenagem ao modernista Piet Mondrian.</p>
      <br>
      <hr>
      <br>
      <p>Desenvolvido por <a href="https://github.com/izichtl"> Ivan Zichtl.</a></p>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Container',
  data () {
    
  },
  props:  {
    msg: String
  },
  methods:{
    
   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
@import 'src/styles/variables';
@import 'src/styles/blink';
@import 'src/styles/mContainer';
@import 'src/styles/mdContainer';
@import 'src/styles/lContainer';

.contentGrid{
    height: 100%;
    display: grid;
  }
  
.item{
     display: flex;
     text-align: center;
     align-items: center;
     justify-content: center;
   }
.contentGrid{
          background-color: $branco;
      }
.gridOne{
      grid-template-columns:  1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
      grid-template-rows:     1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
     
     }
.sobre{
  padding:10px;
  background-color: $branco;
  grid-column: 3/11;
  grid-row: 3/10
}

</style>
