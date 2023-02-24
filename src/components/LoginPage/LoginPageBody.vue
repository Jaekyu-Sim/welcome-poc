<template>
    <div id="body-style">
        <div id = "body-image">

        </div>
    </div>
</template>
  
<script>
  export default {
    name: 'LoginPageBody',
    props: {
      //msg: String
    },
    data() {
      return {
        //count: 0
      }
    }
  }
</script>

<style scoped>
    #body-style{
        width: 100%;
        
    }
    #body-image{
        position: absolute;
        width: 100%;
        min-width: 1280px;
        height: 280px;
        box-sizing: border-box;
        top: 40%;
        z-index: -2;
        background: url("../../assets/images/login_back2.png") center 119px no-repeat, url("../../assets/images/login_back1.png") 38% 0 no-repeat;
        border-bottom: 55px solid #8baeff;
    }
</style>
  