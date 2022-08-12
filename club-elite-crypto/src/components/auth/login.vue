<template>
    <div>
        <form>
            <input type="text" placeholder="Usuario">
            <input type="password" placeholder="contraseña">
            <input type="submit" value="Acceso">
        </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    div, form{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    form{
        height: 20vh;
        justify-content: space-around;
    }
</style>