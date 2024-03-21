<template>
    <body class="bg-secondary">
        <header>
            <TheNavBar />

        </header>

        <main>
    <h1 class="text-center mt-3">Quer entrar em contato?</h1>

    <div class="container mt-5">
        <div class="row">
            <div class="col-12 col-md-6 col-lg-3 mb-4">
                <div class="contact-card p-4 bg-light shadow-sm rounded text-center">
                    <h2 class="mb-3">Email <i class="bi bi-envelope"></i></h2>
                    <p class="mb-0">kauasilva2861@email.com</p>
                </div>
            </div>

            <div class="col-12 col-md-6 col-lg-3 mb-4">
                <div class="contact-card p-4 bg-light shadow-sm rounded text-center">
                    <h2 class="mb-3">Instagram <i class="bi bi-instagram"></i></h2>
                    <p class="mb-0"><a href="https://www.instagram.com/kns.zx/" target="_blank">@knszx</a></p>
                </div>
            </div>

            <div class="col-12 col-md-6 col-lg-3 mb-4">
                <div class="contact-card p-4 bg-light shadow-sm rounded text-center">
                    <h2 class="mb-3">GitHub <i class="bi bi-github"></i></h2>
                    <p class="mb-0"><a href="https://github.com/KnSXl" target="_blank">github.com/KnSXl</a></p>
                </div>
            </div>

            <div class="col-12 col-md-6 col-lg-3 mb-4">
                <div class="contact-card p-4 bg-light shadow-sm rounded text-center">
                    <h2 class="mb-3">LinkedIn <i class="bi bi-linkedin"></i></h2>
                    <p class="mb-0"><a href="https://www.linkedin.com/in/kau%C3%A3-nascimento-da-silva/" target="_blank">linkedin.com/in/kauã-nascimento-da-silva</a></p>
                </div>
            </div>
        </div>
    </div>
</main>


        
        <footer>
            <TheFooter />
        </footer>

    </body>

</template>

<script>
import TheNavBar from '@/components/layout/TheNavBar.vue';
import TheFooter from '@/components/layout/TheFooter.vue';

export default {
    name: 'TheContatos',

    components: {
        TheNavBar,
        TheFooter
    }
}
    
</script>

<style scoped>
h2, h1{
    font-weight: 600;
}

h1{
    color: white;
}
main{
    color: black;


}

footer{
    margin-top: 50%;

}

a{
    color: black;
}
</style>