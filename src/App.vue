<script >
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';

export default{
  components:{
    Navbar
  }
}
</script>

<template>


  <RouterView />
</template>

<style >
*{
  font-family: 'Kanit', sans-serif;
}
.log{
  border: 1.5px solid #006CFF;
  color: #006CFF;
  background: white;
  padding:16px 32px 16px 32px;
  border-radius: 5px;
}

.sign{
  width: px;
  background-color: #006CFF;
  color: white;
  border: #006CFF;
  padding:16px 32px 16px 32px;
  border-radius: 5px;

}

@media(max-width :990px){
 
  .sign {
      width: 100%;
      background-color: #006CFF;
      color: white;
      border: #006CFF;
      padding: 10px 10px;
      border-radius: 5px;
  }

  .log {
      border: 1.5px solid #006CFF;
      color: #006CFF;
      background: white;
      padding: 10px 10px;
      border-radius: 5px;
      width: 100%;
  }
}
</style>
