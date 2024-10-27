<!--
 * @Author: hukai05
 * @Date: 2024-10-27 11:24:17
 * @LastEditors: hk975 huwsmlm@163.com
 * @LastEditTime: 2024-10-27 11:59:13
 * @FilePath: \vuejs-challenges\questions\1-hello-word\App.vue
 * @Description: 2024-10-27
 *
-->
<script setup>
import { ref } from "vue"
const msg = ref("Hello World")
</script>

<template>
  <div>
    <h1> {{ msg }}</h1>
  </div>
</template>
