<template>
  <div id="Main" class="min-h-screen bg-putih">
    <header
      class="h-[100px] p-[20px] w-full bg-cogel absolute z-20 bg-transparent"
    >
      <div class="flex flex-wrap h-full">
        <nav class="w-full flex justify-between relative items-center h-full">
          <img src="/logo.png" alt="logo" class="w-24 h-24" />
          <div class="w-full flex justify-between relative items-center h-full">
            <a href="home" class="font-sans font-bold text-3xl text-putih">
              Coffeteria
            </a>
          </div>
          <a
            href="home"
            class="text-putih font-sans font-medium rounded-lg px-1 py-2 m-4 cursor-pointer hover:text-yellow-500 transition delay-300 ease-in-out"
          >
            HOME
          </a>
          <a
            href="products"
            class="text-putih font-sans font-medium rounded-lg px-1 py-2 m-4 cursor-pointer hover:text-yellow-500 transition delay-300 ease-in-out"
          >
            PRODUCTS
          </a>
          <a
            href="#"
            class="text-putih font-sans font-medium rounded-lg px-1 py-2 m-4 cursor-pointer hover:text-yellow-500 transition delay-300 ease-in-out"
          >
            BLOG
          </a>
          <a
            href="about"
            class="text-putih font-sans font-medium rounded-lg px-1 py-2 m-4 cursor-pointer hover:text-yellow-500 transition delay-300 ease-in-out"
          >
            ABOUT
          </a>
          <a
            href="contact"
            class="text-putih font-sans font-medium rounded-lg px-1 py-2 m-4 cursor-pointer hover:text-yellow-500 transition delay-300 ease-in-out"
          >
            CONTACT
          </a>
        </nav>
      </div>
    </header>
    <div>
      <ScrollUp />
    </div>
    <div>
      <LayerSlide />
      <ContactOrder />
    </div>
    <div>
      <TheBottom />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
