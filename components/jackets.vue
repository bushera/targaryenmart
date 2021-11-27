<template>
  <div class="jackets-component">

      <div class="selct1" v-on:mouseover="onHover1" v-on:mouseleave="offHover1">
        <img  src="./assets/jacket1.png" alt="jackets selections" v-if="!hover1">
        <div class="overlay" v-if="hover1">
          <div class="info-box">
            <h1>Loreem</h1>
            <h2>jackets</h2>
            <p>N25</p>
            <div class="addtoCart-btn">add to cart</div>
          </div>
        </div>
        
      </div>
      <div class="selct2 " v-on:mouseover="onHover2" v-on:mouseleave="offHover2">
          <img src="./assets/jacket2.png" alt="jackets selections" v-if="!hover2">
          <div class="overlay" v-if="hover2">
            <div class="info-box">
              <h1>Loreem</h1>
              <h2>jackets</h2>
              <p>N75</p>
              <div class="addtoCart-btn">add to cart</div>
            </div>
        </div>
      </div>
      <div class="selct3" v-on:mouseover="onHover3" v-on:mouseleave="offHover3">
        <img src="./assets/jacket3.png" alt="jackets selections" v-if="!hover3">
        <div class="overlay" v-if="hover3">
           <div class="info-box">
              <h1>Loreem</h1>
              <h2>jackets</h2>
              <p>N25</p>
              <div class="addtoCart-btn">add to cart</div>
            </div>
        </div>
      </div>
      <div class="selct4" v-on:mouseover="onHover4" v-on:mouseleave="offHover4">
        <img src="./assets/jacket4.png" alt="jackets selections" v-if="!hover4">
        <div class="overlay" v-if="hover4">
           <div class="info-box">
              <h1>Loreem</h1>
              <h2>jackets</h2>
              <p>N75</p>
              <div class="addtoCart-btn">add to cart</div>
            </div>
        </div>
      </div>
    
  </div>
</template>

<script>


export default {
  
  data:  function() {
    return {

      hover1: false,
      hover2: false,
      hover3: false,
      hover4: false

     
    }

  },


  methods: {

    onHover1: function(){
      this.hover1 = true
      
    },

    offHover1: function(){
      this.hover1 = false
      
    },

     onHover2: function(){
      this.hover2 = true
      
    },

    offHover2: function(){
      this.hover2 = false
      
    },

    onHover3: function(){
      this.hover3 = true
      
    },

    offHover3: function(){
      this.hover3 = false
      
    },
    
    onHover4: function(){
      this.hover4 = true
      
    },

    offHover4: function(){
      this.hover4 = false
      
    }



    }
}
</script>

<style scoped>
@media screen and (min-device-width: 1075px)  {

.jackets-component{display: none;}

}

@media screen and (max-device-width: 1024px)  {

.jackets-component{display: none;}

}

@media screen and (max-device-width: 480px)  {

    .jackets-component{
      position: absolute;
      width: 80vw;
      height: 48.75vh;
      left: 10vw;
      top: 33.66vh;
      display: block;
      
     

    }

   

    
   
    .selct1{position: absolute;
            left: 0%;
            right: 53.56%;
            top: 0%;
            bottom: 51.92%;
            filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
            border-radius: 10px;  
    }

    .selct2{
      position: absolute;
      left: 53.56%;
      right: 0%;
      top: 0%;
      bottom: 51.92%;
      filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
      border-radius: 10px;
    }

    .selct3{
      position: absolute;
      left: 0%;
      right: 53.56%;
      top: 51.92%;
      bottom: 0%;
      filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
      border-radius: 10px;
    }

    .selct4{
      position: absolute;
      left: 53.56%;
      right: 0%;
      top: 51.92%;
      bottom: 0%;
      filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
      border-radius: 10px;
     
    }

    img{
      position: absolute;
      width: 38.18vw;
      height: 23.45vh;
     
      
    }

    .overlay{
      position: absolute;
      width: 38.18vw;
      height: 23.45vh;
      background: #141415;
      border-radius: 10px;
    }

    .info-box{position: absolute;
              width: 80%;
              height: 61.33%;
              left: 10%;
              top: 20%;
             
              
              }

    .info-box h1{
      position: absolute;
      left: 0%;
      top: 0%;
      font-family: Arial;
      font-style: normal;
      font-weight: normal;
      font-size: 33px;
      line-height: 14px;
      display: flex;
      align-items: center;
      text-align: right;
      letter-spacing: 0.2em;
      text-transform: capitalize;
      color: #EFFBFB;
    }

    .info-box h2{
      position: absolute;
      left: 0%;
      top: 46px;
      font-family: Arial;
      font-style: normal;
      font-weight: normal;
      font-size: 20px;
      line-height: 8px;
      display: flex;
      align-items: center;
      text-align: right;
      letter-spacing: 0.2em;
      text-transform: lowercase;
      color: #EFFBFB;

    }

    .info-box p{
      position: absolute;
      right: 0%;
      top: 0%;
      font-family: Arial;
      font-style: normal;
      font-weight: normal;
      font-size: 30px;
      line-height: 14px;
      display: flex;
      align-items: center;
      text-align: right;
      letter-spacing: 0.2em;
      text-transform: capitalize;
      color: #FFFFFF;
    }

    .info-box  .addtoCart-btn{
      position: absolute;
      width: 100%;
      height: 80px;
      bottom: 0%;
      text-align: center;
      font-family: Arial;
      font-style: normal;
      font-weight: normal;
      font-size: 24px;
      letter-spacing: 0.2em;
      text-transform: capitalize;
      color: #EFFBFB;
      background: #1F1F20;
      border-radius: 5px;
      display: flex;
      justify-content: center;
      align-items: center;

    }

}

</style>
