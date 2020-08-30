<template>
    <div>
        <article>
            <div id="left" data-aos="fade-right" data-aos-duration="2000">
                <h1  style="margin-bottom: 0">EASY NOTICEMENT</h1>
                <div style="background: #5B28F5;  width: 20vw; height: 1.8vh;margin-top: 0.6rem; margin-bottom: 0.6rem; z-index: 100" />
                <h3>간편하게 알림을 전달할 수 있는 기능을 제공합니다</h3>
            </div>
            <div id="right" data-aos="fade-left" data-aos-duration="2000">
                <img src="../assets/lottie/animation_500_kegkosme.gif" width="300">
            </div>
        </article>
    </div>
</template>

<script>

    export default {
        name: 'Second',
        props: {
        },
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    @font-face {
        font-family: 'GmarketSansBold';
        src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansBold.woff') format('woff');
        font-weight: normal;
        font-style: normal;
    }

    @font-face {
        font-family: 'GmarketSansMedium';
        src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansMedium.woff') format('woff');
        font-weight: normal;
        font-style: normal;
    }

    div{
        background-color: #101010;
        width: 100vw;
        height: 100vh;

        display: flex;
        justify-content: center;
        align-items: center;

        font-size: 18px;
    }

    #left{
        max-width: 480px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
    }

    article{
        width: 960px;
        display: flex;
        flex-direction: row;
    }

    h1{
        color: white;
        font-size: 2em;
        font-weight: bold;
        font-family: 'GmarketSansBold',sans-serif;
    }
    h3{
        color: white;
        font-size: 1em;
        font-family: 'GmarketSansMedium',sans-serif;
        line-height: 150%;
    }

    #right{
        color: white;
    }
</style>
