<template>
    
    <div class="products">
        <h2>O QUE FAZEMOS?</h2>
        <div class="products_container">
            
            <div class="product_item">
                <img src="../static/imagem4.jpg" alt="">
                
                <div class="product_text">
                    <h2>PRODUTO</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, pariatur.</p>
                </div>
            </div>
            <div class="product_item">
                <img src="../static/imagem4.jpg" alt="">
                
                <div class="product_text">
                    <h2>PRODUTO</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, pariatur.</p>
                </div>
            </div>
            <div class="product_item">
                <img src="../static/imagem4.jpg" alt="">
                
                <div class="product_text">
                    <h2>PRODUTO</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, pariatur.</p>
                </div>
            </div>
            <div class="product_item">
                <img src="../static/imagem2.jpg" alt="">
                
                <div class="product_text">
                    <h2>PRODUTO</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, pariatur.</p>
                </div>
            </div>
            
        </div>
    </div>
</template>

<style>

    .products {
        width: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin-bottom: 30px;
    }

    .products_container {
        width: 1300px;
        display: flex;
        align-items: center;
        justify-content: center;
        column-gap: 30px;
        margin-top: 30px;
    }

    .product_item {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 250px;
        height: 400px;
        border-radius: 5px;
        box-shadow: 0px 1px 15px rgba(0, 0, 0, 0.1);
        transition: 0.6s;
    }

    .product_item img {
        width: 99%;
        height: 40%;
        border-radius: 3px;
    }

    .product_item h2 {
        margin-top: 30px;
        font-size: 18px;
        font-weight: 600;

    }

    .product_item p {
        display: flex;
        font-size: 16px;
        margin-top: 15px;
        color: rgb(155, 155, 155);
    }

    .product_item:hover {
        width: 260px;
        height: 410px;
        background: rgb(241, 241, 241);
    }

    .product_text {
        width: 190px;
        height: 60%;
        display: flex;
        flex-direction: column;
        margin: 0 20px;
    }





</style>