<template>
  
  <div class="cover">
    <div class="cover_container">
      <h2>SUA CASA,<br> SUA CARA</h2>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nobis culpa blanditiis maxime aspernatur autem iste officiis! Fugiat aliquam nulla pariatur ipsa consectetur optio provident ab nobis saepe. Quisquam, distinctio ab!</p>
    </div>
  </div>

</template>

<style>

  .cover {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: url('../static/cover_bg.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    margin-bottom: 100px;
  }

  .cover_container {
    width: 1300px;
    display: flex;
    flex-direction: column;
    
  }
  .cover_container h2 {
    font-size: 70px;
    font-weight: 800;
    text-transform: uppercase;
    color: white;
  }

  .cover_container p {
    font-size: 20px;
    width: 600px;
    margin-top: 20px;
    color: rgb(224, 224, 224);
  }

  @media (max-width: 1320px) {
    .cover_container {
      width: 900px;
    }
  }

  @media (max-width: 920px) {
    .cover_container {
      width: 600px;
    }
  }

  @media (max-width: 620px) {

    .cover{
      padding: 0px 10px;
    }

    .cover_container {
      width: 100%;
    }

    .cover_container h2 {
      font-size: 40px;
    }

    .cover_container p {
      width: unset;
      font-size: 16px;
    }
  }

</style>