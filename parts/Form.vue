<template>

  <form action="">

      <input type="text" placeholder="search for products">
      <img src="./assets/search.png" alt="search">

  </form>



</template>

<script>


export default {
  data:  function() {
    return {
     
    }
  }
}
</script>

<style scoped>
@media screen and (min-device-width: 1075px)  {

form{display: none;}

}

@media screen and (max-device-width: 1024px)  {

form{display: none;}

}

@media screen and (max-device-width: 480px)  {


    form{position: absolute;
        width: 80vw;
        height: 7.66vh;
        left: 10vw;
        top: 12.66vh;
        background: #FFFFFF;
        box-shadow: 0px 0px 100px rgba(0, 0, 0, 0.10);
        border-radius: 6px;
        display: block;
        z-index: 2;
                    
            
            }

    input{
        position: absolute;
        width: 100%;
        height:100%;
        text-align: center;
        outline: none;
        border: none;
        font-size: 30px;
        font-weight: 400;
        line-height: 14px;
        letter-spacing: 0.2em;
        color: rgba(92, 94, 94, 0.7);

        
    }

    img{
        position: absolute;
        width: 50px;
        height: 50px;
        left: 80px;
        top: 28.6%;
        transform: matrix(-1, 0, 0, 1, 0, 0);
        display: flex;
        align-self: center;
    }

     

}




</style>
