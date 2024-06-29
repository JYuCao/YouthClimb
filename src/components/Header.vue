<script setup lang="ts">

</script>

<template>
    <header class="unselectable">
        <div class="heading w">Youth Climb</div>
        <div class="sub-heading">Welcome to YouthClimb</div>
    </header>
</template>

<style scoped>
header {
    width: 100%;
    background-color: #333
}

header .heading {
    text-align: center;
    font-family: algerian;
    color: #fff;
    font-size: 5em;
    padding-top: 100px
}

header .sub-heading {
    margin-top: 10px;
    text-align: center;
    color: #fff;
    font-size: 1.5em;
    padding-bottom: 100px
}

@media (max-width: 1024px) {
    header {
        place-items: center;
        padding-right: calc(var(--section-gap) / 2);
        padding-bottom: 75px;
    }
    .sub-heading {
        display: none;
    }
    .heading {
        font-size: 4em !important;
    }
}
</style>