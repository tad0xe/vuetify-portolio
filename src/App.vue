<template >
  
  <v-app dark style="margin:auto; max-width:1100px;">
   

    <v-main>
    

      <HelloWorld/>
    <slid/>
    <key/>
    <About/>
    <Home/>
    
    </v-main>
  </v-app>
  
</template>

<script>
import HelloWorld from './components/HelloWorld'
import slid from './components/slid'
import key from './components/key'
import About from './views/About'
import Home from './views/Home'

export default {
  name: 'App',

  components: {
    HelloWorld,
    slid,
    key,
    About,
    Home,
   
  },

  data: () => ({
    //
  }),
};
</script>
