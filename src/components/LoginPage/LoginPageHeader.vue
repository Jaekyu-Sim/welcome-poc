<template>
    <div id="header-style">

        <div id= "header-img"></div>

        <div id="header-text">
            <strong>SK Hynix 입니다.</strong>
            <span>PoC 페이지 입니다.</span>
        </div>

    </div>
</template>
  
<script>
    export default {
        name: 'LoginPageHeader',
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
    h1{
        float: left;
    }
    strong{
        font-size: 36px;
        margin: 0 0px 20px 0;
        font-weight: normal;
        text-indent: -3px;
        color: #fe3c16;
    }
    span{
        display: block;
    }
    #header-img{
        position: relative;
        float: left;
        margin-left: 35px;
        margin-top: 15px;
        width: 102px;
        height: 53px;
        background: url("../../assets/images/login_ci.png") center center no-repeat;
    }
    #header-text{
        font-family: 'Courier New', Courier, monospace;
        font-size: 17px;
        position: absolute;
        top:160px;
        left:35px;
    }
    #header-style{
        display: flex;
        flex-direction: column;
        
    }
</style>