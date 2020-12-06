<template>
    <div>
        <div >
            <div class="upperNavbar">75TL ve üzeri ÜCRETSİZ KARGO!</div>
            <div  >
                <b-navbar class="center" toggleable="sm" type="light" variant="light">
                <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
                
                <b-nav-item class="menuItems" href="//localhost:3000/" style="color: transparent;">
                    <img class="logo" src="https://kahhve.com/zeplin/img/logo_mini.png" alt="">
                </b-nav-item>
            
                <b-navbar-nav class="menuItemPadding">
                        <b-nav-item class="menuItems" href="/Coffeepage" >  KAHVELER</b-nav-item>
                        <b-nav-item class="menuItems"  href="#">EKİPMAN & AKSESUARLAR</b-nav-item>
                        <b-nav-item class="menuItems">TANIŞMA SETLERİ</b-nav-item>
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
                        <b-nav-item href="/Loginpage" class="menuItems">GİRİŞ</b-nav-item>
                        <b-nav-item href="#" class="menuItems">
                            <p class="h3 mb-2"> <b-icon  icon="search" style="color: #C65800"></b-icon>
                        </p></b-nav-item>
                        <b-nav-item href="#" class="menuItems">
                            <p class="h3 mb-2"> <b-icon  icon="heart" style="color: #C65800"></b-icon>
                        </p></b-nav-item>
                        <b-nav-item href="/Shoppingbasket" class="menuItems" >
                            <p class="h3 mb-2"> <b-icon  icon="cart4" style="color: #C65800" /></p>
                        </b-nav-item>
                       
                    </b-navbar-nav>
            </b-navbar>
            </div>
        </div>
        
        
        
    </div>
</template>

<script>
import Vue from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'


Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)
export default {
    

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
    
   
</style>