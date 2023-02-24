<template>
    <div id="page-layout">
        <LoginPageHeader></LoginPageHeader>
        <LoginPageBody></LoginPageBody>
        <LoginPageFooter></LoginPageFooter>
    </div>
</template>

<script>
    import LoginPageHeader from "../LoginPage/LoginPageHeader.vue";
    import LoginPageBody from "../LoginPage/LoginPageBody.vue";
    import LoginPageFooter from "../LoginPage/LoginPageFooter.vue";
    export default {
    name: 'LoginPage',
    props: {
        //msg: String
    },
    components:{
        LoginPageHeader,
        LoginPageBody,
        LoginPageFooter
    },
    data() {
        return {
        //count: 0
        }
    }
    }
</script>

<style scoped>
    #page-layout{
        display: flex;
        flex-flow: column;
    }
</style>
