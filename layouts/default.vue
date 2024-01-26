<template>
    <div class="default-layout">
        <TheHeader/>
        <main>
            <slot/>
            <img class="bg-decoration" src="/img/vision.png" alt="vision">
        </main>
    </div>
</template>

<script setup>
import TheHeader from '~/components/TheHeader/TheHeader.vue'
</script>

<style scoped lang="scss">

</style>
