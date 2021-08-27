<template>
  <div class="app mobile">
        <div class="head">
          <ul>
              <li>.</li>
              <li>.</li>
          </ul>
        </div> 
        <div class="left"></div> 
        <div class="contentGrid">
            <div class="blue">B</div>
            <div class="blue">B</div>
            <div class="white">W</div>
            <div class="yellow">Y</div>


        </div> 
        <div class="right"></div> 
        <div class="foot">
          <ul>
              <li>.</li>
              <li>.</li>
          </ul>
        </div> 
  </div>
</template>
<style>
*{
  margin: 0px;
  padding: 0px;
}
.app {
  display: grid;
  padding: 1px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100vh;
}
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
.contentGrid{
  background-color: #45d169;
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
