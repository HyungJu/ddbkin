<template>
    <div>

            <video playsinline autoplay muted loop id="background-video">
                <source src="../assets/mixkit-underwater-pink-ink-shot-3843.mp4" type="video/mp4">
            </video>
            <div class="step1"   >

                <h1  data-aos="fade-up" data-aos-duration="3000"  style="margin-bottom: 0; text-align: end" v-bind:style="{opacity: opacity}">1.5K</h1>
                <h6  data-aos="fade-up" data-aos-duration="3000"  >Expected DAU (Daily Active Use)</h6>
            </div>

    </div>
</template>

<script>
    import 'intersection-observer' // for cross-browser support
    export default {
        name: 'Forth',
        props: {
        },
        components: {
        },
        methods: {
            stepEnterHandler ({element, index, direction}) {
                // handle the step-event as required here
                console.log(element, index, direction)
            }
        },
        computed() {
            return {
                oo: function () {
                    Math.round(this.StepProgress * 100);
                }
            }
        }
    }
</script>
<style src="vue-scrollama/dist/vue-scrollama.css"></style>
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
    #ggg{
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
        width: 50vw;
        height: 50vh;
        mix-blend-mode: darken;
        opacity: 0.8;
        z-index: 100;
    }

    div{
        width: 100vw;
        height: 100vh;

        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        font-size: 18px;
        background-color: black;

    }

    .step1{
        width: 960px;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }

    h1{
        color: white;
        font-size: 10em;
        font-weight: bold;
        font-family: 'GmarketSansBold',sans-serif;
    }
    h6{
        color:white;
        font-size: 1.3em;
        font-family: 'GmarketSansMedium',sans-serif;
    }
    #right{
        color: white;
    }
</style>
