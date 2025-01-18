<template>
    <section class="pt-40">
        <div class="flex flex-col gap-8">
            <h1 class="text-6xl text-primary font-extrabold max-w-2xl leading-tight">Effortless Website Creation Made Simple</h1>
            <h2 class="text-lg text-primary max-w-2xl leading-loose">
                Unleash your creativity with our powerful website builder.
                No coding required - design stunning, responsive websites in minutes.
            </h2>

            <div class="mt-12 flex gap-5">
                <button class="bg-primary p-3 w-52 text-lg" @click="startBuilding()">
                    Start building
                </button>
                <button class="text-primary border-2 w-52 p-3">Get more info</button>
            </div>
        </div>
    </section>
</template>

<script setup>
    import { v4 as uuidv4 } from 'uuid';

    function startBuilding() {
        const router = useRouter();

        router.push({
            name: 'websites-website',
            params: {
                website: uuidv4(),
            },
        });
    }
</script>