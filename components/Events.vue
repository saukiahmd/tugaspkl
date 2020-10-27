<template>
    <div>
        <h5 class="my-10 ml-20">events</h5>
        <div class="grid grid-cols-2 gap-4">
            <div>
                <img src="../assets/img/gambar.png" alt="background" class="w-4/4">
            </div>
            <div class="jadwal">
                <nav>
                <ul class="flex">
                    <li class="mx-auto topnav">
                        <a class="active text-gray-400 mr-10" href="#">THIS MONTH</a>
                        <a class="text-gray-400" href="#">UPCOMING</a>
                    </li>
                </ul>
                </nav>
                <div class="grid grid-cols-2 baris mb-3 mt-12">
                    <div class="mb-2">
                        <div>
                            <h1>ROCKINTERVIEW</h1>
                            <p>Episode teaser satu</p>
                        </div>
                    </div>
                    <div class="mb-2 mt-2">
                        <div>
                            <h2>SUN 18/07</h2>
                            <p>YouTube</p>
                        </div>
                    </div>
                </div>
                <div class="grid grid-cols-2 baris mb-3">
                    <div class="mb-2">
                        <div>
                            <h1>ROCK CONCERT</h1>
                            <p>Live Concert at GBK</p>
                        </div>
                    </div>
                    <div class="mb-2 mt-2">
                        <div>
                            <h2>SUN 18/07</h2>
                            <p>Gelora Bung Karno</p>
                        </div>
                    </div>
                </div>
                <div class="grid grid-cols-2 baris mb-3">
                    <div class="mb-2">
                        <div>
                            <h1>ROCK CONCERT</h1>
                            <p>Live Concert at GBK</p>
                        </div>
                    </div>
                    <div class="mb-2 mt-2">
                        <div>
                            <h2>SUN 18/07</h2>
                            <p>Gelora Bung Karno</p>
                        </div>
                    </div>
                </div>
                <div class="grid grid-cols-2 baris mb-3">
                    <div class="mb-2">
                        <div>
                            <h1>ROCK CONCERT</h1>
                            <p>Live Concert at GBK</p>
                        </div>
                    </div>
                    <div class="mb-2 mt-2">
                        <div>
                            <h2>SUN 18/07</h2>
                            <p>Gelora Bung Karno</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="baris1 grid grid-cols-2 ml-40">
            <h6 class="ml-10">Rock Concert
            <h4 class="mb-6">gelora bung karno</h4>
            <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, ullam iste? Sed ipsum iure quo nobis nostrum saepe, exercitationem optio. Perspiciatis reprehenderit vitae aliquam? Voluptate, neque. Nisi necessitatibus nemo blanditiis!</h3>
            </h6>
            
            
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
    h6 {
        font-family: "Playfair Display";
        font-style: normal;
        font-weight: bold;
        font-size: 72px;
        line-height: 96px;
    }
    h5 {
        font-family: "Playfair Display";
        font-style: normal;
        font-weight: bold;
        font-size: 36px;
        line-height: 48px;
    }
    h4 {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 36px;
        color: red;
    }
    h1 {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        line-height: 36px;
    }
    h2 {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 27px;
    }
    h3 {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 27px;
    }
    p {
        font-family: 'Poppins', sans-serif;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 18px;
    }
    .jadwal {
        background: grey;
        padding: 1rem;
    }
    .topnav a:hover {
        border-bottom: 3px solid red;
        color: black;
    }
    .topnav a.active {
        border-bottom: 3px solid red;
        color: black;
    }
    .baris {
        border-bottom: 1px solid black;
    }
    .baris1 {
        border-left: 16px solid red;
    }
</style>