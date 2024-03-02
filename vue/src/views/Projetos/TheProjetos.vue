<template>
    <body class="bg-secondary">
        <header>
            <TheNavBar />

        </header>
        
        <main>
            <div class="container mt-5 mb-5">
                <div class="row gap-5 m-2 d-flex justify-content-center">
                    <TheCard />

                </div>
            </div>

        </main>

        <footer class="mt-5">
            <TheFooter />

        </footer>

    </body>
</template>

<script>
import TheNavBar from '@/components/layout/TheNavBar.vue';
import TheFooter from '@/components/layout/TheFooter.vue';
import TheCard from '@/components/common/TheCard.vue'

export default {
    name: 'TheProjetos',

    components: {
        TheNavBar,
        TheFooter,
        TheCard
    }
}
    
</script>

<style scoped>

</style>