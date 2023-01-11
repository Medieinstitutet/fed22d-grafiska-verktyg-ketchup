<script setup lang="ts">
import SiteHeader from './components/SiteHeader.vue';
import FooterSection from './components/FooterSection.vue';
import ArticleCard from './components/ArticleCard.vue';

import recepies from './components/array';
</script>

<template>
    <SiteHeader />
    <ArticleCard v-for="(recipe, index) in recepies" :key="index" :card-data="recipe" />
    <FooterSection />
</template>

<style scoped lang="scss">

</style>
