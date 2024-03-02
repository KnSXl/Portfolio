<template>
  <component :is="currentView" />
</template>

<script setup>
import { ref, computed } from 'vue'
import TheHome from '../views/Home/TheHome.vue'
import TheSobre from '../views/Sobre/TheSobre.vue'
import TheContatos from '../views/Contatos/TheContatos.vue'
import TheProjetos from '../views/Projetos/TheProjetos.vue'
import NotFound from '../views/Erro/NotFound.vue'

const routes = {
  '/': TheHome,
  '/sobre': TheSobre,
  '/contato': TheContatos,
  '/projetos': TheProjetos
}

// Cria uma referência reativa para armazenar o caminho atual
const currentPath = ref(window.location.pathname)

// Adiciona um ouvinte de evento para atualizar o caminho quando a hash da URL muda
window.addEventListener('popstate', () => {
  currentPath.value = window.location.pathname
})

// Cria uma propriedade computada para determinar o componente a ser exibido com base no caminho
const currentView = computed(() => {
  return routes[currentPath.value] || NotFound
})

</script>

<script>
  export default {
    name: 'TheRoutes',

    components: {
      TheHome,
      TheSobre,
      TheContatos,
      TheProjetos
  }
    
}
</script>