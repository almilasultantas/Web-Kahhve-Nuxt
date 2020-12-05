<template>
    <div>
        <div class="BenzerUrunlerContainer">
            <p class="baslik">BENZER ÜRÜNLER</p>
            <br>
            <div class="satirpad">
                <div class="row">
                <div class="col-sm-3">
                    <div class="urun">
                        <img class="urunImg" src="https://kahhvecom.imgix.net/urunler/448_1565686841_2nX.jpg?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=e9fa9696eb8a47e2a643645eda308d22" alt="">
                    </div>
                    <span class="markaAdı">Acme</span><br>
                    <span class="urunAdı">Petra</span><br>
                    <span class="fiyat">58.99 TL</span>
                </div>
                <div class="col-sm-3">
                    <div class="urun">
                        <img class="urunImg" src="https://kahhvecom.imgix.net/urunler/796_1603712633_TGb.png?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=99033a67784423aa44d6be330195f270" alt="">
                    </div>
                    <span class="markaAdı">All Day Blend</span><br>
                    <span class="urunAdı">Caffe Fresco</span><br>
                    <span class="fiyat">34.99 TL</span>
                </div>
                <div class="col-sm-3">
                    <div class="urun">
                        <img class="urunImg" src="https://kahhvecom.imgix.net/urunler/615_1589354732_SAO.jpg?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=22c536601bce2b9a518389abacb24f5d" alt="">
                    </div>
                    <span class="markaAdı">Colombia Supremo</span><br>
                    <span class="urunAdı">Urban Grind</span><br>
                    <span class="fiyat">49.99 TL</span>
                </div>
                <div class="col-sm-3">
                    <div class="urun">
                        <img class="urunImg" src="https://kahhvecom.imgix.net/urunler/795_1603712422_C8e.png?h=750&ixlib=php-1.0.6&lossless=1&w=750&s=e941e7b5242cdd2d242599ea0407070f" alt="">
                    </div>
                    <span class="markaAdı">Breakfast Blend</span><br>
                    <span class="urunAdı">Caffe Fresco</span><br>
                    <span class="fiyat">29.99 TL</span>
                </div>
            </div>
            </div>
            
            

        </div>
    </div>
</template>

<script>
export default {
    name:"SimilarProduct"
}
    
</script>

<style>
    .satirpad{
        padding-left: 70px;
    }
    .BenzerUrunlerContainer{
        background-color: #EBEBEB;
        width: 1900px;

    }
    .baslik{
        padding-left: 800px;
        font-size: 28px;
        color:  #C65800;
    }
    .urun{
        width: 300px;
        height: 300px;
        border: 2px solid #C65800;
    }
    .markaAdı{
        color: #C65800;
        font-weight: bold;
        text-align: center;
        align-items: center;
        padding-left: 110px;
    }
    .urunAdı{
        color: gray;
        font-size: 16px;
        text-align: center;
        align-items: center;
        padding-left: 115px;
        opacity: 60%;
    }
    .urunImg{
        width: 296px;
        height: 296px;
    }
    .fiyat{
        font-weight: bold;
        padding-left: 120px;
        color: #603813;
        opacity: 90%;
    }
</style>