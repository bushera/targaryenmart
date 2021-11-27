<template>
  <div class="footer">
      <div class="image-holder">
          <img src="./assets/logo.png" >
          <h1>{{h1}}</h1>
          <h2>{{h2}}</h2>
      </div>
  </div>
</template>

<script>


export default {
  data:  function() {
    return {

        h1: 'targaryen',
        h2: 'cohort 4.0'
     
    }
  }
}
</script>

<style scoped>
@media screen and (min-device-width: 1075px)  {

.footer{display: none;}


}

@media screen and (max-device-width: 1024px)  {

.footer{display: none;}


}

@media screen and (max-device-width: 480px)  {

    .footer{display: block;
            display: flex;
            justify-content: center;
            align-items: center;
            position: fixed;
            width: 100%;
            height: 12.97vh;
            left: 0;
            right: 0;
            bottom: 0;
            background: #141415;
            z-index: 2;
            
            
            }

      .image-holder{
        position: absolute;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 130px;
        height: 130px;
        left: 9.72vw;
        border-radius: 50%;
        background: #B3D4E0;
    }

    .image-holder img {
        position: absolute;
        width: 72px;
        height: 70px;
        
    }

    h1{
        position: absolute;
        left: 18vw;
        top: 8px;
        font-family: Arial;
        font-style: normal;
        font-weight: bold;
        font-size: 38px;
        line-height: 16px;
        letter-spacing: 0.2em;
        text-transform: uppercase;
        color: #B3D4E0;
    }

    h2{
        position: absolute;
        width: 300px;
        left: 18vw;
        top: 68px;
        font-family: Arial;
        font-style: normal;
        font-weight: normal;
        font-size: 30px;
        line-height: 1px;
        letter-spacing: 0.2em;
        text-transform: uppercase;
        color: #B3D4E0;
    }
}




</style>
