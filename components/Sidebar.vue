<template>
    <div class="sidenav vl">
      
        <div >
            <a1 href="#" >MARKA</a1><br>
            <a2 href="#">Beanofme(1)</a2><br>
            <a2 href="#">Bianco(3)</a2><br>
            <a2 href="#">Caffe Fresco(8)</a2><br>
            <a2 href="#">Caffe Vergnano(10)</a2><br>
            <a2 href="#">Caffe Sapiens(3)</a2><br>
            <a2 href="#">.......</a2><br><br>
            

        </div>
        <div >
            <a1 href="#" >ORİGİN</a1><br>
            <a2 href="#">Blend(34)</a2><br>
            <a2 href="#">Brazil(5)</a2><br>
            <a2 href="#">Colombia(6)</a2><br>
            <a2 href="#">CostaRica(4)</a2><br>
            <a2 href="#">El Salvador(1)</a2><br>
            <a2 href=  "#">.......
                 <!-- <div class="accordion" role="tablist">
                    <b-card no-body class="mb-1">
                    <b-card-header header-tag="header" class="p-1" role="tab">
                        <b-button block v-b-toggle.accordion-1 variant="info">Accordion 1</b-button>
                    </b-card-header>
                    <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
                        <b-card-body>
                        <b-card-text>I start opened because <code>visible</code> is <code>true</code></b-card-text>
                        <b-card-text>{{ text }}</b-card-text>
                        </b-card-body>
                    </b-collapse>
                    </b-card>
                </div>     -->
            </a2><br><br>

        </div>

        <div >
            <a1 href="#" >TAT</a1><br>
            <a2 href="#">Aromalı Kahve(6)</a2><br>
            <a2 href="#">Meyvemsi/Az Kavrulmuş(13)</a2><br>
            <a2 href="#">Orta Yumuşak/Dengeli(44)</a2><br>
            <a2 href="#">Yoğun/Sert(18)</a2><br><br>

        </div>

        <div >
            <a1 href="#" >EKİPMAN</a1><br>
            <a2 href="#">Decaf Kahve(3)</a2><br>
            <a2 href="#">Espresso Kahve(13)</a2><br>
            <a2 href="#">Filtre Kahve(65)</a2><br>
            <a2 href="#">Kapsül Kahve(5)</a2><br>
            <a2 href="#">Soğuk Kahve(12)</a2><br>
            <a2 href="#">Türk Kahvesi(5)</a2><br><br>

        </div>
</div>
    
</template>

<script>
export default {
    name:"Sidebar",
    
}
</script>

<style >


    .sidenav {
       
        width: 100%; /* Set the width of the sidebar */
        position: static; /* Fixed Sidebar (stay in place on scroll) */
        z-index: 1; /* Stay on top */
        background-color: #fff; /* Black */
        overflow-x: hidden; /* Disable horizontal scroll */
        padding-left: 20%;
        
    }
    a1{
        color:#c65800;
        font-size: 34px;
    }
    a2{
        color: #603813;
        font-size: 16px;
    }

    .vl {
        border-right: 4px solid #c65800 ;
        
        
    } 
   
</style>