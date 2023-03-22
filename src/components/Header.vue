<script>
export default{
    data(){
        return {
            logo: 'https://www.sistema-ufficio.com/Resources/TST/SU/www.png'
        }
    }
}
</script>

<template>
    <header>
        <img :src="logo" alt="logo">
    </header>
</template>

<style scoped>
header{
    display: flex;
    justify-content: center;
    border-bottom: 5px solid black;
    align-items: center;
    padding: 10px;
}

img{
    width: 80px;
}
</style>
