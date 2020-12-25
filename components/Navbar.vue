<template>
    <div>
        <div >
            <div class="upperNavbar">75TL ve üzeri ÜCRETSİZ KARGO!</div>
            <div  >
                <b-navbar class="center" toggleable="sm" type="light" variant="light">
                <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
                
                <b-nav-item class="menuItems" href="#" style="color: transparent;">
                    <nuxt-link to="/">
                        <img class="logo" src="https://kahhve.com/zeplin/img/logo_mini.png" alt="">
                    </nuxt-link>
                </b-nav-item>
            
                <b-navbar-nav class="menuItemPadding">
                        <b-nav-item class="menuItems" href="#" >  
                            <nuxt-link to="/Coffeepage" style="color:#603813;text-decoration: none">
                                KAHVELER
                            </nuxt-link> 
                            </b-nav-item>
                        <b-nav-item class="menuItems"  href="#">
                            <nuxt-link to="#" style="color:#603813;text-decoration: none">
                                EKİPMAN & AKSESUARLAR
                            </nuxt-link></b-nav-item>
                        <b-nav-item class="menuItems">
                            <nuxt-link to="#" style="color:#603813;text-decoration: none">
                                TANIŞMA SETLERİ
                            </nuxt-link></b-nav-item>
                        <b-nav-item-dropdown text="MARKALAR" right class="menuItems">
                            <b-dropdown-item href="#" >Able</b-dropdown-item>
                            <b-dropdown-item href="#">Bianco</b-dropdown-item>
                            <b-dropdown-item href="#">Bravilor Bonamat</b-dropdown-item>
                            <b-dropdown-item href="#">Coffe Vergnano</b-dropdown-item>
                            <b-dropdown-item href="#">Bravilor Bonamat</b-dropdown-item>
                            <b-dropdown-item href="#">Caffe Vergnano</b-dropdown-item>
                            <b-dropdown-item href="#">Coffee Sapiens</b-dropdown-item>
                            <b-dropdown-item href="#">Coffeerem</b-dropdown-item>
                            <b-dropdown-item href="#">Delter</b-dropdown-item>
                            <b-dropdown-item href="#">Felicita</b-dropdown-item>
                            <b-dropdown-item href="#">Illy</b-dropdown-item>
                            <b-dropdown-item href="#">Kronotrop</b-dropdown-item>
                            <b-dropdown-item href="#">Puly Caff</b-dropdown-item>
                            <b-dropdown-item href="#">Shorts Coffee</b-dropdown-item>
                            <b-dropdown-item href="#">The Dripster</b-dropdown-item>
                            <b-dropdown-item href="#">Urban Tools</b-dropdown-item>
                        </b-nav-item-dropdown>

                        <b-nav-item class="kultur">KÜLTÜR </b-nav-item>
                        <b-nav-item class="menuItems">HEDİYELİKLER</b-nav-item>
                    </b-navbar-nav>
                    <b-navbar-nav class="ml-auto sag">
                        <b-nav-item href="#" class="menuItems">
                         <nuxt-link to="/Loginpage" style="color:#603813;text-decoration: none">
                             GİRİŞ
                             </nuxt-link></b-nav-item>
                        <b-nav-item href="#" class="menuItems">
                            <p class="h3 mb-2"> <b-icon  icon="search" style="color: #C65800"></b-icon>
                        </p></b-nav-item>
                        <b-nav-item href="#" class="menuItems">
                            <p class="h3 mb-2"> <b-icon  icon="heart" style="color: #C65800"></b-icon>
                        </p></b-nav-item>
                        <b-nav-item href="#" class="menuItems" id="popover-target-1">
                             <nuxt-link to="/Shoppingbasket" style="color:#603813;text-decoration: none" >
                                <p class="h3 mb-2"> <b-icon  icon="cart4" style="color: #C65800" /></p>
                               
                                
                             </nuxt-link>
                            
                        </b-nav-item>
                        <b-popover  target="popover-target-1" triggers="hover" placement="top" >
                            <br>
                            <div style="width:255px">
                                <hr color="#C65800" size="4">
                            </div>
                            <div>
                                <j >Toplam</j> <j class="popupend">0.00 TL</j>
                            </div>
                            <br>
                            <div>
                                <nuxt-link to="/Shoppingbasket">
                                     <button class="popsppgnbtn">SEPETE GİT</button>
                                </nuxt-link>
                               
                                <button class="popcrtbtn">SİPARİŞİ TAMAMLA</button>
                            </div>
                            <br>
                        </b-popover>
                       
                    </b-navbar-nav>
            </b-navbar>
            </div>
            
        </div>
        
        
        
    </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'
import ShoppingCart from "./ShoppingCart"


Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)
export default {
    data(){
        return{
            isHovered:false
        }
    },
    methods:{
        handleHover(hovered){
            this.isHovered=hovered
        }
    },
    components:{
        ShoppingCart
    }

}
</script>

<style>

    .dropDown{
        background-color:transparent;
        color: #603813;
        border-width: 0;
        
    }
    .logo{
        width: 90px;
    }

    .upperNavbar{
        background-color:#C65800;
        color: wheat;
        text-align: center;
        
    }

    .firstdiv{
        width: 200px;
    }

    .menuItems{
        color: #603813;
        font-size: 18px;
        font-family: sans-serif;
    }

    .kultur{
        color: #C65800;
        font-weight: bold;
        font-size: 18px;
        font-family: sans-serif;
    }

    .center{
        text-align: center;
        align-items: center;
        padding-left: 200px;
    }

    .menuItemPadding{
        padding: 20px;
    }
    .sag{
        padding-right: 200px;
    }
    .popupend{
        padding-left: 130px;
        padding-top: 0px;
        color: #C65800;
        font-size:20px
    }
    .popsppgnbtn{
    background-color: #603813;
    color: white;
    border-radius: 10px;
    right: 0;
    position: absolute;
    left:70px;
    border: #603813;
    font-size: 13px;
    }
    .popcrtbtn{
    background-color:  #c65800;
    color: white;
    border-radius: 10px;
    position: absolute;
    left:145px;
    border: #c65800;
    font-size: 13px; 
    }
   
</style>