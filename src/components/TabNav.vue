<template>
    <section class="">
  
    <div class="container d-flex justify-content-between   mb-4">
           
            <div class=" col-12" >
              <ul class="d-flex justify-content-between tablist nav nav-tabs dashboard_tablist-center p-3 gap-2">
                <li v-for="tab in tabs"  :key="tab" class="nav-item">
                 <a class="nav-link log" :class="{ active: tab === selected}" @click="setTab(tab)">
                  {{ tab }}
                 </a>
                </li>
                
              </ul>

              <slot></slot>
            </div>

          </div>
      </section>
</template>

<script>

    export default {
        props:{
          tabs:{
            type: Array,
            required: true,
          },
          selected:{
            type:String,
            required: true
          }
        },
        methods:{
          setTab(tab){
            this.$emit('selected',tab);
          }
        }
    }
</script>

<style scoped>

</style>