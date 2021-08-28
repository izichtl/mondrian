<template>
  <router-view/>
</template>
<style lang="scss">
@import 'src/styles/variables';
@import url('https://fonts.googleapis.com/css2?family=Teko:wght@600&display=swap');
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
h3, h4{
  font-family: 'Teko', sans-serif;
}
p{
  font-family: 'Teko', sans-serif;
}
a{
  text-decoration: none;
}
a:visited{
  text-decoration: none;
  color: $preto;
}

</style>
