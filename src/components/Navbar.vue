<template>

     <nav class="navbar navbar-expand-lg container p-2">
        <a class="navbar-brand fw-bold fs-1" href="/"><img :src="Logo" alt=""/>    Heed</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mx-auto p-2 gap-3">
                <li class="nav-item">
                    <a class="nav-link  text-black" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-black" href="#">Pricing</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link text-black" href="#">About Us</a>
                  </li>
            </ul>
            <div class="navbar-nav sm-icons mr-0">
                <div class="d-flex gap-4 p-2 ">
                    <router-link   class="btn log "  to="/login">login</router-link>
                     <a href=""><button type="button" class=" sign ">Try For Free</button> </a> 
                 </div>
            </div>
        </div>
    </nav>
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

<style  scoped>
li:hover{
    color: #006CFF;
}
@media (max-width: 990px){
    .log {
        border: 1.5px solid #006CFF;
        color: #006CFF;
        background: white;
        padding: 10px 10px;
        border-radius: 5px;
      width: 40%;
    }
}


</style>