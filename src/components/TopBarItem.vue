<script setup lang="ts">
defineProps<{
    name: string,
    link: string
}>()
</script>

<template>
    <li><a :href="`/${link}`">{{ name }}</a></li>
</template>

<style scoped>
li {
    float: left
}

li a {
    font-size: 14px;
    color: #a7a7a7;
    display: block;
    padding: 0 16px
}

li a:hover {
    color: #fff;
    transition: color 0.5s
}
</style>
