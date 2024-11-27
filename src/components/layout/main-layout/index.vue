<template>
    <div>
        <Header/>
        <MainLayout>
            <slot/>
        </MainLayout>
        <Footer/>
    </div>
</template>

<script setup>
import Header from '../header/index.vue';
import MainLayout from '../main/index.vue';
import Footer from '../footer/index.vue';
</script>

<style lang="scss" scoped>

</style>