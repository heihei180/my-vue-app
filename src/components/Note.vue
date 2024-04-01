<script setup>
import { ref } from 'vue'

defineProps({
    msg: String,
    // 这里添加上默认值，父组件就可以不传值 。
    default: "ddd"
})

const count = ref(0)
</script>


<template>
    这是一个笔记的组件、什么一些的note之类东西
</template>

<style scoped>
.read-the-docs {
    color: #888;
}
</style>
