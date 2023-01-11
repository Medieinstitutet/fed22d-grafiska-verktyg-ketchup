<template>
    <div>
        <h2>ImagePlay.vue</h2>
        <pre>
            {{ imageData }}
        </pre>
        <button> </button>
        <img: src="''+images[]" alt="recepies[]alt" width="300" height="200" loading="lazy" />
        <button> </button>


    </div>
</template>

<script setup lang="ts">
const props = defineProps(['imageData']);
</script>

<style lang="sass" scoped>

</style>