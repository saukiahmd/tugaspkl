<template>
    <div class="container--video">
        <video ref="video" autoplay muted loop id="myVideo" class="video">
            <source src="../assets/img/kasus.mp4" type="video/mp4">
        </video>
        <button id="btn-play" @click.prevent="toggle"><img src="~assets/img/play.png" alt="play" class=""></button>
    </div>
</template>
<script>
export default {
    computed: {
        video () {
            return this.$refs.video
        }
    },

    methods: {
        toggle (e)    {
            if (this.video.paused)
              return  this.video.play()

            this.video.pause()
        }
    }
}
</script>
<style scoped>
    .container--video {
        position: relative !important;
    }
    .video {
        margin-top: 2rem;
        right: 0;
        bottom: 0;
        min-width: 100%;
        min-height: 100%;
        z-index: 1;
    }
    #btn-play {
        position: absolute !important;
        top: 50%;
        left: 50%;
    }
    .content{
        margin-right: 1000px;
    }
</style>