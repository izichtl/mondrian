<template>
  <div class="contentGrid gridOne">
      <div v-for="(item, index) in 19" v-bind:key="item" class="item" :class="this.class+(index+1)">
        <a v-if="index+1 == 15" v-on:click="myF"><p>A arte abstrata é a verdadeira visão da realidade.</p></a>    
        {{index+1}}
        



      </div>
  </div>
</template>

<script>
export default {
  name: 'Container',
  data () {
    return {
      result: "",
      class: "sqr",
      array: [1, 2, 3, 4, 5],
      classObject: {
        box06: true,
        sqr06: false
  }
    }
  },
  props:  {
    msg: String
  },
  methods:{
    myF: function () {
        if(this.class === "box"){
          this.class = "sqr";
        }else{
          this.class = "box";
        }
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
.sqr06{
  background-color: blue;
}

</style>
