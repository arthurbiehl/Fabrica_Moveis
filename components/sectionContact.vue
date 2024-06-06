<template>
   
   <div class="contact" id="contact">
      <h1>FALE CONOSCO!</h1>
      <div class="contact_container">
         <div class="contact_text">
            <h2>Por onde Estamos?</h2>
            <span>Contatar-nos é muito importante!!</span>
            <div class="contact_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin-filled" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M18.364 4.636a9 9 0 0 1 .203 12.519l-.203 .21l-4.243 4.242a3 3 0 0 1 -4.097 .135l-.144 -.135l-4.244 -4.243a9 9 0 0 1 12.728 -12.728zm-6.364 3.364a3 3 0 1 0 0 6a3 3 0 0 0 0 -6z" stroke-width="0" fill="currentColor" />
               </svg>
               <div class="item_text">
                  <h2>Localização</h2>
                  <p>Nada</p>
               </div>
            </div>
            <div class="contact_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-at" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M12 12m-4 0a4 4 0 1 0 8 0a4 4 0 1 0 -8 0" />
               <path d="M16 12v1.5a2.5 2.5 0 0 0 5 0v-1.5a9 9 0 1 0 -5.5 8.28" />
               </svg>
               <div class="item_text">
                  <h2>Email</h2>
                  <p>nada</p>
               </div>
            </div>
            <div class="contact_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-device-mobile-filled" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M16 2a3 3 0 0 1 2.995 2.824l.005 .176v14a3 3 0 0 1 -2.824 2.995l-.176 .005h-8a3 3 0 0 1 -2.995 -2.824l-.005 -.176v-14a3 3 0 0 1 2.824 -2.995l.176 -.005h8zm-4 14a1 1 0 0 0 -.993 .883l-.007 .117l.007 .127a1 1 0 0 0 1.986 0l.007 -.117l-.007 -.127a1 1 0 0 0 -.993 -.883zm1 -12h-2l-.117 .007a1 1 0 0 0 0 1.986l.117 .007h2l.117 -.007a1 1 0 0 0 0 -1.986l-.117 -.007z" stroke-width="0" fill="currentColor" />
               </svg>
               <div class="item_text">
                  <h2>Telefone</h2>
                  <p>nada</p>
               </div>
            </div>
            <div class="contact_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-whatsapp" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M3 21l1.65 -3.8a9 9 0 1 1 3.4 2.9l-5.05 .9" />
               <path d="M9 10a.5 .5 0 0 0 1 0v-1a.5 .5 0 0 0 -1 0v1a5 5 0 0 0 5 5h1a.5 .5 0 0 0 0 -1h-1a.5 .5 0 0 0 0 1" />
               </svg>
               <div class="item_text">
                  <h2>Whatsapp</h2>
                  <p>nada</p>
               </div>
            </div>

         </div>
         <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3461.211078275176!2d-51.1663855!3d-29.8293285!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95196f4e74800fb9%3A0x3731768ad7ba452d!2sR.%20Gov.%20Palheta%20-%20Get%C3%BAlio%20Vargas%2C%20Sapucaia%20do%20Sul%20-%20RS%2C%2093210-130!5e0!3m2!1spt-BR!2sbr!4v1694802387334!5m2!1spt-BR!2sbr" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

      </div>
   </div>
</template>

<style>

   .contact {
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin-bottom: 100px;
   }

   .contact_container {
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      width: 1300px;
      margin-top: 80px;
   }

   .contact_text{
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      width: 650px;
   }

   .contact_text span {
      font-size: 14px;
      color: rgb(160, 160, 160);
      margin-top: 10px;
      margin-bottom: 20px;
   }

   .contact_item {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      margin-top: 20px;
   }

   
   .contact_item svg{
      width: 30px;
      height: 30px;
      margin-right: 10px;
   }

   .contact_item h2 {
      font-weight: 500;
      font-size: 14px;
   }

   .contact_item p {
      color: rgb(138, 138, 138);
   }
   
   .contact h1 {
      font-size: 30px;
      font-weight: 800;
   }

   .contact_container iframe   {
      width: 600px;
      height: 400px;
   }


   @media  (max-width: 1320px){
      .contact_container{
         width: 900px;
      }

      .contact_container .contact_text {
         width: 425px;
      }

      .contact_container iframe {
         width: 425px;
         height: 350px;
      }

   }

   @media  (max-width: 920px){
      .contact_container{
         flex-direction: column;
         align-items: center;
         width: 600px;
         row-gap: 40px;

      }

      .contact_container .contact_text {
         width: 600px;
      }

      .contact_container iframe {
         width: 600px;
         height: 400px;
      }

   }

   @media  (max-width: 620px){

      .contact {
         padding: 0px 10px;
      }

      .contact_container{
         width: 100%;
      }

      .contact_container .contact_text {
         width: 100%;
      }

      .contact_container iframe {
         width: 100%;
      }

   }




</style>