<template>
    <div>
        <nav class="flex items-center justify-between flex-wrap p-6">
            <div class="flex items-center flex-shrink-0 text-white mr-6">
                <span class="font-semibold text-xl tracking-tight ml-10 text-red-600"><h1>ROADMANN</h1></span>
            </div>
            <div class="block lg:hidden">
                <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
                <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
                </button>
            </div>
            <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
                <div class="ml-auto topnav">
                    <a href="#responsive-header" class="active block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        ABOUT
                    </a>
                    <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        ARTIST
                    </a>
                    <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        EVENT
                    </a>
                    <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        MEDIA
                    </a>
                    <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        PARTNER
                    </a>
                    <a href="#responsive-header" class="block mt-4 lg:inline-block lg:mt-0 text-black mr-10">
                        SHOP
                    </a>
                </div>
            </div>
        </nav>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    h1 {
        font-family: "Playfair Display";
        font-size: 36px; 
        font-style: normal; 
        font-weight: bold; 
        line-height: 48px;
    }
    .block {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 18px;
        font-style: normal;
        font-weight: 600;
        line-height: 27px;
    }
    .topnav a:hover {
        border-bottom: 3px solid red;
    }
    .topnav a.active {
        border-bottom: 3px solid red;
    }
</style>