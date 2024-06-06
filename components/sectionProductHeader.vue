<template>
    <header>
        <div class="header_product_container">
            <h2>MOVEIS PLANEJADOS</h2>
            <div class="header_product_links">
                <a href="/">Início</a>
                <a href="/">Sobre Nós</a>
                <a href="/produtos">Produtos</a>
                <a href="/">Fale Conosco</a>
            </div>

            <svg @click="mobileMenu = !mobileMenu" xmlns="http://www.w3.org/2000/svg" id="open_menu_product" class="icon icon-tabler icon-tabler-align-right" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
            <path d="M4 6l16 0" />
            <path d="M10 12l10 0" />
            <path d="M6 18l14 0" />
            </svg>

        </div>
        <transition name="slide-fade">
            <div v-if="mobileMenu" class="mobile_menu_product">
                <div class="header_mobile_menu_product">
                    <svg @click="mobileMenu = !mobileMenu" xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-x" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M18 6l-12 12" />
                    <path d="M6 6l12 12" />
                    </svg>
                </div>
                <div class="body_mobile_menu_product">
                    <a href="#">Início</a>
                    <a href="#">Sobre Nós</a>
                    <a href="#">Produtos</a>
                    <a href="#">Fale Conosco</a>
                </div>
            </div>
        </transition>
    </header>

</template>

<script setup>

    const mobileMenu = ref(false);

</script>

<style>

    header {
        width: 100%;
        height: 80px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .header_product_container {
        width: 1300px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .header_product_container h2 {
        color: black;
        font-size: 20px;
    }

    .header_product_container .header_product_links {
        display: flex;
        justify-content: space-between;
        align-items: center;
        column-gap: 40px;
    }

    .header_product_container .header_product_links a {
        text-decoration: none;
        color:  black;
        font-size: 14px;
        transition: .3s;
    }

    .header_product_container .header_product_links a:hover {
        color:  rgb(88, 88, 88);
    }

    /* mobile menu */

    #open_menu_product {
        display: none;
        width: 30px;
        height: 30px;
        stroke: rgb(0, 0, 0);
    }

    .mobile_menu_product {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        position: fixed;
        top: 0;
        left: 0;
        background: white;
        padding-bottom: 40px;
        z-index: 99;
    }
    

    .header_mobile_menu_product {
        width: 100%;
        height: 80px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        padding: 0 10px;
    }

    .header_mobile_menu_product svg {
        width: 30px;
        height: 30px;
        stroke: rgb(73, 73, 73);
    }

    .body_mobile_menu_product {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        row-gap: 20px;
        
    }

    .body_mobile_menu_product a {
        text-decoration: none;
        color:rgb(73, 73, 73);
        font-weight: 500;
    }


    @media (max-width: 1320px ) {
        .header_product_container {
            width: 900px;
        }
    }

    @media (max-width: 920px ) {
        .header_product_container {
            width: 600px;
        }

        .header_product_container .header_product_links {
            column-gap: 20px;
        }
    }

    @media (max-width: 620px) {

        header {
            padding: 0 10px;
        }

        .header_product_container {
            width: 100%;
        }

        .header_product_container .header_product_links {
            display: none;
        }

        #open_menu_product {
            display: flex;
        }
        
    }

    /* animacao para o header mobile */

    .slide-fade-enter-active {
        transition: all .9s ease-in-out;
    }
    
    .slide-fade-leave-active {
        /* from left */
        transition: all .7s cubic-bezier(1.0, 0.5, 0.8, 1.0);
    }
    
    .slide-fade-enter, .slide-fade-leave-to {
        transform: translateY(-500px);
        opacity: 0;
    }

</style>