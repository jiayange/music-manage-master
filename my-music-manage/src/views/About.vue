<!--
 * @Description: 
 * @Version: 2.0
 * @Author: yange
 * @Date: 2019-09-03 21:07:13
 * @LastEditors: yange
 * @LastEditTime: 2019-09-03 21:19:43
 -->
<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
export default {
   created(){
    
    this.$api.user.login({username:'lixd67',password:'123456'}).then(res=>{
        console.log(res)
    })
  }
}
</script>
