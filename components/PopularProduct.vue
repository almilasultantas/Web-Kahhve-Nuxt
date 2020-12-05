<template>
  <div>
      <div >
          <p class="populer" style="text-align:center; margin-right:150px">POPÜLER KATEGORİLER</p>
      </div>

      <div class="row">
          <div class="col-sm-2" ><button class="kahvelerButon"><img src="../assets/static/image/kahveler.png" class="butonImg"></button></div>
          <div class="col-sm-2"><button class="kahvelerButon"><img src="../assets/static/image/frenchpress.png" class="butonImg"></button></div>
          <div class="col-sm-2"><button class="kahvelerButon"><img src="../assets/static/image/mokapot.png" class="butonImg"></button></div>
          <div class="col-sm-2"><button class="kahvelerButon"><img src="../assets/static/image/hario.png" class="butonImg"></button></div>
          <div class="col-sm-2"><button class="kahvelerButon"><img src="../assets/static/image/filtreler.png" class="butonImg"></button></div>
          <div class="col-sm-2"><button class="kahvelerButon"><img src="../assets/static/image/ogutuculer.png" class="butonImg"></button></div>
      </div>
      <hr>
  </div>
</template>

<script>

export default {
    name:"PopularProduct"

}
</script>

<style>
    .populer{
        color:#C65800 ;
        font-size: 28px;
        font-weight: bold;
        padding-left: 200px;
    }
    .kahvelerButon{
        border: 2px solid #C65800;
        border-radius: 80px;
        background-color: white;
        width: 150px;
        height: 150px;
        
    }
    .butonImg{
        height: 80px;
        width: 80px;
    }
</style>