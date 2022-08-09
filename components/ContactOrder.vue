<template>
  <div class="w-max-full px-10 pt-10 relative bg-orange-50">
    <h2 class="mb-7 font-medium font-serif text-2xl">Get In Touch</h2>
    <div class="">
      <textarea
        id="message"
        name="message"
        class="w-[700px]"
        cols="30"
        rows="9"
        placeholder="Enter Message"
      ></textarea>
    </div>
    <div class="flex flex-wrap">
      <div>
        <input
          id="name"
          type="text"
          class="mt-4 w-[350px]"
          name="name"
          placeholder="Enter Your Name"
        />
      </div>
      <div>
        <input
          id="email"
          type="text"
          class="mt-4 ml-10 w-[310px]"
          name="email"
          placeholder="Enter Your Email"
        />
      </div>
    </div>
    <div>
      <input
        id="subject"
        type="text"
        class="mt-4 w-[700px]"
        name="subject"
        placeholder="Enter Your Subject"
      />
    </div>
    <div>
      <button
        type="submit"
        class="mt-5 text-md text-putih border border-transparent bg-coter py-3 px-6 shadow-lg font-mono hover:text-coter hover:border-coter hover:bg-transparent transition duration-500 ease-in-out"
      >
        SEND
      </button>
    </div>
    <ProductAddress />
  </div>
</template>

<script>
export default {
  name: 'ContactOrder',
}
</script>

<style></style>
