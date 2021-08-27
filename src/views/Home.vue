<template>
    <div class="app size">
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

<style lang="scss" >
@import 'src/styles/variables';
@import 'src/styles/mobile';
@import 'src/styles/mediumOne';
@import 'src/styles/mediumTwo';
@import 'src/styles/large';





</style>