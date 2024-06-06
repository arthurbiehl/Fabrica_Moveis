<template>
    
    <div class="product_card">

        <div class="product_image">
            <img src="../../static/product.jpg" alt="">
            <div class="background"></div>
        </div>

        <div class="product_body">
            <h2>{{ product.title }}</h2>
            <p>{{ limitString(product.description, 80) }}</p>
            
        </div>

    </div>

</template>

<script setup>

    const props = defineProps({
        product: {}
    });


</script>

<style>

    .product_card {
        width: 300px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        transition: .3s;
        padding-bottom: 40px;
        cursor: pointer;
    }

    .product_card:hover {
        box-shadow: 0px 1px 15px rgba(0, 0, 0, 0.07);
    }

    .product_card:hover p {
        color: #424242;
    }

    .product_image {
        width: 100%;
        height: 200px;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
        position: relative;
    }

    .background {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(92, 45, 7, 0.445);
    }

    .product_image img {
        width: 100%;
    }

    .product_body {
        padding: 20px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        row-gap: 10px;
    }

    .product_body h2 {
        font-size: 16px;
        font-weight: 600;
        color: #424242;
    }

    .product_body p {
        font-size: 13px;
        color: rgb(158, 158, 158);
        transition: .3s;
    }
    

    @media (max-width: 1320px) {

        .product_card {
            width: 260px;
        }

        .product_card:last-child {
            margin: 0 auto;
        }
        
    }

    @media (max-width: 920px) {

        .product_card {
            width: 280px;
        }

        .product_card:last-child {
            margin: 0;
        }
        
    }

    @media (max-width: 620px) {

        .product_card {
            width: 100%;
        }
        
    }

</style>