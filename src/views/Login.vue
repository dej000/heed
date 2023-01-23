<template>
    <NavbarVue/>
    <div class="hero d-flex align-items-center justify-content-between mt-2 container gap-2"> 
        <div class="">
    {{ message }}
    
    <div class="alert alert-danger" id="hideDiv" role="alert" v-if="error">
    {{error}}
    </div>
    <div class="alert alert-success" role="alert" v-if="success">
      {{ success }}
      </div>
      
    <Form
     @submit="onSubmit"
     :validation-schema="schema"
     @invalid-submit="onInvalidSubmit"
    >
    <h2><strong>Welcome back</strong></h2>
    <p class="text-secondary">Please enter your details</p>
    <div class="container ">
     
    </div>
    
    
  
    
    
    
    <div class="row text-secondary">
     <div class="col-12">
       <TextInput
       name="email"
       type="email"
       label="Email"
       placeholder=" Enter your company email"
       id="floatingInput"
       class=""
       v-model="email"
     />
     
     </div> 
     </div>
    
     <div class="text-secondary">
      
    
       <div class="col-12">
         <TextInput
         name="password"
         type="password"
         label="Password"
         placeholder="Password at least 8 characters"
         id="floatingPassword"
         v-model="password"
       
       />
       </div> 
       <div class="d-flex justify-content-center mt-4 mb-4 gap-3">
        <input class="" type="checkbox"  v-model="acceptTerms">
        <label for="">Yes, I understand and agree to Love in Planning's  Terms and Conditions</label>
     </div>
     </div>
     <div class="form-group d-flex flex-column justify-content-center align-items-center  "><button  type="submit" class="btn submit-btn mb-3 btn-light sign " id="myBtn">Sign in     <div class="spinner-border spinner-border-sm " v-show="loading" role="status">
        <span class="visually-hidden">Loading...</span>
      </div></button>
        <p>Don’t have an account? <span> <router-link   class="text-decoration-none"  to="/signup">Sign up</router-link></span></p>
      </div>
     
    
    
    
    </Form>
    </div>
      <img :src="Sign" alt="">
     </div>
</template>

<script>
import NavbarVue from '../components/Navbar.vue';
import * as Yup from 'yup';
import { Form } from 'vee-validate';
import TextInput from '../components/TextInput.vue';
import axios from 'axios'
import Sign from '../assets/Signup.svg'
import { useRouter, useRoute } from 'vue-router'
    export default {
     components :{
    NavbarVue, 
    Form,
    TextInput,
    Yup

},
data(){
    return{
    Sign:Sign,
    schema : Yup.object().shape({
  email: Yup.string().email().required(),
  password: Yup.string().min(8).required(),
 
}), 
loading:false,
// error:'',
// success:''
router: useRouter() 
 }
 },
 methods:{
   onSubmit(values) {
    this.loading=true;
    axios.post(import.meta.env.VITE_BASE_URL+'login',values).then((res)=>{
      this.loading=false;
    })
    .catch(err=>{
      this.loading=false;
    })
 
  },
  onInvalidSubmit() {
    const submitBtn = document.querySelector('.submit-btn');
    submitBtn.classList.add('invalid');
    setTimeout(() => {
      submitBtn.classList.remove('invalid');
    }, 1000);
  }
     },

    }
</script>

<style scoped>
.sign{
    width: 100%;
}
img{
   max-width: 600px;
   max-height: 500px;
}
:root {
    --primary-color: #0071fe;
    --error-color: #f23648;
    --error-bg-color: #fddfe2;
    --success-color: #21a67a;
    --success-bg-color: #e0eee4;
  }
@media(max-width :1050px){
   img{
    display:none ;
   }
    .hero{
        display: flex !important;
        justify-content: center !important;
        align-content: center;
    }
  }

</style>