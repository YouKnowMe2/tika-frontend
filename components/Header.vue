<template>
<div>
  <div class="primary-bg">
    <div class="container mx-auto py-20">
      <div class="bg-white mb-20">
        <div class="flex items-center justify-center">
          <div class="min-w max">
            <!-- logo -->
            <h2 class="text-2xl font-bold text-black uppercase px-6">Tika  </h2>
          </div>
          <!-- Menu -->
          <div class="w-full">
            <ul class="flex justify-center">
              <li><nuxt-link class="menu-item" to="/">Home</nuxt-link></li>
              <li><nuxt-link class="menu-item" to="/">Verify</nuxt-link></li>
              <li><nuxt-link class="menu-item" to="/">Tika Card</nuxt-link></li>
              <li><nuxt-link class="menu-item" to="/">Registration</nuxt-link></li>
              <li><nuxt-link class="menu-item" to="/">FAQs</nuxt-link></li>
              <li><nuxt-link class="menu-item" to="/">Help</nuxt-link></li>
            </ul>
          </div>

          <!-- Registration -->
          <div class="min-w-max">
              <div class="px-6">
                <nuxt-link to="/" class="primary-btn">Register Now</nuxt-link>
              </div>
          </div>

        </div>
      </div>

      <!-- Heading Text -->
      <div class="flex items-center">
         <div class="w-full">
           <h1 class="hero-heading font-bold text-white uppercase leading-none mb-6">Vaccine</h1>
           <h2 class="text-7xl font-medium text-white mb-10">Registration</h2>
           <p class="text-white text-2xl "> Complete the Registration by verifying your national identity card and mobile number</p>
         </div>
        <!-- Home Image -->
        <div class="min-w-max">
          <img src="~/static/img/bro.png" alt="">
        </div>
      </div>

    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
