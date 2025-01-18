<template>
    <div>
        <BuilderHeader />

        <main class="bg-primary h-screen relative">
            <slot />

            <Propertybar />
            <Toolbar />
        </main>
    </div>
</template>