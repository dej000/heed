<template>
    <Navbar2/>
   
    
</template>

<script>
import Navbar2 from '../components/Navbar2.vue';
import TabNav from '../components/TabNav.vue'
import Tab from '../components/Tab.vue';
import TextInput from '../components/TextInput.vue';



    export default {
        components:{
       Navbar2,
       TabNav,
       Tab,
       TextInput
      }, 

      data(){
        return {
          selected:'Single Upload',
          selectedFile: null,
        }

      },
      methods :{
          setSelected(tab){
            this.selected= tab;
          },
          onFileSelected(event){
            this.selectedFile = event.target.files[0]
          },
          onUpload(){
            const fd = new FormData
            fd.append('image',this.selectedFile,this.selectedFile.name)
            instance.post(import.meta.env.VITE_BASE_URL+'mine-service/upload',fd, {
    onUploadProgress: progressEvent => {
      console.log('Upload Progress:' + Math.round(progressEvent.loaded / progressEvent.total *100) +"%" )
    }
  })
            .then(res =>{
                console.log(res)
            })
          }
        },
        
       
    }
</script>

<style >
img{
    width: 111px;
    height: 111px;
}

.input_file {
    cursor: pointer;
    height: 100%;
    left: 0;
    opacity: 0;
    position: relative;
    top: 0;
    width: 100%;
}
.sign{
    width: 100%;
    background-color: #FF6C00;
    color: white;

 }


 input {
  
   
    padding: 30px ;
    display: block;
    width: 100%;
    font-size: 16px;
    height: 40px;
    border-radius: 10px;
  }

  .upload_con {
    background: #FF6C00;
  }
  
</style>