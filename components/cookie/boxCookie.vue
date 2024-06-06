<template>
    <VueIfBot>
        <cookie-consent>
            <template slot="message">
                <h2>Utilização de Dados</h2>
                <p>Ao navegar em nosso site, você concorda com a utilização de cookies e outras tecnologias semelhantes para aprimorar e personalizar a sua experiência. <a class="btn btn-link" href="/politicas">Visualizar Políticas</a></p>
                
            </template>
            <template slot="button" style="background: red;">
                <button class="btn btn-info">Aceitar</button>
            </template>
        </cookie-consent>
    </VueIfBot>
</template>

<script>
    import VueIfBot from 'vue-if-bot/dist/vue-if-bot.es'
    import CookieConsent from 'vue-cookieconsent-component/src/components/CookieConsent.vue'

    export default {
        components: {
            VueIfBot,
            CookieConsent
        }
    }
</script>

<style>
    .cookie-consent {
        position: fixed;
        bottom: 20px;
        right: 20px;
        width: 400px;
        background: white;
        border-radius: 4px;
        display: flex;
        flex-direction: column;
        box-shadow: 0 0.625em 1.875em rgb(57 62 72 / 10%);
        padding: 30px 40px;
        animation: fromLeft .9s ease-in-out;
    }

    .cookie-consent h2 {
    font-size: 15pt !important;
    font-weight: bold;
        margin: 0 0 0.6em 0;
    }

    .cookie-consent p {
        margin-bottom: 20px;
        font-size: 10pt;
        font-family: inherit;
        line-height: 1.45em;
    }

    .cookie-consent p a {
        font-size: 10pt;
        font-family: inherit;
        line-height: 1.45em;
        font-weight: 500;
        color: #3684ce;
    }

    /* slot button */
    .cookie-consent button {
        border: none;
        padding: 1em 2em;
        margin-bottom: 0.625em;
        display: inline-block;
        outline: 0;
        box-shadow: 0 0 0 0 transparent;
        margin-right: 1.25em;
        border-radius: 0.25em;
        cursor: pointer;
        transition: none!important;
        font-weight: bold;
        font-family: inherit;
        font-size: 0.9em;
        user-select: none;
        -moz-user-select: none;
        -khtml-user-select: none;
        -webkit-user-select: none;
        -o-user-select: none;
        text-align: center;
        width: 100%;
    }

    .cookie-consent button:hover {
        background: #f5f5f5;
    }

    @keyframes fromLeft {
        0% {
            opacity: 0;
            transform: translateX(100%);
        }
        100% {
            opacity: 1;
            transform: translateX(0);
        }
    }

    @media (max-width: 768px) {
        .cookie-consent {
            width: 100%;
            bottom: 0;
            right: 0;
            left: 0;
            margin: 0 auto;
            padding: 20px;
            border-radius: 0;
            box-shadow: none;
        }
    }

</style>