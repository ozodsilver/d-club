<template>
  <div id="app">
   <Header></Header>
   <Kurslar></Kurslar>
   <Reklama></Reklama>
  </div>
</template>

<script>
import Header from './components/header.vue'
import Kurslar from './components/kurslar.vue'
import Reklama from './components/reklama.vue'
export default {
components:{
Header,
Kurslar,
Reklama
},
  data() {
    return {
      
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>