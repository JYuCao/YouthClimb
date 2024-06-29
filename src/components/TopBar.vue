<script setup lang="ts">
import TopBarItem from './TopBarItem.vue'
</script>

<template>
    <nav class="topbar-warpper">
        <div class="topbar w clearfix">
            <ul class="service">
                <TopBarItem name="首页" link="" />
                <TopBarItem name="小说" link="novels/index.html" />
                <TopBarItem name="文章" link="pages/articles.html" />
                <TopBarItem name="弔图" link="diaotu/show.html" />
                <TopBarItem name="图片" link="photos/show.html" />
                <TopBarItem name="成员" link="members/show.html" />
            </ul>
        </div>
    </nav>
</template>

<style scoped>
.topbar-warpper {
    width: 100%;
    height: 60px;
    line-height: 60px;
    top: 0;
    left: 0;
    float: left
}
</style>
