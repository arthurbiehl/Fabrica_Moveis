<template>
   
   <div class="about" id="about">
      <div class="about_container">
            <h1>SOBRE NOS</h1>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Neque, culpa, laborum at unde aliquid libero voluptate id quam nobis perferendis cum cupiditate architecto. Neque magnam voluptatem, quaerat, fugit a voluptates non quidem tenetur provident error aut aspernatur modi libero, architecto facilis? Consequuntur eveniet ipsa sit qui et laudantium inventore voluptatem.</p>
      </div>
      <div class="mission_container">
         <div class="mission_item">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-target-arrow" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M12 12m-1 0a1 1 0 1 0 2 0a1 1 0 1 0 -2 0" />
               <path d="M12 7a5 5 0 1 0 5 5" />
               <path d="M13 3.055a9 9 0 1 0 7.941 7.945" />
               <path d="M15 6v3h3l3 -3h-3v-3z" />
               <path d="M15 9l-3 3" />
               </svg>
               <h1>MISSAO</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, blanditiis! Magnam, hic voluptatum. </p>
         </div>
         <div class="mission_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-eye-filled" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M12 4c4.29 0 7.863 2.429 10.665 7.154l.22 .379l.045 .1l.03 .083l.014 .055l.014 .082l.011 .1v.11l-.014 .111a.992 .992 0 0 1 -.026 .11l-.039 .108l-.036 .075l-.016 .03c-2.764 4.836 -6.3 7.38 -10.555 7.499l-.313 .004c-4.396 0 -8.037 -2.549 -10.868 -7.504a1 1 0 0 1 0 -.992c2.831 -4.955 6.472 -7.504 10.868 -7.504zm0 5a3 3 0 1 0 0 6a3 3 0 0 0 0 -6z" stroke-width="0" fill="currentColor" />
               </svg>
               <h1>VISAO</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, blanditiis! Magnam, hic voluptatum. </p>
         </div>
         <div class="mission_item">
               <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-123" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
               <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
               <path d="M3 10l2 -2v8" />
               <path d="M9 8h3a1 1 0 0 1 1 1v2a1 1 0 0 1 -1 1h-2a1 1 0 0 0 -1 1v2a1 1 0 0 0 1 1h3" />
               <path d="M17 8h2.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1 -1.5 1.5h-1.5h1.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1 -1.5 1.5h-2.5" />
               </svg>
               <h1>VALORES</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, blanditiis! Magnam, hic voluptatum. </p>
         </div>
      </div>
</div>
   
</template>

<style scoped> 

   .about {
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-bottom: 100px;
   }

   .about_container {
      width: 1300px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
   }

   .mission_container {
      width: 1300px;
      display: flex;  
      justify-content: space-between;
      align-items: center;
   }

   .mission_item {
      width: 400px;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
   }

   /* responsivo */

   @media (max-width: 1320px) {

      .about_container {
         width: 900px;

      }

      .mission_container {
         width: 900px;
      }

      .mission_item {
         width: 250px;
      }

   }
   
   
   @media (max-width: 920px) {

      .about_container {
         width: 600px;

      }

      .mission_container {
         width: 600px;
         flex-direction: column;
         align-items: center;
      }

      .mission_item {
         width: 600px;
      }

   }

   @media (max-width: 620px) {

      .about {
         padding: 0px 10px;
         padding-top: 100px;
      }

      .about_container {
         width: 100%;

      }

      .mission_container {
         width: 100%;
      }

      .mission_item {
         width: 100%;
      }

   }

   



</style>