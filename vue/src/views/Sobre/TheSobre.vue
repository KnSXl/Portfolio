<template>
    <body class="bg-secondary">
        <header>
            <TheNavBar />

        </header>

        <main>
           <div class="container mt-5 m">
                <h1 class="text-center mb-5">Sobre o Kauã Nascimento da Silva</h1>
                <p>
                    Bom, meu nome é Kauã Nascimento da Silva. Gosto muito da abreviação das letras do meu nome, que fica KNS. Interessei-me no mundo da programação há menos de um ano, começando com um curso de desenvolvimento web Front-end, que é onde atuo atualmente. Meu plano futuro é me tornar um desenvolvedor full-stack, dominando diversas linguagens, participando de vários projetos e tendo meu cantinho home office. Tudo isso para construir o melhor futuro possível fazendo algo que realmente gosto.
                </p>
                <p>
                    Possuo conhecimento em linguagens e tecnologias como HTML, CSS, JavaScript, React, Vue.js, Bootstrap e Node.js. Claro, em um nível inicial, mas estou sempre adquirindo conhecimento constante para aprimorar minhas habilidades.
                </p>
                <p>
                    As faculdades que me interessam fazer primeiro são ADS: Análise e Desenvolvimento de Sistemas e Ciência da Computação. Primeiro, quero ganhar experiência prática em ADS e, em seguida, aprofundar-me na teoria em Ciência da Computação.
                </p>
                <p>
                    Acredito que isso é um pouco sobre mim nessa área incrível, e conforme evoluí, sempre estarei compartilhando aqui no meu portfólio. Obrigado pela atenção em conhecer um pouco mais sobre mim. Estamos juntos, devs e pessoal!
                </p>
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
    name: 'TheSobre',

    components: {
        TheNavBar,
        TheFooter
    }
}
    
</script>

<style scoped>

main{
    color: white;
    font-size: 20px;
}

footer {
    margin-top: 200px;
}

h1{
    font-weight: 700;
    
}
</style>