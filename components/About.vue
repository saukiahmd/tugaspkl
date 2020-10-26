<template>
    <div class="background position-relative text-white">
            <div class="text">
                    <div class="text1"><h5>ROCKINTERVIEW</h5></div>
                    <div class="">JOHN ANGELZ</div>
                    <div class="grid grid-cols-3 gap-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facere, assumenda! Ducimus iure similique dolorum maiores porro, quam provident impedit facilis tempora vitae? Reprehenderit dolores praesentium ipsam, veniam aspernatur earum eum.</div>
            </div>
        <img src="../assets/img/Johnlennon.png" alt="gambar" class="position-absolute">
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .background {
        background-color: black;
        background-image: url(../assets/img/Roadmann.png);
        background-position: center;
        background-repeat: no-repeat;
    }
    .text {
        position: absolute;
        bottom: 8px;
        right: 16px;
        color: white;
        text-align: right;
        margin-left: auto;
    }
    h5 {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 18px;
        font-style: normal;
        font-weight: 600;
        line-height: 27px;
    }
</style>