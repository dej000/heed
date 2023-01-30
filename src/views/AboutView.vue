<template>
    <NavbarVue/>
    <section class="" >
        <div class="container hero d-flex justify-content-center gap-5  align-items-center mt-5 mb-5">
            <div class="left mb-5">
                <div class="content"> 
                    <h1 class="fw-bolder mt-5 mb-3 text-center"> Scrybe helps businesses to  make <br> informed decisions <span> faster </span></h1>
                </div>
               </div>
            
        </div>
  
    </section>

    <section class="mt-5 fw-bold">
        <h1 class="fw-bold text-center  mb-5">Who we are</h1>
        <div class="container hero d-flex justify-content-c gap-5  a mt-5 mb-5">
            <div class="left mb-5">
                <div class="content d-flex flex-column justify-content-center align-items-center">
                   
                    <p class="fw-bold mb-5 text-secondary">At Scrybe, we transcribe call recordings between customer support agents and customers to
                        give sentimental analysis as we analyze transcriptions to give sentiment score of the
                        conversation
                        (Positive, Neutral or Negative)
                    </p>

                    <p class="fw-bold mb-5 text-secondary">At Scrybe, we transcribe call recordings between customer support agents and customers to
                        give sentimental analysis as we analyze transcriptions to give sentiment score of the
                        conversation
                        (Positive, Neutral or Negative)
                        
                       
                    </p>

                    <p class="fw-bold mb-5 text-secondary">
                        We believe that we can come together, to make the business world better for all and this is what we are forever committed to.
                        Our slogan is <span class="text-black fw-bolder"> Speak, we listen</span>
                       
                    </p>
                  
                </div>
               </div>
            
               <div class="right d-flex justify-content-center  ">
                <img :src="pana2" alt="">
               </div> 
        </div>

   </section> 
   <section class="p-5" style="background-color: #E6F0FF
   ">
    <div class="container hero d-flex flex-column justify-content-between gap-5  a mt-5 mb-5">
        <div class="row justify-content-between gap-5 text-secondary">
            <div class="col-md-5  border p-3  border-primary">
             <h3 class="text-black">Customer Success</h3>
             <p>
            Our number one goal is to see our customers suceed at business. We will go above and beyond to assist businesses to ensure they are getting the best service from us.
             </p>
            
            </div> 
       
            <div class="col-md-5  border p-3  border-primary">
                <h3 class="text-black">Creativity</h3>
                <p>
                    We are a team of creative and innovative people who think outside of the box and we take unconventional approaches to assist our customers to operate at high levels of efficacy.
                </p>
            </div> 


        </div> 

        <div class="row justify-content-between gap-5  text-secondary">
            <div class="col-md-5 border p-3  border-primary">
             <h3 class="text-black">Teamwork</h3>
             <p>
                The foundation of Scrybe is Teamwork. Every person in every position allows us to be as great as we are. No one position is greater than the other as we are all needed to achieve our mission. 
             </p>
            
            </div> 
       
            <div class="col-md-5 border p-3 border-primary">
                <h3 class="text-black">Ownership</h3>
                <p>
                    We are more than employees at Scrybe. Every person that is a part of team Scrybe owns the role. We only want team members who fully believe in our vision and are committed to make it a reality.              </p>
            </div> 


        </div> 
           
    </div>
   </section>

   <section>
    <div class="container info mt-5  text-center   ">
        <h3 class="fw-bold text-center  text-center mb-2">Partners</h3>
        <p class="mb-5">Great Success, they say, is never achieved alone. This is also true for us at Scrybe. In order <br> to achieve our goals and to offer a better service all customers, we have partnered with a <br> number of brands to achieve these goals. </p>
        <div class="row mb-5 justify-content-center">
            <div class="col ">
                <img :src="HNG" alt="">
            </div>
            <div class="col  ">
                <img :src="Zuri" alt="">
            </div>
            <div class="col">
                <img :src="Payoneer" alt="">
            </div>
            <div class="col">
                <img :src="Hotel" alt="">
            </div>
           
       
           
            
        </div>  
    </div>
</section>


<section class="">
    <div class="container info mt-5  text-center  ">
        <h3 class="fw-bold text-center  text-center mb-2">Meet Our Team</h3>
        <p class="mb-5">We are improving at a breakneck speed and are across all tech departments. We research <br>
            and deploy advanced machine learning and deep learning technologies. <br> 
            Here are the key members that make up the team behind Scrybe. </p>
        <div class="row mb-5 justify-content-center">
            <div class="col ">
                <img src="" alt="">
                <p>Mark Essien</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col  ">
                <img src="" alt="">
                <p>Aigbe Marvelous</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col">
                <img src="" alt="">
                <p>Collins Akpaka</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col">
                <img src="" alt="">
                <p>Delphine Ogbonna</p><p class="text-secondary">FrontEnd Lead</p>

            </div>
              
        </div> 
        
        <div class="row mb-5 justify-content-center">
            <div class="col ">
                <img src="" alt="">
                <p>Mark Essien</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col  ">
                <img src="" alt="">
                <p>Aigbe Marvelous</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col">
                <img src="" alt="">
                <p>Collins Akpaka</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
            <div class="col">
                <img src="" alt="">
                <p>Delphine Ogbonna</p>
                <p class="text-secondary">FrontEnd Lead</p>
            </div>
           
       
           
            
        </div>  
    </div>
</section>
   
<FooterNavVue/>
</template>

<script>
import NavbarVue from '../components/Navbar.vue';
import FooterNavVue from '../components/FooterNav.vue';
import pana2 from '../assets/pana2.svg'

import HNG from '../assets/HNG.svg'
import Zuri from '../assets/Zuri.svg'
import Payoneer from '../assets/Payoneer.svg'
import Hotel from '../assets/Hotel.svg'

    export default {
        components:{
       NavbarVue,
       FooterNavVue,
    
      },
  data(){
          return{
            pana2:pana2,
            HNG:HNG,
            Zuri:Zuri,
            Payoneer:Payoneer,
            Hotel:Hotel,
          }
     
        },
       
    }
</script>

<style >

section{
    margin-bottom: 150px;
}
span{
    color:#006CFF ;
}

.info img{
    height: 50px;
    width: 90%;
}

.content{
    width: 100%;
   height: 100%;
   
}


a{
    color: #000;
  }

  .nav-tabs .nav-link {
    color: #006CFF;
}

.hero img{
    max-height: 80%;
}
  
  .tablist {
      background:#E6F0FF;
      border: none;
      margin-bottom: 20px;
     max-width: 350px;
      padding: 8px;
      align-items: center;
      border-radius: 10px;
    }
  
    ul li{
      cursor: pointer;
      list-style: none;
    }
  
    .nav-tabs .nav-item.show .nav-link, .nav-tabs .nav-link.active {
      color: #ffffff;
      background-color: #006CFF ;
      border-color: var(--bs-nav-tabs-link-active-border-color);
    }

    @media(max-width :990px){
        h1{
          font-size: 24px;
        }
        p{
          font-size: 16px;
        }
        .hero{
            display: flex;
            flex-direction: column;
            margin-bottom: 0px;
            gap: 0px;
           }
        
      }
    
    
      @media(max-width :770px){
        h1{
          font-size: 24px;
          text-align: center;
        }
        p{
          font-size: 14px;
          text-align: center;
        }
       .hero{
        display: flex;
        flex-direction: column;
        margin-bottom: 0px;
        gap: 0px;
       }
      .hero img{
        height: 100%;
        width: 100%;
       }
    
       .butt{
        display: flex;
        flex-direction: column-reverse;
        
       }
    
       .content{
        width: 100%;
       height: 100%;
       
    }
    button span{
      color: #006CFF;
      display: none;
    }
      }
</style>
