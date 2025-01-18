<template>
    <div class="p-2">
        <h1 @click.self="isToggled = !isToggled" class="text-xl font-medium">{{ title }}</h1>
        <div v-if="isToggled">
            <slot />
        </div>
    </div>
</template>

<script setup>
    defineProps(['title']);

    const isToggled = ref(true);
</script>