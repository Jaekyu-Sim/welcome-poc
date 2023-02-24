<template>
    <div id="form-style">
        <div id = "form-image">

        </div>
    </div>
</template>
  
<script>
  export default {
    name: 'LoginPageForm',
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
    #form-style{
        width: 100%;
        
    }
    #form-image{
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
  