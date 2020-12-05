<template>
  <div>
   
    
    <div >
        <div class="row ">
          <div class="col-md4" >
            <Sidebar/>
          </div>
          <div class="col-md8 " >
            <div class="productsList ">
              <div v-for="i in 12" :key="i" class="productArea">
                Product
              </div>
            </div>
            
          </div>
        
        </div>
        
    </div>
    <Nuxt />
  </div>
</template>
<script>

import Sidebar from "../components/Sidebar"

export default {
  components:{
  Sidebar
  
}
}
</script>
<style>

.productsList{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
    padding-left: 30%;
    padding-right: 20%;
    align-items: center;
    width: 200%;
    
    
}
.productArea{
    height:300px;
    width: 29%;
    margin-bottom: 10%;
    border-style: solid;
    border-width: medium;
    border-color: #c65800;
    text-align: center;
    
}
</style>
