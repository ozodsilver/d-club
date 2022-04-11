<template>
  <div id="header">
    <nav>
      <div class="left">
       <img src="../assets/logo.png" alt="" class="img img-fluid w-25">
  
      </div>

      <div class="right">
        <div class="link">
            <a href="">KURSLAR</a>
        </div>
        <div class="link">
<a href="">XODIMLAR</a>
        </div>

        <div class="link">
<a href="">MAXSULOTLAR</a>
        </div>

        <div class="link">
<a href="">BIZ KIMMIZ?</a>
        </div>
      </div>
    </nav>


<div class="container home">
  <div class="row">
    <div class="col-5 d-flex justify-content-center align-items-center home_height">
      <div>
<h1>Dasturchilar Klubining rasmiy web sayti</h1>
<p>
  Maqsadni to'g'ri qo'ying, va haraktni boshlang.
</p>
      </div>

    </div>

    <div class="col-7">

    </div>
  </div>
</div>




  </div>
</template>

<script>
export default {
  name: "DClubHeader",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped>
#header {
  width: 100%;
  height: 100vh;
  background-image: url("../assets/fon.png");
  background-size: 85% 90%;
  background-position: 150% 0px;
  background-repeat: no-repeat;
  background-color: #fafbfc;
  
  
  nav{
    width: 100%;
    height: 12%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    backdrop-filter: blur(11px) saturate(180%);
    -webkit-backdrop-filter: blur(11px) saturate(180%);
    background-color: rgba(35, 33, 39, 0.21);
clip-path: polygon(100% 0, 100% 60%, 96% 100%, 4% 100%, 0 60%, 0% 0%);
position: sticky;
top: 0;
   

    .left {
      width: 30%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Merienda2';
    }

    .right {
      width: 55%;
      height: 100%;
      display: flex;
      justify-content: space-evenly;
      align-items: center;
     
      .link{
          width: 20%;
          height: 70%;
          display: flex;
          justify-content: center;
          align-items: center;
          border-radius: 10px;
          transition-duration: 0.4s;
       
          &:hover{
            background: white;
          }
&:hover a{
  color:black;
}
          
          a{
              text-decoration: none;
              color:rgb(255, 255, 255);
              font-size: 1.1em;
              font-family: 'light';
          }
      }
    }
  }


  .home{
    h1{
      font-family: 'fred';
      color:rgb(67, 66, 80);
    }

    .home_height{
      height: 80vh; 
    }
  }
}



@font-face {
  font-family: "Merienda";
  src: local("Merienda"),
   url(../assets/shriftlar/RubikWetPaint-Regular.ttf) format("truetype");
}


@font-face {
  font-family: "Merienda2";
  src: local("Merienda2"),
   url(../assets/shriftlar/RubikMoonrocks-Regular.ttf) format("truetype");
}


@font-face {
  font-family: "fred";
  src: local("fred"),
   url(../assets/shriftlar/FredokaOne-Regular.ttf) format("truetype");
}



@font-face {
  font-family: "light";
  src: local("light"),
   url(../assets/shriftlar/Rajdhani-Light.ttf) format("truetype");
}
</style>