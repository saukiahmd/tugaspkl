<template>
    <div class="background position-relative text-white">
            <div class="text position-asbsolute grid lg:grid-cols-2 gap-20">
                    <div><img src="../assets/img/Johnlennon.png" alt="gambar"></div>
                    <div class="text-right my-auto mb-20 mr-20">
                        <h5>ROCKINTERVIEW</h5>
                        <h1>JOHN ANGELZ</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium officiis harum earum delectus quos quisquam atque repudiandae fugit optio odio qui, voluptatibus dolor ut sapiente? Ad obcaecati dolorum est dicta.</p>
                    </div>
            </div>
    </div>
</template>
<script>
export default {
   link: [
        {
          rel: 'stylesheet',
          href: 'https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap'
        }
      ]
}
</script>
<style scoped>
    .background {
        background-color: black;
        background-image: url(../assets/img/Roadmann.png);
        background-position: center;
        background-repeat: no-repeat;
    }
    .backgroundimage {
        z-index: 9;
    }
    .text {
        z-index: 9;
        bottom: 8px;
        right: 16px;
        color: white;
        text-align: right;
        margin-left: auto;
    }
    h5 {
        font-family: 'Poppins', sans-serif;
        font-size: 18px;
        font-style: normal;
        font-weight: 600;
        line-height: 27px;
    }
    h1 {
        font-family: "Playfair Display";
        font-size: 72px;
        font-style: normal;
        font-weight: 700;
        line-height: 95.98px;
        color: #ED1B24;
    }
    p {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 27px;
    }
</style>