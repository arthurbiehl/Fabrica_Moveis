<template>
    
    <div class="product_card_page">

        <div class="product_image_page">
            <img src="../../static/product.jpg" alt="">
            <div class="background_page"></div>
        </div>

        <div class="product_body_page">
            <h2>asdasdasdasdasda</h2>
            <p>asasasasassasasasasa</p>
            
        </div>

    </div>

</template>

<style>

    .product_card_page {
        width: 310px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        transition: .3s;
        padding-bottom: 40px;
        cursor: pointer;
    }

    .product_card_page:hover {
        box-shadow: 0px 1px 15px rgba(0, 0, 0, 0.07);
    }

    .product_card_page:hover p {
        color: #424242;
    }

    .product_image_page {
        width: 100%;
        height: 200px;
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
        position: relative;
    }

    .background_page {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(92, 45, 7, 0.445);
    }

    .product_image_page img {
        width: 100%;
    }

    .product_body_page {
        width: 100%;
        padding: 20px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        row-gap: 10px;
    }

    .product_body_page h2 {
        font-size: 16px;
        font-weight: 600;
        color: #424242;
    }

    .product_body_page p {
        font-size: 13px;
        color: rgb(158, 158, 158);
        transition: .3s;
    }


    @media (max-width:1320px ) {

        .product_card_page {
            width: 290px;
        }

    }

    
    @media (max-width:920px ) {

        .product_card_page {
            width: 295px;
        }

    }
    
    
    @media (max-width: 620px ) {

        .product_card_page {
            width: 400px;
        }

    }

    @media (max-width: 450px ) {

        .product_card_page {
            width: 100%;
        }

    }

    
</style>