<template>
    <div>
        <article>
            <div  data-aos="fade-right" data-aos-duration="2000" id="left">
                <h1 style="margin-bottom: 0; text-align: end">IN-CLASS COMMUNITY</h1>
                <div style="background: white; width: 20vw; height: 1.8vh;margin-top: 0.6rem; margin-bottom: 0.6rem; z-index: 100" />
                <h3>학급 커뮤니티를 통해 교실 구성원간의 자유로운 소통을 지원합니다</h3>
            </div>
            <div data-aos="fade-left" data-aos-duration="2000"  id="right">
                <img src="../assets/lottie/animation_500_kegl8k43.gif" width="300">
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
        background-color: #5B28F5;
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
        align-items: flex-end;
    }

    article{
        width: 960px;
        display: flex;
        flex-direction: row-reverse;
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
        text-align: end;
    }

    #right{
        color: white;
    }
</style>
