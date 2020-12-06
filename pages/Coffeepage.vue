<template>
  <div>
   
    
    <div >
        <div class="row ">
          <div class="col-md2" >
            <Sidebar/>
          </div>
          <div class="col-md10 " >
            <div class="productsList ">
              <b-button v-for="i in imagess" :key="i" class="productArea" style="background-color:transparent" href="/Productpage" >
                <img  :key="i" :src="i" width="170px" height="280px" />
              </b-button>
             
                
              
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
  data(){
    return{
      imagess:[
        "https://kahhvecom.imgix.net/urunler/72_1442606029_MKI.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=186a16752ee405111bef7f387e157fdf",
        "https://kahhvecom.imgix.net/urunler/618_1589354785_O3b.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=4fd7970233528e6eed7ad3ab585f8162",
        "https://kahhvecom.imgix.net/urunler/617_1589354769_NSY.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=2602dd55b82b4f379ca19ffc9394570f",
        "https://kahhvecom.imgix.net/urunler/448_1565686841_2nX.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=758bad7e254169a904791ba2bfb0e4e4",
        "https://kahhvecom.imgix.net/urunler/614_1589354714_f8p.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=bb0ed2137d1cf091b5f2f9045eea2f8a",
        "https://kahhvecom.imgix.net/urunler/982_1597740545_WtU.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=6343eb0996333290f987a55e29ae1ffa",
        "https://kahhvecom.imgix.net/urunler/125_1444946611_dMW.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=a72fa3fdfbd07169ee43236fa302d935",
        "https://kahhvecom.imgix.net/urunler/948_1587282144_k0F.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=84d595e2288bf2ed8ff5a5a8aebe9afa",
        "https://kahhvecom.imgix.net/urunler/947_1587281686_gVt.jpg?h=250&ixlib=php-1.0.6&lossless=1&w=250&s=4b8d5b36a9c67b957ece25c64a022136"

    ],
    i:0
    }
    
    
  },
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
    padding-left: 15%;
    padding-right: 20%;
    align-items: center;
    width: 100%;
    
    
}
.productArea{
    height:300px;
    width: 29%;
    margin-bottom: 10%;
    border-style: solid;
    border-width: medium;
    border-color: #c65800;
    text-align: center;
    align-items: center;
    
}
</style>
