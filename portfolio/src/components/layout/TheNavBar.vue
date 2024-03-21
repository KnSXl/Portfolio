<template>
    <nav class="navbar navbar-dark navbar-expand-lg bg-dark p-2">
        <div class="container-fluid">
            
            <a class="navbar-brand nav-link link-light link-opacity-50-hover" href="/">KNS</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ms-auto gap-2">
                    <a class="nav-link link-light link-opacity-50-hover" href="/">Home</a>
                    <a class="nav-link link-light link-opacity-50-hover" href="/projetos">Projetos</a>
                    <a class="nav-link link-light link-opacity-50-hover" href="/sobre">Sobre</a>
                    <a class="nav-link link-light link-opacity-50-hover" href="/contato">Contato</a>
                </div>
            </div>

        </div>
    </nav>
</template>

<script>
    export default {
        name: 'TheNavBar',
        
    }
</script>