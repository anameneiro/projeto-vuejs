<template >
    <div id="main-banner">
        <h1>A perfeição entre dois pães.</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=PT+Serif:ital,wght@0,400;0,700;1,400;1,700&display=swap');

    #main-banner{
        background-image: url('/public/img/burguer.banner.jpg');
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        font-family: "PT Serif", serif;
        font-style: normal;
        color: #fff;
        text-align: center;
        font-size: 50px;
        background-color: #2222227c;
        padding: 20px 40px;
    }
</style>