<template>
    <div v-for="cards in bancoDeDados" :key="cards.idDoProjeto" class="card bg-dark col-sm-5 col-md-4 col-lg-3  ">
      <img :src="cards.imagemDoProjeto" class="card-img-top p-3" :alt="`Card ${cards.idDoProjeto}`">
      <div class="card-body">
        <h4 class="card-title text-center">{{ cards.tituloDoProjeto }}</h4>
        <p class="card-text">{{ cards.descricaoDoProjeto }}</p>
        <div class="text-center">
            <a :href="cards.linkDoProjeto" class="btn btn-light" target="_blank">Explorar</a>
        </div>
      </div>
    </div>

</template>

<script>
export default {
    name: 'TheCard',

    data() {
        return{
            bancoDeDados: [
                {
                    "idDoProjeto": 1,
                    "imagemDoProjeto": "../assets/images/IPHONESTORE.png",
                    "tituloDoProjeto": "iPhones Store",
                    "descricaoDoProjeto": "Meu primeiro serviço como desenvolvedor. O cliente queria uma loja para vender seus produtos. Não precisava ser algo complexo, mas mesmo assim, dei o meu melhor para atender ao propósito dele e proporcionar uma boa experiência para seus clientes. Feito com React Native, esse foi o resultado.",
                    "linkDoProjeto": "https://iphones-store-sandy.vercel.app/"

                },
                {
                    "idDoProjeto": 2,
                    "imagemDoProjeto": "../assets/images/APIS.png",
                    "tituloDoProjeto": "APIS-Project",
                    "descricaoDoProjeto": "Este projeto consiste em uma API para gerenciar livros, oferecendo funcionalidades como listagem, pesquisa, ordenação, estatísticas, adição, atualização e exclusão de registros. Utiliza um servidor Express.js, armazena dados em um arquivo JSON e proporciona uma interface eficiente para operações de CRUD em um sistema de gerenciamento de livros.",
                    "linkDoProjeto": "https://github.com/KnSXl/APIS-Project"

                },
                {
                    "idDoProjeto": 3,
                    "imagemDoProjeto": "../assets/images/BIBLIOTECA.png",
                    "tituloDoProjeto": "Biblioteca Digital",
                    "descricaoDoProjeto": "Biblioteca Virtual interativa desenvolvida com HTML, CSS, e JavaScript, usando Bootstrap para um layout responsivo. Os usuários podem pesquisar e visualizar livros a partir de um banco de dados JSON. Destaca-se pela facilidade de uso, design moderno e integração de tecnologias web.",
                    "linkDoProjeto": "https://github.com/KnSXl/Biblioteca-Digital"

                },
                {
                    "idDoProjeto": 4,
                    "imagemDoProjeto": "../assets/images/TELA DE LOGIN.png",
                    "tituloDoProjeto": "Login-Screen",
                    "descricaoDoProjeto": "Biblioteca Virtual interativa desenvolvida com HTML, CSS, e JavaScript, usando Bootstrap para um layout responsivo. Os usuários podem pesquisar e visualizar livros a partir de um banco de dados JSON. Destaca-se pela facilidade de uso, design moderno e integração de tecnologias web.",
                    "linkDoProjeto": "https://github.com/KnSXl/LOGIN-SCREEN"

                },
                {
                    "idDoProjeto": 5,
                    "imagemDoProjeto": "../assets/images/TIKTOK.png",
                    "tituloDoProjeto": "TikTok-Replic",
                    "descricaoDoProjeto": "Réplica do TikTok feita apenas com HTML e CSS, apenas para prática de conteúdo e estilização.",
                    "linkDoProjeto": "https://github.com/KnSXl/TIKTOK-REPLIC"

                },
                {
                    "idDoProjeto": 6,
                    "imagemDoProjeto": "../assets/images/JS.jpg",
                    "tituloDoProjeto": "Estudo JS",
                    "descricaoDoProjeto": "Toda a minha experiência estudando JavaScript abrange desde os conceitos mais básicos até os intermediários.",
                    "linkDoProjeto": "https://github.com/KnSXl/ESTUDO-JS-VIDEOS"

                },
            ]

        }
    }
}
    
</script>

<style scoped>
    img{
        border-radius: 25px;
    }

    h4 {
       font-weight: 600; 

    }

    .card{
        color: white;
    }
</style>