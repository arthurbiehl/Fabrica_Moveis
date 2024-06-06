<template>
    <footer>
        <div class="footer_container">
            <div class="footer_item">
                <img src="/static/foto2fundobranco.png.jpeg" alt="">
            </div>
            <div class="footer_item">
                <h2>Links</h2>
                <a href="#">Início</a>
                <a href="#">Sobre Nós</a>
                <a href="#">Produtos</a>
                <a href="#">Fale Conosco</a>
            </div>
            <div class="footer_item">
                <h2>Redes Sociais</h2>
                <a href="#">Facebook</a>
                <a href="#">Instagram</a>

            </div>

        </div>
        <div class="footer_infos">
            <p>© {{new Date().getFullYear()}} <a href="https://darbybiehl.com.br">DarbyBiehl</a>. Todos os direitos reservados.</p>
            <a href="/politicas">Políticas de Privacidade</a>
        </div>
    </footer>
</template>

<style>

    footer{
        display: flex;
        flex-direction: column;
        align-items: center;
        row-gap: 100px;
        width: 100%;
        padding: 100px 0px;
        box-shadow: 0px 3px 20px rgba(0, 0, 0, 0.1);
    }

    .footer_container {
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
        width: 1300px;
        height: 200px;
    }

    .footer_item {
        width: 300px;
        row-gap: 5px;
        display: flex;
        align-items: flex-start;
        justify-self: center;
        flex-direction: column;
    }

    .footer_item h1 {
        font-size: 20px;
    }

    .footer_item h2 {
        font-size: 20px;
        margin-bottom: 20px;
    }

    .footer_item a {
        text-decoration: none;
        color:  rgb(160, 160, 160);
        transition: 0.3s;
    }

    .footer_item img {
        display: flex;
        justify-content: left;
        align-items: left;
        top: 0;
        left: 0;
        width: 300px;
        background-size: cover;
    }

    .footer_item a:hover {
        color: rgb(0, 0, 0);

    }

    .footer_infos {
        width: 1300px;
        display: flex;
        justify-content: space-between;
    }

    .footer_infos a{
        text-decoration: none;
        font-weight: bold;
        color: black;
    }

    @media (max-width: 1320px) {
        .footer_container {
            width: 900px;
        }

        .footer_item {
            width: 250px;
        }

        .footer_infos {
            width: 900px;
        }
    }

    @media (max-width: 920px) {
        .footer_container {
            flex-direction: column;
            align-items: center;
            width: 600px;
            row-gap: 50px;
        }

        .footer_item {
            width: 100%;
            align-items: center;
        }

        .footer_infos {
            text-align: center;
            width: 600px;
            flex-direction: column;
            align-items: center;
            row-gap: 20px;
        }
    }

    @media ( max-width: 620px) {

        .footer_container {
            width: 100%;
        }

        .footer_item {
            width: 100%;
        }

        .footer_infos {
            width: 100%;
        }
    }


</style>