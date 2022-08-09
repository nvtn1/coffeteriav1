<template>
  <button
    :class="{
      'opacity-100': isScrolled,
    }"
    class="flex items-center justify-center bottom-11 right-9 fixed z-10 w-14 h-14 border border-transparent bg-coklat rounded-full shadow-xl"
    @click="Scrol"
  >
    <img src="/up.png" alt="up" class="w-5" />
  </button>
</template>

<script>
export default {
  name: 'ScrollUp',
  data() {
    return { isScrolled: false }
  },
  mounted() {
    window.addEventListener('scroll', this.onScrollHandler)
  },
  methods: {
    Scrol() {
      window.scroll({
        top: 0,
        behavior: 'smooth',
      })
    },

    onScrollHandler() {
      if (document.documentElement.scrollTop > 0) {
        this.isScrolled = true
      } else {
        this.isScrolled = false
      }
    },
  },
}
</script>
