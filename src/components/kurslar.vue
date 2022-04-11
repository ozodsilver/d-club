<template>
  <div id="kurslar">
    <div class="container">
         <h1>Kurslar</h1>
      <div class="menu">
         
        <div class="link" @click = 'makeActive("1", "Python")' :class = '{active:(activeId == 1)}'>
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link"  @click = 'makeActive("2", "Frontend")' :class = '{active:(activeId == 2)}'>
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (4).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (5).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>

        <div class="link">
          <img
            src="../assets/kurslar/pngegg (1).png"
            alt=""
            class="img img-fluid w-50"
          />
        </div>
      </div>
    </div>


<component :is="tanlanganComponent"></component>




  </div>
</template>

<script>
import Python from '../components/Kurslar/Python'
import Frontend from '../components/Kurslar/Frontend'
export default {
    components:{
Python,
Frontend
    },
  name: "DClubKurslar",

  data() {
    return {
        tanlanganComponent:'Python',
        activeId:0
    };
  },

  mounted() {},

  methods: {
      makeActive(id, tanlangan){
this.activeId = id;
this.tanlanganComponent = tanlangan

      }
  },
};
</script>

<style lang="scss" scoped>
#kurslar {
  width: 100%;
  height: 110vh;
  background-color: #fafbfc;
  .menu {
    width: 100%;
    height: 20vh;
  border-radius: 2px;
background: linear-gradient(145deg, #e1e2e3, #ffffff);
box-shadow:  39px 39px 66px #dadadb,
             -39px -39px 66px #ffffff;
    border-radius: 4px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;

    .link {
      width: 10vw;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      cursor: pointer;
      filter:blur(1px) grayscale(1);
      transition-duration: 0.1s;
    }
  }

  .active{
      border-bottom:3px solid blueviolet;
      filter:blur(0px) !important;
      border-radius: 10px;
  }
}
</style>