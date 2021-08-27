<template>
  <div class="contentGrid gridOne">
 
    <div class="item box01"></div>
    <div class="item box02"></div>
    <div class="item box03"></div>
    <div class="item box04"></div>
    <div class="item box05"></div>
    <div class="item box06"></div>
    <div class="item box07"></div>
    <div class="item box08"></div>
    <div class="item box09"></div>
    <div class="item box10"></div>
    <div class="item box11"></div>
    <div class="item box12"></div>
    <div class="item box13"></div>
    <div class="item box14"></div>
    <div class="item box15">
      <p>A arte abstrata é a verdadeira visão da realidade.</p>
    </div>
    <div class="item box16"></div>
    <div class="item box17"></div>
    <div class="item box18"></div>
    <div class="item box19"></div>
    



    
  </div>
</template>

<script>
export default {
  name: 'Container',
  data () {
    return {
      result: ""
    }
  },
  props:  {
    msg: String
  },
  methods:{
    myFunction: function () {	
		this.result = screen.width+"px";
    }
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
          background-color: $preto;
      }
.gridOne{
      grid-template-columns:  1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
      grid-template-rows:     1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
     
     }


</style>
