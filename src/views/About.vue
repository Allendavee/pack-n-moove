<template>
    <Navbar />
</template>

<script>
import Navbar from "../components/Navbar.vue"
export default {
    name: 'About',
    mounted(){
        document.title = 'About | Packnmoove.com.ng'
    },

    components: {
      Navbar
    }    
}
</script>

<style scoped>

</style>