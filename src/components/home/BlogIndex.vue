<template>
    <div>
        <blog-header></blog-header>
        <hr/>
        <div>
            这是首页
        </div>
        <hr/>
        <blog-footer></blog-footer>
    </div>
</template>

<script>
 import blogHeader from '@/components/common/BlogFooter.vue'
 import blogFooter from '@/components/common/BlogHeader.vue'
export default {
   name: 'BlogIndex',
   components: {blogHeader,blogFooter}
}
</script>