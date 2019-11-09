<template>
    <div class="login_dise">
        <div class="login_box">
            <!-- 头像区域 -->
            <div class="user">
                <img src="../assets/logo.png" alt="">
            </div>
            <!-- 登陆表单区 -->
            <el-form  label-width="0px" class="login_form">
                <!-- 用户名 -->
                <el-form-item >
                    <el-input prefix-icon="iconfont icon-user"></el-input>
                </el-form-item>
                <!-- 密码 -->
                <el-form-item >
                    <el-input prefix-icon="iconfont icon-3702mima"></el-input>
                </el-form-item>
                <!-- 按钮 -->
                <el-form-item class="btns">
                    <el-button type="primary" round>登录</el-button>   
                    <el-button type="info" round>注销</el-button> 
                </el-form-item>
            </el-form>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="less" scoped>
    .login_dise{
        position: relative;
        background-color: skyblue;
        height: 100%;
    }
    .login_form{
        position: absolute;
        bottom: 0;
        width: 100%;
        padding: 25px;
        box-sizing: border-box;
    }
    .login_box{
        width: 450px;
        height: 300px;
        background-color: #fff;
        border-radius: 10px;
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%,-50%);
        .user{
            overflow: hidden;
            width: 130px;
            height: 130px;
            background-color: #fff;
            border:1px solid #fff;
            padding: 10px;
            box-shadow: 0,0,10px,#ddd;
            border-radius: 50%;
            position: absolute;
                left: 50%;
                top: 0;
                transform: translate(-50%,-50%);
            img{
                width: 100%;
                height: 100%;
                background-color: #eee;
                border-radius: 50%;
                
            }
        }
    }
    .btns{
        text-align: right;
    }
</style>
