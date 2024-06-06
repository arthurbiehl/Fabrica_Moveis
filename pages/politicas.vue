<template>
    <main>
        <div class="politic_container">
            <div class="politic_link">
                <a href="/">Pagina Inicial</a> / <a href="#">Políticas de Privacidade</a>
            </div>
            <div class="politic_body">
                <div class="politic_text">
                    <h2>Termos de uso e Autorização do Usuário</h2>
                    <p>
                        As partes se obrigam a cumprir com a legislação de proteção de dados brasileira (Lei n.º 13.709/2018).
                    </p>
                    <p>
                        As partes e seus representantes legais, através deste Contrato, autorizam o tratamento de seus dados pessoais, nos termos do artigo 7º, I da Lei 13.709/2018, unicamente para o atingimento do objeto deste Contrato.
                    </p>
                    <p>
                        Todos os dados dos <b>USUÁRIOS</b> cadastrados no domínio da administradora estão em segurança e protegidos em servidor de dados, nos termos da Lei Geral de Proteção de Dados. Ao aceitar estes termos e condições, o <b>USUÁRIO</b> estará autorizando que <b>SEUS DADOS SEJAM UTILIZADOS PARA COMERCIALIZAR PRODUTOS E SERVIÇOS.</b>
                    </p>
                    <p>
                        <b>O USUÁRIO</b> permite que seus dados sejam compartilhados entre os demais <b>USUÁRIOS</b> que utilizem a plataforma.
                    </p>
                    <p>
                        A administradora garante que os dados dos <b>USUÁRIOS</b> serão utilizados ou tratados, apenas, para possibilitar os serviços da plataforma, na medida em que necessário. Não utilizará, nem de outro modo tratará, os Dados nem as informações derivadas dos mesmos para qualquer publicidade ou outros fins comerciais semelhantes.
                    </p>
                    <p>
                        A administradora não vende e não comercializa informações que identifiquem os usuários. Também não compartilhamos ou transferimos, de qualquer forma, suas Informações pessoais para terceiros estranhos a plataforma.
                    </p>
                    <p>
                        Armazenaremos as informações pessoais, somente, pelo tempo que for necessário para cumprir o objetivo para o qual foram coletadas, cumprir requisitos legais ou regulamentares ou durante o prazo de prescrição legal de possíveis responsabilidades legais ou contratuais. Após o término do período, os dados serão excluídos ou inutilizados de forma que nenhuma pessoa possa ser individualizada, conforme permitido pela legislação pátria.
                    </p>
                    <p>
                        Os dados serão armazenados em banco de dados. A exclusão dos dados se dará por meio de eliminação no banco de dados do servidor.
                    </p>
                    <p>
                        A administradora garante ainda que, excluirá ou inutilizará todos os Dados obtidos até o prazo de 05 (cinco) anos contados da rescisão ou término do presente Contrato.
                    </p>
                </div>
            </div>
        </div>
    </main>
</template>

<script setup>

  useHead({
    title: 'Políticas - Móveis Planejados'
  });

</script>


<style scoped>

    main {
        width: 100%;
        background: #F5F5F5;
        display: flex;
        justify-content: center;
        padding-top: 100px;
        padding-bottom: 100px;
    }

    .politic_container {
        width: 800px;
        height: unset;
        background: #fff;
        border-radius: 5px;
        padding: 50px 70px;
        margin-bottom: 100px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.05);
    }

    .politic_container .politic_link {
        width: 100%;
        display: flex;
        justify-content: flex-start;
        align-items: center;
        margin-bottom: 30px;
        column-gap: 5px;
        color: rgb(59, 59, 59);
    }

    .politic_container .politic_link a {
        padding: 7px 15px;
        border-radius: 20px;
        background: #F5F5F5;
        color: rgb(59, 59, 59);
        font-weight: 600;
        font-size: 11px;
    }

    .politic_container .politic_body {
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        column-gap: 100px;
    }

    .politic_container .politic_body .politic_text {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    .politic_container .politic_body .politic_text h2 {
        font-size: 20px;
        font-weight: bold;
        color: rgb(59, 59, 59);
        margin-bottom: 20px;
    }

    .politic_container .politic_body .politic_text p {
        font-size: 13px;
        color: rgb(59, 59, 59);
        line-height: 1.5;
        margin-bottom: 10px;
    }

    .politic_container .politic_body .politic_box {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        border: 2px solid rgb(243, 243, 243);
        border-radius: 5px;
        padding: 25px;
    }

    .politic_container .politic_body .politic_box h2 {
        font-size: 18px;
        font-weight: bold;
        color: rgb(59, 59, 59);
        margin-bottom: 10px;
    }

    .politic_container .politic_body .politic_box p {
        font-size: 13px;
        color: rgb(59, 59, 59);
        line-height: 1.5;
    }

</style>