<template>

     <nav class="navbar navbar-expand-lg container p-2">
        <a class="navbar-brand fw-bold fs-1" href="/"><img src="../assets/Group 45.svg" alt=""/>    Heed</a>
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
                    <a href=""><button type="button" class=" log  ">Login</button></a> 
                     <a href=""><button type="button" class=" sign ">Try For Free</button> </a> 
                 </div>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
li:hover{
    color: #006CFF;
}
</style>