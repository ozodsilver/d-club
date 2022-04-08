<template>

    <div id="header">
        <nav>
<div class="left">
<h2 style="color:blue">DASTURCHILAR</h2>  <h2 style="color:orange; margin-left:10px">KLUBI</h2>
</div>


<div class="right">

</div>
        </nav>
    </div>

</template>

<script>
export default {
    name: 'DClubHeader',

    data() {
        return {
            
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style lang="scss" scoped>
#header{
width: 100%;
height: 100vh;
background-image: url('../assets/fon.png');
background-size: 85% 90%;
background-position: 150% 0px;
background-repeat: no-repeat;
nav{
    width: 100%;
    height: 18%;
    border: solid;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .left{
        width: 30%;
        height: 100%;
        border: solid red;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    }

    .right{
        width: 55%;
        height: 100%;
        border: solid red;
    }
}
}
</style>