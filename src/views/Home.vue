<template>
    <div class="app mobile">
        <div class="head">
          <ul>
      <li><a href="https://github.com/izichtl" target="_blank">O</a></li>
      <li><a href="https://github.com/izichtl" target="_blank">O</a></li>
    </ul>
        </div> 
        <div class="left"></div> 
        <div class="content">
            <Container msg="Este é container"/>
        </div> 
        <div class="right"></div> 
        <div class="foot">
         <ul>
      <li><a href="https://github.com/izichtl" target="_blank">O</a></li>
      <li><a href="https://github.com/izichtl" target="_blank">O</a></li>
    </ul>
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

<style >
.mobile{
  grid-template-columns: 1fr 20fr 1fr;
  grid-template-rows: 1fr 20fr 1fr;

}
.head{
  background-color: white;
  grid-column: 1 /span 3;
  grid-row: 1;
}
.left{
  grid-column: 1;
  grid-row: 2;
}
.content{
  background-color: #131313;
  grid-column: 2;
  grid-row: 2;
}
.right{
  grid-column: 3;
  grid-row: 2;
}
.foot{

  grid-column: 1/ span 3;
  grid-row: 3;
}


</style>