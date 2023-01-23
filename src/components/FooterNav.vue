<template>
    
    <footer class="text-white ">
        <div class="container foot d-flex justify-cintent-between gap-5  ">
            <div class="">
                <a class="navbar-brand fw-bold fs-1" href="/"><img :src="Logo" alt=""/>    Heed</a>
                <p>Providing businesses with intelligent, accurate, and precise intent
                    analysis to improve customer experience.</p>
            
    
            </div>
            <div class="d-flex  foot1 text-center  col-8  ">
                <div >
                    <h4>Explore</h4>
                    <ul class="list-unstyled text-center">
                    <li>Home</li>
                    <li>About Us</li>
                    <li>Privacy Policy</li>
                    <li>Terms & Conditions</li>
                    </ul>
                </div>
    
                <div>
                    <h4>Quick links</h4>
                    <ul class="list-unstyled  text-center">
                    <li >Billing and pricing</li>
                    <li>FAQ</li>
                    <li>Help & Support</li>
                    </ul>
                </div>
    
                <div>
                    <h4>Contact</h4>
                    <ul class="list-unstyled  text-center">
                    <li><i class='far fa-envelope-open'></i>Terms</li>
                
                    </ul>
                </div>

                
            </div>
           

           
           
          
        
       
        </div>
       
    </footer>
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
.bord{
    background-color: white;
    height: 2px;
    width: 30%;
    display: block;
}
.foot1{
  display: flex;
  gap: 150px;
}
footer{
    background: #031025;

    height: 100%;
    padding: 30px;
}

input{
    border-radius: 10px 0 0 10px;
    height: 54px;
    outline: none;
   
}
button{
    height: 51px;
    border-top-right-radius: 0.5rem;
    border-bottom-right-radius: 0.5rem;
    color: white;
    background-color: #FF6C00;
    border: #FF6C00;
}

li{
 padding-bottom: 20px;
}

form{
    width: 100%;
    margin-bottom: 20px;
}

@media(max-width:1140px){
    .foot1 {
        display: flex;
        gap: 100px;
    }
}

@media(max-width:990px){
    footer{
        padding: 15px;
    }
    .foot{
        display: flex;
        flex-direction:column ;
        align-items: center;
         gap: 20px;
       
    }

    .foot1{
        display: flex;
        flex-direction:column ;
        align-items: center;
        width: 60%;
        gap: 30px;
    }
    h4{
        font-size: 24px;
    }
    .bord{
        display: none;
    }
}

</style>