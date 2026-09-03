<template>
    <div class="bg-gray-900 min-h-screen">
        <Header />
        <main class="pb-12">
            <NuxtLoadingIndicator />
            <NuxtPage />
        </main>
        <Footer />
    </div>
</template>

<script setup>
import Header from "~/components/Header/index.vue"
import Footer from "~/components/Footer/index.vue"

defineOptions({
    name: "DefaultLayouts",
})
</script>