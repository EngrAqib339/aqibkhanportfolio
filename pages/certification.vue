<template>
<html>
<div>
 <h1 class=" heading itle-font sm:text-4xl text-3xl mb-4 font-medium text-black-900 ">Certifications 🏆 </h1>
   <section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-col text-center w-full mb-20">
      <p class="lg:w-2/3 mx-auto leading-relaxed text-base">CERTIFICATIONS ,AWARD LETTERS AND SOME COOL STUFF THAT I HAVE DONE !</p>
    </div>
    <div class="flex flex-wrap -m-2">
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/wp.png')">
          <div class="flex-grow">
            <p class="text-gray-500">Word press</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/DMr.png')">
          <div class="flex-grow">

            <p class="text-gray-500">Digital Marketing</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('/workspace/nuxt-website/assets/images/content-writing.png')">
          <div class="flex-grow">
                        <p class="text-gray-500">Content Writing</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/CrW.png')">
          <div class="flex-grow">

            <p class="text-gray-500">Creative writing</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4":src="require('assets/images/WbApp.png')">
          <div class="flex-grow">

            <p class="text-gray-500">MCSD-Web Applications</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/SEO.png')">
          <div class="flex-grow">

            <p class="text-gray-500">SEO</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/ECm.png')">
          <div class="flex-grow">

            <p class="text-gray-500">E commerce Management</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/QB.png')">
          <div class="flex-grow">

            <p class="text-gray-500">Quick Books</p>
          </div>
        </div>
      </div>
      <div class="p-2 lg:w-1/3 md:w-1/2 w-full">
        <div class="h-full flex items-center border-gray-200 border p-4 rounded-lg">
          <img alt="team" class="w-16 h-16 bg-gray-100 object-cover object-center flex-shrink-0 rounded-full mr-4" :src="require('assets/images/MS365.png')">
          <div class="flex-grow">
            <p class="text-gray-500">Microsoft Dynamic 365</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
</div>
</html>
</template>

<script>
import LayerComponent from '~/components/LayerComponent.vue'

export default {
    head() {
        return {
            title: ' My Portfolio',
            description: 'Home page meta description',
            meta: [
                {
                    name: 'twitter:title',
                    content: 'Portfolio Website'
                },
                {
                    name: 'twitter:description',
                    content: 'Home page meta description'
                },
                {
                    name: 'twitter:image',
                    content: 'https://placehold.it/1200x600'
                },
                {
                    name: 'twitter:card',
                    content: 'summary_large_image'
                }
            ]
        }
    },
    components: {
        LayerComponent
    },
    computed: {
        projects() {
            return this.$store.state.projects.all.filter(project => project.isFeatured);
        }
    }
}
</script>

<style>
.heading{
    margin: 5% 3% 0% 10%;
    text-align:center;
}
/* Transitions using the page hook */
.page-enter-active,
.page-leave-active {
    transition: all 0.30s ease;
}
.page-enter,
.page-leave-active {
    opacity: 0;
    transform-origin: 50% 50%;
}
</style>
