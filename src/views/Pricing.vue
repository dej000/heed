<template>
    <NavbarVue/>
    <section class="" >
        <div class="container hero d-flex justify-content-center gap-5  align-items-center mt-5 mb-5">
            <div class="left mb-5">
                <div class="content">
                    <h1 class="fw-bolder mb-3">Plans for every stage of your customer  <span>success team</span> </h1>
                    <p class="fw-bold mb-5 text-secondary">Whether your audio files are large <br> or small, we are here to take the stress <br> off you
                    </p>
                  
                </div>
               </div>
            
               <div class="right">
                <img :src="raf" alt="">
               </div> 
        </div>
  
    </section>

    <section class="mt-5 fw-bold">

    <div class="container hero text-center d-flex flex-column justify-content-center align-items-center mb-5 ">
        <h2 class="fw-bold text-center  mb-5">Choose a plan that fits your needs</h2>
        <TabNav  :tabs="['Monthly','Yearly']" :selected="selected" @selected="setSelected">
            <tab :isSelected="selected ==='Monthly'">
             <section class="">
              
     
              
                  
     
                 
             </section>  
            </tab>
     
            <tab :isSelected="selected ==='Yearly'">
             <section class="">
              
     
               
                 
             </section>
     
            </tab>
           </TabNav>
   
       </div>
     
    
   </section> 
   
<FooterNavVue/>
</template>

<script>
import TabNav from '../components/TabNav.vue'
import Tab from '../components/Tab.vue';
import NavbarVue from '../components/Navbar.vue';
import FooterNavVue from '../components/FooterNav.vue';
import raf from '../assets/raf.svg'
    export default {
        components:{
       NavbarVue,
       FooterNavVue,
       TabNav,
        Tab 
      },
  data(){
          return{
          raf:raf,
          selected:'Yearly',
          }
     
        },
        methods :{
         
         setSelected(tab){
           this.selected= tab;
         }
       },   
    }
</script>

<style >
span{
    color:#006CFF ;
}

img{
  
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
