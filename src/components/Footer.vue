<script setup lang="ts">

</script>

<template>
    <footer class="footer-warpper">
        <div class="footer">
            <span>2024 &copy; YouthClimb</span>
        </div>
    </footer>
</template>

<style scoped>
.footer-warpper {
    width: 100%;
    height: 100px;
    line-height: 100px;
    background-color: #000
}

.footer {
    color: #e3e4e5;
    font-size: 1.2rem;
    text-align: center
}

@media (max-width: 1024px) {
    .footer-warpper {
        height: 60px;
        line-height: 60px;
        font-size: 0.5em;
    }
}
</style>