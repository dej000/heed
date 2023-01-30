<template>
    
    <footer class="text-white d-flex gap-5">
        <div class="col-md-4">
            <a class="navbar-brand fw-bold fs-3 d-flex align-items-center gap-2 mb-2 " href="/">  <img :src="Logo" alt=""/>    Heed</a>
            <h5>Providing businesses with intelligent,accurate, and precise intent
                analysis to  improve customer experience.</h5>
         <div>
            <p>Join our community:</p>
         </div>

        </div>
        
        <div class="container-fluid foot d-flex justify-content-between gap-5  ">
         

            <div class="row justify-content-between col-lg-12 ">
                <div class="col-md-4 p-3 ">
                    <h4>Explore</h4>
                    <ul class="list-unstyled ">
                        <li>Home</li>
                        <li>About Us</li>
                        <li>Privacy Policy</li>
                        <li>Terms & Conditions</li>
                        </ul>
                
                </div> 

                <div class="col-md-4  p-3 ">
                    <h4>Quick links</h4>
                    <ul class="list-unstyled  ">
                    <li >Billing and pricing</li>
                    <li>FAQ</li>
                    <li>Help & Support</li>
                    </ul>
                
                </div> 

                <div class="col-md-4  p-3 ">
                    <h4>Contact</h4>
                    <ul class="list-unstyled ">
                    <li>Terms</li>
                
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

.foot1{
  display: flex;
  gap: 20px;
}
footer{
    background: #031025;

    height: 100%;
    padding: 30px;
}
 
p{
    text-align: left;
   } 

li{
 padding-bottom: 20px;
}




@media(max-width:760px){
    footer{
        padding: 15px;
        display: flex;
        flex-direction:column ;
     
    }
    .foot{
        display: flex;
        flex-direction:column ;
         gap: 20px;
       
    }

    .foot1{
       
        width: 60%;
        gap: 30px;
    }
    h4{
        font-size: 24px;
    }
   p{
    text-align: left;
   }
}

</style>