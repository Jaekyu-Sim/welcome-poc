<template>
    <div id="footer-style">
        <p>
            PoC Test Page Footer 부분 입니다.
        </p>
    </div>
</template>
  
<script>
    export default {
        name: 'LoginPageFooter',
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
    #footer-style{
        width: 100%;
        background-color: bisque;
        position: absolute;
        height: 50px;
        box-sizing: border-box;
        top: 80%;
        z-index: -2;
    }
</style>