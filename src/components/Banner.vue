<template>
    <!-- BANNER -->
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
    <!-- BANNER END -->
</template>

<script>
export default {
    name: 'Banner'
}
</script>

<style scoped>

    #main-banner {
        background-image: url('/public/img/burger.jpg');
        background-position: 0 720px;
        background-size: cover;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1 {
        color: #FFF;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
    

</style>
