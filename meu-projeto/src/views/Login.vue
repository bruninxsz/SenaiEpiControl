<template>
    <header>
        <Header />
    </header>
    <div class="title">
        <h1>pagina Login</h1>
    </div>
    <div class="menu">
        <Menu />
    </div>
</template>

<script>
import Menu from '../components/Menu.vue'
import Header from '../components/Header.vue'

export default {
    name: 'Activities',
    components: {
        Menu,
        Header
    }
}

</script>