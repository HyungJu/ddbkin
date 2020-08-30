<template>
    <div>

        <video playsinline autoplay muted loop id="background-video">
            <source src="../assets/world.mp4" type="video/mp4">
        </video>

        <article>
            <h1 data-aos="fade-down" data-aos-duration="2000">동대부고인</h1>
            <h3 data-aos="fade-down" data-aos-duration="2000">교내 생활 편의를 위한 All-In-One 서비스</h3>
        </article>
    </div>
</template>

<script>
    export default {
        name: 'Main',
        props: {
        }
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

    div{
        object-fit: cover;
        position: relative;
        z-index: 0;
        min-width: 100vw;
        min-height: 100vh;

        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        flex-direction: column;
    }
    video{
        object-fit: cover;
        width: 100vw;
        height: 100vh;
    }

    article{
        position: absolute;
    }

    h1{
        color: white;
        font-size: 6rem;
        font-weight: bold;
        font-family: 'GmarketSansBold',sans-serif;
    }
    h3{
        color: white;
        font-size: 1.3rem;
        opacity: 0.5;
        margin-top: 1rem;
        font-family: 'GmarketSansBold',sans-serif;
    }
</style>
