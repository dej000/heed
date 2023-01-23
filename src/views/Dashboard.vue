<template>
    <Navbar2/>
   <!-- <section class="mt-5 fw-bold">

    <div class="container hero text-center d-flex flex-column justify-content-center align-items-center mb-5 ">
        <h1 class="mb-5 fw-bold">AI - Powered Solutions To Boost <br> Sales And Support Teams Efficiency
        </h1>
        <p class="text-secondary mb-5">Heed uses Artificial Intelligence to automatically transcribe and analyze recorded audio calls by Customer support agents <br> and sales reps to give cutting-edge insight into customer sentiment, thereby boosting operational efficiency, brand loyalty <br> and customer retention
        </p>
   
       </div>
      <div class="d-flex justify-content-center ">
        <TabNav  :tabs="['For Support','For Sale']" :selected="selected" @selected="setSelected">
            <tab :isSelected="selected ==='For Support'">
             <section class="">
              
     
              
                  
     
                 
             </section>  
            </tab>
     
            <tab :isSelected="selected ==='For Sale'">
             <section class="">
              
     
               
                 
             </section>
     
            </tab>
           </TabNav>
      </div>
    
   </section>  -->

</template>

<script>
import TabNav from '../components/TabNav.vue'
import Tab from '../components/Tab.vue';
import Navbar2 from '../components/Navbar2.vue';
import Navbar from '../components/Navbar.vue';
    export default {
        data(){
        return{
            selected:'For Support',
        }
        },
      components:{
        Navbar,
        TabNav,
        Navbar2,
        Tab 
      } ,
      methods :{
         
          setSelected(tab){
            this.selected= tab;
          }
        },
    }
</script>

<style lang="scss" scoped>

</style>