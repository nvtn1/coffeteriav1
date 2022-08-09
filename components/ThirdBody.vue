<template>
  <div
    id="triple"
    class="relative flex justify-center bg-orange-50 pb-24 pt-10"
  >
    <div class="absolute left-0 top-0 opacity-40">
      <img src="/opa2.png" alt="opa2" />
    </div>
    <div class="relative z-10 text-center">
      <h2 class="text-3xl font-serif font-medium">OUR SPECIAL OFFER FOR YOU</h2>
      <p class="pt-3 font-sans">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere iusto,
        quisquam ducimus blanditiis obcaecati laborum!
      </p>
      <div>
        <OfferSlide />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ThirdBody',
}
</script>

<style></style>
