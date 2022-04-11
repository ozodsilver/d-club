<template>
  <div id="reklama">
    
      <div class="center d-flex justify-content-center align-items-center">
        <h4>
          Dasturchilar Klubining telegram Kanali
          <button class="btn btn-primary">telegram</button>
        </h4>
    
    </div>

    <div class="center2">
<div class="box">
<lord-icon
    src="https://cdn.lordicon.com/cmrzxpzz.json"
    trigger="loop-on-hover"
    colors="primary:#b4b4b4,secondary:#30e8bd"
    style="width:100px; height:100px">
</lord-icon>

<h6>Markazda Ixtiyoriy vaqt kelib o'z ustida ishlash imkoniyati</h6>
</div>
<div class="box">
<lord-icon
    src="https://cdn.lordicon.com/cmrzxpzz.json"
    trigger="loop-on-hover"
    colors="primary:#b4b4b4,secondary:#30e8bd"
    style="width:100px; height:100px">
</lord-icon>

<h6>Markazda Ixtiyoriy vaqt kelib o'z ustida ishlash imkoniyati</h6>
</div>
<div class="box">
<lord-icon
    src="https://cdn.lordicon.com/cmrzxpzz.json"
    trigger="loop-on-hover"
    colors="primary:#b2a1b4,secondary:#30e8bd"
    style="width:100px; height:100px">
</lord-icon>

<h6>Markazda Ixtiyoriy vaqt kelib o'z ustida ishlash imkoniyati</h6>
</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DClubReklama",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped>
#reklama {
  width: 100%;
  height: 30vh;
  color: white;
  background-attachment: fixed;
  clip-path: polygon(96% 0, 100% 10%, 100% 100%, 0 100%, 0 10%, 4% 0);

  .center {
    width: 100%;
    height: 15vh;
    font-family: "fred";
    background: #171f2d;
    
    h4 {
      margin: 0;
    }
  }
  .center2{
      width: 100%;
      height: 15vh;
     background: #171f2d;
      display: flex;
      justify-content: space-evenly;
      align-items: center;

      .box{
        width: 30%;
        height: 100%;
      
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        font-family: 'fred';
      color: rgb(243, 235, 235);
      }
     
  }
}

@font-face {
  font-family: "fred";
  src: local("fred"),
    url(../assets/shriftlar/FredokaOne-Regular.ttf) format("truetype");
}
</style>