<template>
    <body class="bg-secondary">
        <header>
            <TheNavBar />

        </header>

        <main>
            <div class="container">
                <div class="row align-items-center justify-content-between">
                    <div class="col-md-6 p-3 mb-5">
                        <h2>Hello world!<br>
                            Eu sou o Kauã Nascimento da Silva<br>
                            Desenvolvedor front-end</h2>

                        <p class="p1">Desenvolvedor front-end iniciante</p>
                        <p class="p2">Estou todo dia praticando e estudando para melhorar minhas habilidades como
                            desenvolvedor.</p>
                    </div>

                    <div class="col-md-6 d-flex justify-content-center p-3">
                        <img src="../../../public/assets/images/retrato.jpg" alt="alto retrato">
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
    name: 'TheHome',

    components: {
        TheNavBar,
        TheFooter
    }
}
    
</script>

<style scoped>
main{
  width: 100%;
  height: auto;
  
}

.container{
  margin-top: 50px;

}

.container img{
  width: 400px;
  height: 400px;
  border-radius: 50%;

}

h2{
  color: black;
  font-size: 30px;
  font-weight: 600;

}

.p1{
  color: black;

}

.p2{
  margin: 0;
  color: white;

}

footer{
  margin-top: 150px;

}

@media (max-width: 576px) { 
    .container img {
        width: 250px;
        height: 250px;
    }
}

</style>

