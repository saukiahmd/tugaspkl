<template>
<div>
    <div>
    <img src="../assets/img/johnangelz.png" alt="artist" class="artist mb-4">
    </div>
    <div class="layer">
        <div class="text ml-48 mt-32 grid grid-cols-6 text-white">
            <h5>Artist
                <h4 class="ml-10 mt-12">John 
                    Angelz</h4>
                <p class="ml-24 mt-6">read more</p>
            </h5>
        </div>
    </div>
</div>    
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .layer{
      position: relative;
      background-color: red;
      background-image: url(../assets/img/Vector.png);
      background-position: bottom right;
      background-repeat: no-repeat;
      height: 728px;
      z-index: 1;
      top: 7rem;
    }
    .artist{
        position: absolute;
        z-index: 2;
        right: 150px;
    }
    .text {
        position: absolute;
    }
    h5{
        font-family: "Playfair Display";
        font-style: normal;
        font-weight: bold;
        font-size: 36px;
        line-height: 48px;
    }
    h4{
        font-family: "Playfair Display";
        font-style: normal;
        font-weight: bold;
        font-size: 72px;
        line-height: 96px;
    }
    p{
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 27px;
    }
</style>