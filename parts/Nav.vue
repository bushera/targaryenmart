<template>
  <div class="nav">
     
      <svg id="hambg-btn" width="25" height="10" viewBox="0 0 25 10" fill="none" xmlns="http://www.w3.org/2000/svg" >
        <rect width="25" height="3" fill="#141415"/>
        <rect x="10" y="7" width="15" height="3" fill="#141415"/>
      </svg>

      <img src="./assets/cartCheck.png">
     
  </div>
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

.nav{display: none;}

}

@media screen and (max-device-width: 1024px)  {

.nav{display: none;}

}

@media screen and (max-device-width: 480px)  {
    .nav{display: block;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            padding: 0px;
            position: absolute;
            width: 85.3vw;
            height: 3.13vh;
            left: 9.72vw;
            top: 2.26vh;
            background: white;
            z-index: 2;
        
            
            
            }

     #hambg-btn{position: static;
                width: 55px;
                height: 30px;
                right: 0;
                top: 0;
                flex: none;
                order: 1;
                flex-grow: 0;
                
                
                }

    img{
        position: static;
        width: 45px;
        height: 45px;
        left: 0;
        top: 0;
        flex: none;
        order: 0;
        flex-grow: 0;
       
    }

}




</style>
