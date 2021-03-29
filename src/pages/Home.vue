<template>
    <main>
        <div class="text-top">Vídeos novos toda <b>quinta</b> às <b>20h</b></div>

        <a href="https://www.youtube.com/channel/UCPtOwBPlYOQTDaCUxUyGSSA" target="blank">
        <img src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg
" alt="inscreva-se" id="subscribe">
        
        </a>

        <div class="text-bottom">youtube.com/desenvtioficial</div>
    </main>
</template>

<script>
export default {
    setup() {
        
    },
}
</script>

<style scoped>

    main{
        background-color: var(--color-background-home);
        justify-content: center;
        align-items: center;
    }

    .text-top{
        color: var(--color-text-ligth);
        font-size: 22px;
        margin-bottom: 20px;

    }

    #subcribe{
        width: 340px;
    }
    
    .text-bottom{
        color: var(--color-text-light);
        font-size: 18px;
        margin-top: 20px;
    }

    @media (min-width:700px){
        #subscribe{
            width: 370px;
        }
    }

</style>