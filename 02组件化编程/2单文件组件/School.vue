<template>
    <!-- 1. 组件的结构 -->
    <div class="demo">
        <h2>学校名称:{{schoolName}}</h2>
        <h2>学校地址:{{address}}</h2>
    </div>
</template>

<script>
    //2. 组件交互相关的代码
     export default{
            name:'School',
            data(){
                return {
                    schoolName:'scdx',
                    address:'眉山'
                }
            }
      }

</script>

<style>
    /* 3. 组件的样式 */
    .demo{
        background-color: black;
    }
</style>