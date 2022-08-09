<template>
  <div id="slide" class="relative max-w-full z-10">
    <div class="relative text-center">
      <img src="/slide1.jpg" alt="slide1" class="w-full" />
      <div class="absolute inset-0 flex items-center justify-center flex-col">
        <div class="shadow-lg rounded-md p-14 backdrop-blur-sm">
          <ul class="font-sans text-putih">
            <!-- <li v-show="date" class="text-sm">{{ date }}</li> -->
            <li v-show="time" class="text-5xl">{{ time }}</li>
            <li v-show="fulldatetime" class="text-sm">
              {{ fulldatetime }}
            </li>
          </ul>
          <h2 class="font-bold text-4xl font-sans text-putih">
            Everytime is A Coffee Time
          </h2>
        </div>
        <div
          class="border border-coter bg-coter shadow-lg rounded-md mt-14 py-4 px-6 cursor-pointer transition duration-500 ease-in-out hover:bg-opacity-0"
        >
          <a href="products" class="text-putih">OUR MENU</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LayerSlide',
  data: () => ({
    // date: '',
    time: '',
    fulldatetime: '',
  }),
  mounted() {
    // this.date = this.printDate()
    this.time = this.printTime()
    this.fulldatetime = this.printFullDate()
  },
  methods: {
    // printDate() {
    //   return new Date().toLocaleDateString()
    // },
    printTime() {
      return new Date().toLocaleTimeString()
    },
    printFullDate() {
      return new Date()
    },
  },
}
</script>
