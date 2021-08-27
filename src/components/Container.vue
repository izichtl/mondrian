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
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
@import 'src/styles/variables';

.contentGrid{
  height: 100%;
  display: grid;
  grid-gap: 8px;
}
.gridOne{
  grid-template-columns:  1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
  grid-template-rows:     1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
 
 }
 .item{
   display: flex;
   text-align: center;
   align-items: center;
   justify-content: center;
 }
.box01{
  background-color: $azul;
  grid-column: 1/3;
  grid-row: 1/2;
}
.box02{
  background-color: $azul;
  grid-column: 3/5;
  grid-row: 1/2;
}
.box03{
  background-color: $branco;
  grid-column: 5 / 11;
  grid-row: 1/2;
}
.box04{
  background-color: $amarelo;
  grid-column: 11 / 13;
  grid-row: 1/2;
}
.box05{
  background-color: $branco;
  grid-column: 1 / 5;
  grid-row: 2/7;
}
.box06{
  background-color: $vermelho;
  grid-column: 5 / 11 ;
  grid-row: 2/6;
}
.box07{
  background-color: $branco;
  grid-column: 11 / 13 ;
  grid-row: 2/6;
}
.box08{
  background-color: $branco;
  grid-column: 5 / 11;
  grid-row: 6/7;
}
.box09{
  background-color: $vermelho;
  grid-column: 11 / 13 ;
  grid-row: 6/7;
}
.box10{
  background-color: $branco;
  grid-column: 1 / 3;
  grid-row: 7/8;
}
.box11{
  background-color: $amarelo;
  grid-column: 3 / 9;
  grid-row: 7/8;
}
.box12{
  background-color: $amarelo;
  grid-column: 9/ 11;
  grid-row: 7/8;
}
.box13{
  background-color: $branco;
  grid-column: 11 / 13;
  grid-row: 7 / 8;
}
.box14{
  background-color: $vermelho;
  grid-column: 1 / 3;
  grid-row: 8 /13;
}
.box15{
  background-color: $branco;
  grid-column: 3 / 9;
  grid-row: 8 /11;
}
.box16{
  background-color: $azul;
  grid-column: 9 /11;
  grid-row: 8 /11;
}
.box17{
  background-color: $branco;
  grid-column: 11/13;
  grid-row: 8 /11;
}
.box18{
  background-color: $branco;
  grid-column: 3/9;
  grid-row: 11 /13;
}
.box19{
  background-color: $amarelo;
  grid-column: 9/13;
  grid-row: 11 /13;
}
</style>
