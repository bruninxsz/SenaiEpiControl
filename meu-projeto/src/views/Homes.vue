<template class="scroll-smooth">

    <!--Montando o Header-->
    <div id="Header" class="flex justify-between px-6 py-6 shadow-md ">
        <img src="../assets/logo.png" class="w-40 rounded-md hover:scale-105">     <!--LOGO-->

        <router-link to='#Sobre'>
            <div class="px-2 py-4 text-black hover:text-red-600 hover:scale-[1.02]">Sobre</div>       <!--SOBRE-->
        </router-link> 

        <router-link to='#Contato'>
            <div class="px-2 py-4 text-black hover:text-red-600 hover:scale-[1.02]">Contato</div>     <!--CONTATO-->
        </router-link> 

        <router-link to='Login'>
            <button class="bg-red-700 px-12 py-4 text-white rounded-md hover:bg-red-800 hover:scale-[1.01]"> <!--BOTÃO LOGIN-->
                Login
            </button>
        </router-link>
    </div>

    <!-- Mudar quebra de linhas depois-->
    <br><br><br><br><br><br><br>

    <!--Montando o Corpo da Página-->
    <div class="body">
        <div class="flex justify-between px-80">
            <h1>Sistema de Controle de EPIs <br> para Instituições de Ensino</h1>
            <img src="../assets/Home/Dashboard-example.svg" class="w-[50%] rounded-xl"><br> <!--Imaem notebook-->
        </div>
        <div class="flex justify-between px-80">
            
        </div>

    </div>


</template>





<script>
import Header from "../components/Header.vue" 
import Menu from "../components/Menu.vue"

export default {
    name: 'Homes',
    components: {
        Header,
        Menu
    }
}
</script>
