<template>
    <NavbarVue/>
    <section class="" >
        <div class="container hero d-flex justify-content-center gap-5  align-items-center mt-5">
            <div class="left">
                <div class="content">
                    <h1 class="fw-bold mb-3">World class Transcription <br> 
                        and  <span> Sentiment Analysis </span> <br>
                        for yor Business</h1>
                    <p class="fw-bold mb-5">We help businesses unlock insights and extract meaningful <br>
                        data from your customer support conversations </p>
                    <div class="d-flex gap-4 butt  ">
                        <a href=""><button type="button" class=" log  ">Request a Demo  </button></a> 
                         <a href=""><button type="button" class=" sign ">Get Started</button> </a> 
                     </div>
                </div>
               </div>
            
               <div class="right">
                <img :src="Hero" alt="">
               </div> 
        </div>
  
    </section>


    <section>
        <div class="container info mt-5  ">
            <h3 class="fw-bold text-center mb-5">Our Clients</h3>
            <div class="row mb-5 justify-content-center">
                <div class="col col-md-4">
                    <img :src="HNG" alt="">
                </div>
                <div class="col  col-md-4">
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

    <section>
        <div class="container mb-5">
           

            <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center">
                <div class="col col-sm-4">
                    <img :src="Group" alt="">
                </div>

                <div class="col col-lg-4 text-center col-sm-12">
                    <h4 class="fw-bold text-center">About US</h4>
                    <p>Scrybe is a conversation intelligence tool that automatically transcribes and analyzes recorded customer support conversations to extract 
                     sentimental analysis data. We help you determinethe efficiency of your customer support agents with the aim of improving overall customer satisfaction</p>
                     <button type="button" class=" sign ">read more</button>
                 </div>
               </div>     
        </div>
    </section>

    <section class="p-4" style="background-color: #E6F0FF
    ">
        <div class="container  mt-5 mb-5 ">
           

            <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center mb-5" >
                <h4 class="text-center fw-bold mt-5 mb-5">Get Started In These 3 Steps</h4>

               
                
           </div>  
           <div class=" container">
            <div class="row gap-4">
              <div class="col d-flex justify-content-center  ">
                <div class="card text-center" style="width: 18rem; max-height:500px">
                  <img :src="bro" class="card-img-top p-4" alt="...">
                  <div class="card-body">
                    <h5 class="card-title fw-bold">Upload Audio</h5>
                    <p class="card-text">Upload Audio between customers 
                        and staff on our database</p>
                    <a href="#" class="btn log">Get Started</a>
                  </div>
                </div>
              </div>
        
        
              
              <div class="col d-flex justify-content-center">
                <div class="card text-center" style="width: 18rem; max-height:500px">
                  <img :src="pana" class="card-img-top p-4" alt="...">
                  <div class="card-body">
                    <h5 class="card-title fw-bold">Transcribe Text</h5>
                    <p class="card-text">Our system transcribes these audio 
                        into readable texts</p>
                    
                  </div>
                </div>
              </div>
        
              
              <div class="col d-flex justify-content-center ">
                <div class="card text-center" style="width: 18rem; max-height:500px">
                  <img :src="rafiki" class="card-img-top p-4" alt="...">
                  <div class="card-body">
                    <h5 class="card-title fw-bold">Sentiment Analysis</h5>
                    <p class="card-text">The text is analyzed  using open Ai for 
                        for sentiments</p>
                    <a href="#" class="btn log">Get Started</a>
                  </div>
                </div>
              </div>
        
            </div>
          </div>   
        </div>
    </section>
    <section>
        <div class="container">
            <h4 class="fw-bold text-center mt-5">See what our clients  are saying</h4>

            <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center">
                <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="true">
                    <div class="carousel-indicators">
                      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active bg-secondary" aria-current="true" aria-label="Slide 1"></button>
                      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2" class=" bg-secondary"></button>
                      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3" class=" bg-secondary"></button>
                    </div>
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                       
            <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center mb-5">
                <div class="col col-sm-4">
                    <img :src="Group" alt="">
                </div>

                <div class="col   col-sm-4">
                    
                    <q>Scrybe is half the price and twice the speed. We looked for a more reliable and flexible platform for our calls analysis, then we found Scrybe. ever since then, its been a wonderful experience
                        being their client
                        </q>
                   
                 </div>
               </div>     
                      </div>
                      <div class="carousel-item">
                        <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center mb-5">
                            <div class="col col-sm-4">
                                <img :src="Group" alt="">
                            </div>
            
                            <div class="col   col-sm-4">
                               
                                <q>Scrybe is half the price and twice the speed. We looked for a more reliable and flexible platform for our calls analysis, then we found Scrybe. ever since then, its been a wonderful experience
                                    being their client
                                    </q>
                                
                             </div>
                           </div>     
                      </div>
                      <div class="carousel-item">
                        <div class="row flex-column flex-lg-row justify-content-center gap-5  align-items-center mb-5">
                            <div class="col col-sm-4">
                                <img :src="Group" alt="">
                            </div>
            
                            <div class="col   col-sm-4">
                                
                                <q>Scrybe is half the price and twice the speed. We looked for a more reliable and flexible platform for our calls analysis, then we found Scrybe. ever since then, its been a wonderful experience
                                    being their client
                                    </q>
                            
                             </div>
                           </div>     
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon rounded-circle  bg-primary" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next  " type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                      <span class="carousel-control-next-icon bg-primary rounded-circle " aria-hidden="true"></span>
                      <span class="visually-hidden p-5 ">Next</span>
                    </button>
                  </div>

            </div>     
        </div>
    </section>

    <section>
        <div class="container info mt-5 ">
            <h3 class="fw-bold text-center mb-5">Frequently Asked Questions</h3>
            <div class="row mb-5 justify-content-center">
                <div class="accordion row gap-4 " id="accordionExample">
                    <div class="accordion-item">
                      <h2 class="accordion-header" id="headingOne">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                            How do I register on Scrybe?
                        </button>
                      </h2>
                      <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                          <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                    </div>
                    <div class="accordion-item">
                      <h2 class="accordion-header" id="headingTwo">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                            What are the limitations of free package?
                        </button>
                      </h2>
                      <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                          <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                    </div>
                    <div class="accordion-item mb-5 ">
                      <h2 class="accordion-header" id="headingThree">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                            What format can i use for uploads?
                        </button>
                      </h2>
                      <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                          <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                        </div>
                      </div>
                     
                    </div>
                    <div class="d-flex justify-content-center">
                        <button class="log">Load more questions</button>
                    </div>
                    
                  </div>   
            </div>  
        </div>
    </section>
    
    <section style="background-color: #E6F0FF
    ">
        <div class=" info mt-5 p-5 ">
            <h1 class="fw-bold text-center  mb-5">Subscribe To Our Newsletter And <br>
                Get Newest industry Updates</h1>
           
             <form  class="d-flex justify-content-center gap-2 " >
               
                <input class="p-3 col-6" type="email" name="" id="" placeholder="email">
                <button class="sign"> subscribe</button>
             </form>
                
              
        </div>
    </section>
<FooterNavVue/>
</template>

<script>
import NavbarVue from '../components/Navbar.vue';
import FooterNavVue from '../components/FooterNav.vue';
import Hero from '../assets/Hero.svg'
import HNG from '../assets/HNG.svg'
import Zuri from '../assets/Zuri.svg'
import Payoneer from '../assets/Payoneer.svg'
import Hotel from '../assets/Hotel.svg'
import bro from '../assets/bro.svg'
import Group from '../assets/Group.svg'
import pana from '../assets/pana.svg'
import rafiki from '../assets/rafiki.svg'
    export default {
        components:{
  NavbarVue,FooterNavVue
},
data(){
          return{
            Hero:Hero,
            HNG:HNG,
            Zuri:Zuri,
            Payoneer:Payoneer,
            Hotel:Hotel,
            bro:bro,
            Group:Group,
            pana:pana,
            rafiki:rafiki
          }
     
        }
    }
</script>

<style  scoped>
span{
    color:#006CFF ;
}

img{
    height: 400px;
    width: 90%;
}
.content{
    width: 100%;
   height: 100%;
   
}

button.active {
   color: #006CFF !important;
}
.info img{
    height: 50px;
}
.card img{
    max-height: 220px ;
}
.carousel-item img{
    max-height: 220px ;
}

.accordion-button:focus {
    z-index: 3;
    
    outline: 0;
     box-shadow: none; 
}
input{
    background: #E6F0FF ;
}

.carousel-indicators button{
  background-color: #006CFF;
}
@media(max-width :990px){
    h1{
      font-size: 24px;
    }
    p{
      font-size: 16px;
    }
    
  }


  @media(max-width :770px){
    h1{
      font-size: 20px;
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
   img{
    height: 100%;
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