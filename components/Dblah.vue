<template>

    
    <div class="main">
      <div class="header">
        <img class="header-img" src="./assets/Dheader-img.png" alt=" header img">
        <img class="prev" src="./assets/backBtn.png" alt="previous page button">
      </div>

      <form action="">
        <input type="text" placeholder="Search...">
        <img class="input-icon" src="./assets/searchIcon.png" alt="search icon">
      </form>

      <div class="sneakers">
        <div class="selct1" v-on:mouseover="hoverOn1" v-on:mouseleave="hoverOff1">
          <img class="slct-img1" src="./assets/Dsneaks1.png" alt="sneakers selection" >
          <div class="addtoCart" v-if="visible1" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>
        <div class="selct2" v-on:mouseover="hoverOn2" v-on:mouseleave="hoverOff2">
          <img class="slct-img2" src="./assets/Dsneaks2.png" alt="sneakers selection">
          <div class="addtoCart" v-if="visible2" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N75</span> </div>
          </div>
        </div>
        <div class="selct3" v-on:mouseover="hoverOn3" v-on:mouseleave="hoverOff3">
          <img class="slct-img3" src="./assets/Dsneaks3.png" alt="sneakers selection">
          <div class="addtoCart" v-if="visible3" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>

        <h1>sneakers</h1>
        <p class="p1">Loreem</p>
        <p class="p2">Loreem</p>
        <p class="p3">Loreem</p>

      </div>

      <div class="jackets">
        <div class="selct1" v-on:mouseover="hoverOn4" v-on:mouseleave="hoverOff4">
          <img class="slct-img1" src="./assets/Djacket1.png" alt="jackets selection">
          <div class="addtoCart" v-if="visible4" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>
        <div class="selct2" v-on:mouseover="hoverOn5" v-on:mouseleave="hoverOff5">
          <img class="slct-img2" src="./assets/Djacket2.png" alt="jackets selection">
           <div class="addtoCart" v-if="visible5" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>
        <div class="selct3" v-on:mouseover="hoverOn6" v-on:mouseleave="hoverOff6">
          <img class="slct-img3" src="./assets/Djacket3.png" alt="jackets selection">
           <div class="addtoCart" v-if="visible6" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N75</span> </div>
          </div>
        </div>

        <h1>jackets</h1>
        <p class="p1">Loreem</p>
        <p class="p2">Loreem</p>
        <p class="p3">Loreem</p>


      </div>

 
      <div class="hats">
        <div class="selct1" v-on:mouseover="hoverOn7" v-on:mouseleave="hoverOff7">
          <img class="slct-img1" src="./assets/Dhat1.png" alt="hats selection">
          <div class="addtoCart" v-if="visible7" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>
        <div class="selct2" v-on:mouseover="hoverOn8" v-on:mouseleave="hoverOff8">
          <img class="slct-img2" src="./assets/Dhat2.png" alt="hats selection">
          <div class="addtoCart" v-if="visible8" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N50</span> </div>
          </div>
        </div>
        <div class="selct3" v-on:mouseover="hoverOn9" v-on:mouseleave="hoverOff9">
          <img class="slct-img3" src="./assets/Dhat3.png" alt="hats selection">
          <div class="addtoCart" v-if="visible9" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N125</span> </div>
          </div>
        </div>

        <h1>hats</h1>
        <p class="p1">Loreem</p>
        <p class="p2">Loreem</p>
        <p class="p3">Loreem</p>


      </div>



      <div class="men">
        <div class="selct1" v-on:mouseover="hoverOn10" v-on:mouseleave="hoverOff10">
          <img class="slct-img1" src="./assets/Dmen1.png" alt="men selection">
          <div class="addtoCart" v-if="visible10" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N50</span> </div>
          </div>
        </div>
        <div class="selct2" v-on:mouseover="hoverOn11" v-on:mouseleave="hoverOff11">
          <img class="slct-img2" src="./assets/Dmen2.png" alt="men selection">
          <div class="addtoCart" v-if="visible11" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N75</span> </div>
          </div>
        </div>
        <div class="selct3" v-on:mouseover="hoverOn12" v-on:mouseleave="hoverOff12">
          <img class="slct-img3" src="./assets/Dmen3.png" alt="men selection">
          <div class="addtoCart" v-if="visible12" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>

        <h1>men</h1>
        <p class="p1">Loreem</p>
        <p class="p2">Loreem</p>
        <p class="p3">Loreem</p>


      </div>


      <div class="women">
        <div class="selct1" v-on:mouseover="hoverOn13" v-on:mouseleave="hoverOff13">
          <img class="slct-img1" src="./assets/Dwomen1.png" alt="women selection">
          <div class="addtoCart" v-if="visible13" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N50</span> </div>
          </div>
        </div>
        <div class="selct2" v-on:mouseover="hoverOn14" v-on:mouseleave="hoverOff14">
          <img class="slct-img2" src="./assets/Dwomen2.png" alt="women selection">
          <div class="addtoCart" v-if="visible14" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N25</span> </div>
          </div>
        </div>
        <div class="selct3" v-on:mouseover="hoverOn15" v-on:mouseleave="hoverOff15">
          <img class="slct-img3" src="./assets/Dwomen3.png" alt="women selection">
          <div class="addtoCart" v-if="visible15" > 
            <div class="text">add to cart <span style="color:#8FDDE5">N100</span> </div>
          </div>
        </div>

        <h1>women</h1>
        <p class="p1">Loreem</p>
        <p class="p2">Loreem</p>
        <p class="p3">Loreem</p>


      </div>

    <div class="footer">
      <h2>team targaryen</h2>
      <img class="footer-img" src="./assets/vueLogo.png" >
    </div>
      
    </div>
    
    
 
</template>

<script>


export default {
 

  components: {
  
  },

  data:  function() {
    return {
      
     visible1: false,
     visible2: false,
     visible3: false,
     visible4: false,
     visible5: false,
     visible6: false,
     visible7: false,
     visible8: false,
     visible9: false,
     visible10: false,
     visible11: false,
     visible12: false,
     visible13: false,
     visible14: false,
     visible15: false,
    
    }
  },


  methods: {
    hoverOn1: function(){
      this.visible1 = true
    },
    hoverOff1: function(){
      this.visible1 = false
    },


    hoverOn2: function(){
      this.visible2 = true
    },
    hoverOff2: function(){
      this.visible2 = false
    },


    hoverOn3: function(){
      this.visible3 = true
    },
    hoverOff3: function(){
      this.visible3 = false
    },


    hoverOn4: function(){
      this.visible4 = true
    },
    hoverOff4: function(){
      this.visible4 = false
    },


    hoverOn5: function(){
      this.visible5 = true
    },
    hoverOff5: function(){
      this.visible5 = false
    },


    hoverOn6: function(){
      this.visible6 = true
    },
    hoverOff6: function(){
      this.visible6 = false
    },


    hoverOn7: function(){
      this.visible7 = true
    },
    hoverOff7: function(){
      this.visible7 = false
    },


    hoverOn8: function(){
      this.visible8 = true
    },
    hoverOff8: function(){
      this.visible8 = false
    },


    hoverOn9: function(){
      this.visible9 = true
    },
    hoverOff9: function(){
      this.visible9 = false
    },


    hoverOn10: function(){
      this.visible10 = true
    },
    hoverOff10: function(){
      this.visible10 = false
    },


    hoverOn11: function(){
      this.visible11 = true
    },
    hoverOff11: function(){
      this.visible11 = false
    },


    hoverOn12: function(){
      this.visible12 = true
    },
    hoverOff12: function(){
      this.visible12 = false
    },



    hoverOn13: function(){
      this.visible13 = true
    },
    hoverOff13: function(){
      this.visible13 = false
    },


    hoverOn14: function(){
      this.visible14 = true
    },
    hoverOff14: function(){
      this.visible14 = false
    },


    hoverOn15: function(){
      this.visible15 = true
    },
    hoverOff15: function(){
      this.visible15 = false
    },
  }

  
}
</script>

<style scoped>




@media screen and (min-device-width: 1075px) {
  
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0;
    scroll-behavior: smooth;
  }

  
.main{display: block;
     width: 100%;
     height: 100%;
     top: 0%;
     left:0%;
     position: absolute;
    
}

.header{

  position: absolute;
  width: 100%;
  height: 625px;
  left: 0;
  top: 0;

  border-radius: 0px 0px 10px 10px;
}

.header-img{
  position: absolute;
  width:100%;
  height: 100%;
}

.prev{
  position:absolute;
  width:30px;
  height:30px;
  left:2%;
  top:3%;
  z-index:2;
}

form{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 0px;
  position: absolute;
  width: 83.75vw;
  height: 96px;
  left: 8.33vw;
  top: 110%;
  border: 6px solid #0392BF;
  box-sizing: border-box;
  border-radius: 415px;
}

input{
  position: absolute;
  width: 100%;
  height:100%;
  border-radius: 415px;
  outline: none;
  border: none;
  font-size: 40px;
  font-weight: bold;
  text-indent: 50px;
}

.input-icon{
  position:absolute;
  width:35px;
  height:35px;
  right:3%;
}




.sneakers{
  position: absolute;
  width:90%;
  left:5%;
  top: 145%;
  height: 585px;
  background: white;
}

.jackets{
  position: absolute;
  width:90%;
  left:5%;
  top: 245%;
  height: 585px;
  
}
.hats{
  position: absolute;
  width:90%;
  left:5%;
  top: 345%;
  height: 585px;
  
}

.men{
  position: absolute;
  width:90%;
  left:5%;
  top: 445%;
  height: 585px;
  
}

.women{
  position: absolute;
  width:90%;
  left:5%;
  top: 545%;
  height: 585px;
 
}


.selct1{
  position: absolute;
  left: 0%;
  width: 30%;
  right: 68.65%;
  top: 15.38%;
  bottom: 7.18%;
  background: black;
  filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
  backdrop-filter: blur(50px);
  border-radius: 10px;
}

.selct2{
  position: absolute;
  left: 35%;
  width: 30%;
  right: 68.65%;
  top: 15.38%;
  bottom: 7.18%;
  background: black;
  filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
  backdrop-filter: blur(50px);
  border-radius: 10px;
}

.selct3{
  position: absolute;
  left: 70%;
  width: 30%;
  right: 68.65%;
  top: 15.38%;
  bottom: 7.18%;
  background: black;
  filter: drop-shadow(20px 20px 100px rgba(17, 1, 23, 0.1));
  backdrop-filter: blur(50px);
  border-radius: 10px;
}

.slct-img1{
  position: absolute;
  width: 100%;
  height: 100%;
}

.slct-img2{
  position: absolute;
  width: 100%;
  height: 100%;
}

.slct-img3{
  position: absolute;
  width: 100%;
  height: 100%;
}

h1{
  position: absolute;
  left: 1%;
  top: 0%;
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 30px;
  line-height: 34px;
  letter-spacing: 0.1em;
  color: #000000;
  text-transform: uppercase;

}

.p1{
  position: absolute;
  left: 0%;
  bottom: 0%;
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 28px;
  letter-spacing: 0.2em;
  text-transform: capitalize;
  color: #000000;

}

.p2{
  position: absolute;
  left: 35%;
  bottom: 0%;
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 28px;
  letter-spacing: 0.2em;
  text-transform: capitalize;
  color: #000000;

}

.p3{
  position: absolute;
  left: 70%;
  bottom: 0%;
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 28px;
  letter-spacing: 0.2em;
  text-transform: capitalize;
  color: #000000;

}

.addtoCart{
 display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 10px;
  position: absolute;
  width: 50%;
  height: 12%;
  left: 25%;
  top: 83%;
  background: rgba(0, 0, 0, 0.8);
  border-radius: 5px;
  transition:all 2s ease;
}

.text{
  position: static;
font-family: Arial;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 28px;
letter-spacing: 0.2em;
color: #FFFFFF;
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;
}

.footer{
  position: absolute;
  width: 34.86vw;
  height: 20vw;
  left: 33.1vw;
  top: 680%;
  display: flex;
  align-items: center;
  justify-content:center;
}

h2{
  position: absolute;
  bottom:0;
  left:15%;
  top:60%;
  font-family: Arial;
  font-style: normal;
  font-weight: normal;
  font-size: 28px;
  line-height: 34px;
  letter-spacing: 0.5em;
  color: #000000;
  text-transform:uppercase;
  text-align:center;
}

.footer-img{
  position:absolute;
  width:100px;
  height:100px;
  top:0%;

}





}

@media screen and (max-device-width: 540px)  {

  .main{display: none;}

}

@media screen and (max-device-width: 480px) {

  .main{display: none;}

}



</style>
