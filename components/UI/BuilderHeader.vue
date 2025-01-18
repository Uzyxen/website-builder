<template>
    <header class="h-16 w-full bg-secondary">
        <div class="max-w-screen-2xl mx-auto flex justify-between items-center h-full text-primary">
            <button class="text-xl" @click="$router.back()">Back</button>

            <div>
                <h1>Untitled/</h1>
            </div>

            <div class="flex gap-8">
                <button>Run</button>
                <button>Save</button>
            </div>
        </div>
    </header>
</template>
