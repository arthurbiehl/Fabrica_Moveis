<template>

    <main>

        <section-product-header />

        <div class="product">
            <div class="container_product">

                <div class="product_img">
                    <img src="../../static/product.jpg" alt="">
                </div>
                
                <div class="product_text">
                    <h2>Titulo do Produto</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore, magnam at modi fugit voluptates officiis blanditiis facere nesciunt doloribus optio consequatur vitae tempora fuga suscipit minus ut deserunt sunt quos. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quae, totam sunt alias magnam placeat eius vitae ducimus error cum perspiciatis aut nam reiciendis harum incidunt doloremque et sint. Cupiditate, debitis?   </p>
                    <button>
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-whatsapp" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M3 21l1.65 -3.8a9 9 0 1 1 3.4 2.9l-5.05 .9" />
                        <path d="M9 10a.5 .5 0 0 0 1 0v-1a.5 .5 0 0 0 -1 0v1a5 5 0 0 0 5 5h1a.5 .5 0 0 0 0 -1h-1a.5 .5 0 0 0 0 1" />
                        </svg>

                        Quero Comprar!!
                    </button>
                </div>

            </div>
        </div>
        
        <section-footer />

    </main>

</template>

<script setup>

  useHead({
    title: 'Produto x - Móveis Planejados'
  });

</script>

<style>

    .product {
        width: 100%;
        margin-top: 120px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .container_product {
        padding-bottom: 200px;
        width: 1300px;
        display: flex;
        justify-content: flex-start;
        align-items: flex-start;
        column-gap: 60px;
    }

    .container_product .product_img {
        width: 500px;
        height: 500px;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
        -webkit-box-shadow: 20px 20px 0px 0px rgba(237,237,237,1);
        -moz-box-shadow: 20px 20px 0px 0px rgba(237,237,237,1);
        box-shadow: 20px 20px 0px 0px rgba(237,237,237,1);
    }

    .container_product .product_img img {
        width: 100%;
    }

    .container_product .product_text {
        flex: 1;
        padding-top: 20px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: flex-start;
    }

    .container_product .product_text h2 {
        font-size: 25px;
        margin-bottom: 20px;
        
    }

    .container_product .product_text p {
        margin-bottom: 20px;
        font-size: 15px;
        font-weight: 400;
        color: rgb(140, 140, 140);
    }
    
    .container_product .product_text button {
        padding: 10px 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: #06d57f;
        color: white;
        font-size: 14px;
        font-weight: 500;
        column-gap: 6px;
        cursor: pointer;
        transition: .3s ;
        
    }

    .container_product .product_text button:hover {
        padding: 10px 40px;
    }

    .container_product .product_text svg {
        width: 27px;
        height: 27px;
        stroke: white;
    }

    @media (max-width: 1320px ) {
        
        .container_product {
            width: 900px;
        }

        .container_product .product_img {
            width: 400px;
            height: 400px;
            -webkit-box-shadow: 10px 10px 0px 0px rgba(237,237,237,1);
            -moz-box-shadow: 10px 10px 0px 0px rgba(237,237,237,1);
            box-shadow: 10px 10px 0px 0px rgba(237,237,237,1);
        }

    } 

    @media (max-width: 920px ) {

        .container_product {
            width: 600px;
            column-gap: 10px;
        }

        .container_product .product_img {
            width: 250px;
            height: 250px;
        }

        .container_product .product_text {
            padding-top: 5px;
        }

    } 

    @media (max-width: 620px ) {

        .product {
            padding: 0 10px;
        }
        
        .container_product {
            width: 100%;
            flex-direction: column;
            align-items: center;
            row-gap: 40px;
        }

        .container_product .product_img {
            width: 100%;
        }

        .container_product .product_text {
            padding-top: 0;
            width: 100%;
        }
        

    } 

</style>