<template>
    <div>
        <Info />

        <div id="skills-section" class="seprate-section">
            <!-- skills -->
            <Skills />

            <!-- projects -->
            <Projects />
        </div>
    </div>
</template>

<script setup>
import Info from "~/components/Home/Info/index.vue"
import Skills from "~/components/Home/Skills/index.vue"
import Projects from "~/components/Home/Projects/index.vue"

// const { data, pending, refresh } = useApiFetch('/v2/search/all', {
//     method: 'POST',
//     body: computed(() => ({
//         q: query.value,
//     })),
//     immediate: false,
// })
</script>