<template>
    <main>

        <section-product-header />

        <div class="products_page">
            <div class="products_header">
                <h1>Nossos Produtos</h1>
            </div>
            <div class="products_container">
                
                <product-card-page-product />
                <product-card-page-product />
                <product-card-page-product />
                <product-card-page-product />

            </div>
        </div>


        <section-footer />
    </main>

</template>

<script setup>

  useHead({
    title: 'Produtos - Móveis Planejados'
  });

</script>

<style>

    main {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .products_page {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 120px;

    }
    
    .products_page .products_header {
        width: 1300px;
        display: flex;
        justify-content: flex-start;
        align-items: center;
    }  

    .products_page .products_header h1 {
        font-size: 20px;
        
    }

    .products_page .products_container {
        width: 1300px;
        padding-bottom: 400px;
        display: flex;
        align-content: flex-start;
        justify-content: flex-start;
        flex-wrap: wrap;
        row-gap: 20px;
        column-gap: 20px;
    }


    @media (max-width: 1320px) {
        .products_page .products_header {
            width: 900px;
        }

        .products_page .products_container {
            width: 900px;
            row-gap: 15px;
            column-gap: 15px;

        }
        
    }

    
    @media (max-width: 920px) {
        .products_page .products_header {
            width: 600px;
        }

        .products_page .products_container {
            width: 600px;
            row-gap: 10px;
            column-gap: 10px;

        }
        
    }

    @media (max-width: 620px) {

        .products_page {
            padding: 0 20px;
        }

        .products_page .products_header {
            width: 100%;
        }

        .products_page .products_container {
            width: 100%;
            row-gap: 20px;
            align-content: center;
            justify-content: center;
        }
        
    }



</style>