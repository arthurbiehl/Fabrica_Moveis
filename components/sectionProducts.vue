<template>
    <div class="products" id="products">

        <div class="product_title">
            <h1>Nossos Produtos</h1>
        </div>

        <div class="product_container">

            <product-card-product
                v-for="(product, index) in products"
                :key="index + '_product'"
                :product="product"
            />


        </div>

    </div>
</template>

<script setup>

    import { useMyProducts } from "~/store/products.store";

    const store = useMyProducts();
    const {products} = storeToRefs(store);


</script>

<style>

    .products {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 100px;
        row-gap: 50px;
    }

    .product_title {
        width: 1300px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .product_container {
        width: 1300px;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    @media (max-width: 1320px) {

        .product_container {
            width: 900px;
            flex-wrap: wrap;
            row-gap: 20px;
        }
        
    }

    @media (max-width: 920px) {

        .product_container {
            width: 600px;
        }
        
    }

    @media (max-width: 620px) {

        .products {
            padding: 0px 50px;
        }

        .product_container {
            width: 100%;
        }
        
    }

    @media (max-width: 460px) {

        .products {
            padding: 0px 20px;
        }

    }



</style>