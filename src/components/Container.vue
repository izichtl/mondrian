<template>
  <div class="contentGrid gridOne">
 
    <div class="item box01">01</div>
    <div class="item box02">02</div>
    <div class="item box03">03</div>
    <div class="item box04">04</div>
    <div class="item box05">05</div>
    <div class="item box06">06</div>
    <div class="item box07">07</div>
    <div class="item box08">08</div>
    <div class="item box09">09</div>
    <div class="item box10">10</div>
    <div class="item box11">11</div>
    <div class="item box12">12</div>
    <div class="item box13">13</div>
    <div class="item box14">14</div>
    <div class="item box15">15</div>
    <div class="item box16">16</div>
    <div class="item box17">17</div>
    <div class="item box18">18</div>
    <div class="item box19">19</div>
    



    
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
