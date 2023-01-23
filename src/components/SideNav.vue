<template>
    <div class="sidebar p-5 ">
      <a class="navbar-brand mb-5 fw-bold fs-5" href="/"><img :src="Logo" alt="">   HEED</a>
      <ul class="list-unstyled d-grid gap-4  "  id="myDIV" >
          <li>   <router-link   class="btn  "  to="/dashboard">Overview</router-link></li>
          <li> <router-link   class="btn  "  to="/analysis">Analysis</router-link></li>
          <li><router-link   class="btn "  to="/leaderboard">Leaderboard</router-link></li>
          <li>   <router-link   class="btn "  to="/settings">Settings</router-link></li>
      </ul>
    </div>
  
  </template>
  
  
  <script>
  import Logo from '../assets/Logo.svg'
  
      export default {
        
          data(){
            return{
              Logo:Logo
            }
       
          }
      }
  </script>
  
  <style scoped>
   .sidebar{
      color: black;
      background: #FBFBFB;
     float: left;
     position: fixed;
     z-index: 1;
     top: 0;
     left: 0;
     bottom: 0;
     display: flex;
     flex-direction: column;
  
   }
  
   a{
      text-decoration: none;
      color: black;
      gap: 10px;
   }


  .navbar-brand img{
    width: 48px;
   height: 39.18px;
  }


  </style>