<template>
  <div class="login_page">
    <div class="login_box">
        
    </div>
  </div>
</template>

<script>
export default {
name:'loginPage',
data(){
    return {

    }
}
}
</script>

<style scoped lang="less">
.login_page{
    position: relative;
    width: 100vw;
    height: 100vh;
    background-image: url('../../assets/loginbg.jpg');
    background-size: 100% 100%;
    background-repeat: no-repeat;
    background-position: center;
    .login_box{
        position:absolute;
        left:50%;
        top:50%;
        transform: translate(-50%,-50%);
        width: 400px;
        height: 250px;
        // background-color: #fff;
        background: rgba(255, 255, 255, .5);
	-webkit-backdrop-filter: blur(10px);
	backdrop-filter: blur(5px);

    }
}
</style>