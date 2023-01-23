<template>
    <Navbar2/>
 
     
</template>

<script>
import Navbar2 from '../components/Navbar2.vue';
import TabNav from '../components/TabNav.vue'
import Tab from '../components/Tab.vue';

    export default {
        components:{
       Navbar2,
       TabNav,
       Tab
      }, 
      data(){
        return {
          selected:'Images',
          mined_image:null,
          imageUrl:''
        }

      },
      
    }
</script>

<style scoped>
.contain{
    padding-left: 180px;
    padding-right: 40px;
}

img{
    height: 50px;
    width: 100px;
}
</style>