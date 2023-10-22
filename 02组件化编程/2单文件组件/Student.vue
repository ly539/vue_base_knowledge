<template>
    <!-- 1. 组件的结构 -->
    <div class="demo">
        <h2>学生名称:{{name}}</h2>
        <h2>年龄:{{age}}</h2>
    </div>
</template>

<script>
    //2. 组件交互相关的代码
     export default{
            name:'Student',
            data(){
                return {
                    name:'ly',
                    age:20
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