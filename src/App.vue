<script >
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Signup from './views/Signup.vue';
import LoginVue from './views/Login.vue';
import Dashboard from './views/Dashboard.vue';

export default{
  components:{
    Navbar,
    Signup,
    LoginVue,
    Dashboard
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
:root {
  --primary-color: #0071fe;
  --error-color: #f23648;
  --error-bg-color: #fddfe2;
  --success-color: #21a67a;
  --success-bg-color: #e0eee4;
}

.submit-btn {
  background: var(--primary-color);
  outline: none;
  border: none;
  color: #fff;
  font-size: 18px;
  padding: 10px 15px;
  display: block;
  width: 100%;
  border-radius: 7px;
  margin-top: 15px;
  transition: transform 0.3s ease-in-out;
  cursor: pointer;
}

.submit-btn.invalid {
  animation: shake 0.5s;
    animation-iteration-count: infinite;
}

@keyframes shake {
  0% {
    transform: translate(1px, 1px);
  }
  10% {
    transform: translate(-1px, -2px);
  }
  20% {
    transform: translate(-3px, 0px);
  }
  30% {
    transform: translate(3px, 2px);
  }
  40% {
    transform: translate(1px, -1px);
  }
  50% {
    transform: translate(-1px, 2px);
  }
  60% {
    transform: translate(-3px, 1px);
  }
  70% {
    transform: translate(3px, 1px);
  }
  80% {
    transform: translate(-1px, -1px);
  }
  90% {
    transform: translate(1px, 2px);
  }
  100% {
    transform: translate(1px, -2px);
  }
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
