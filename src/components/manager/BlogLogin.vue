<template>
    <div>
        <blog-header></blog-header>
        <hr/>
        <div>
            用户名：<input type="text" v-model="loginInfo.username" placeholder="请输入用户姓名"/>
            <br/>
            密码：<input type="password" v-model="loginInfo.password" placeholder="请输入密码"/>
            <br/>
            登录验证情况：<textarea cols="30" rows="10" v-model="responseResult"></textarea>
        </div>
        <hr/>
        <blog-footer></blog-footer>
    </div>
</template>
<script>
import blogHeader from '@/component/common/BlogHeader.vue'
import blogFooter from '@/component/common/BlogFooter.vue'
export default {
    
}
</script>