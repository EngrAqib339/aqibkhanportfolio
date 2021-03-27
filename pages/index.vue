<template>

<body>
<div class="flex-container">
 </div>
<section class="text-gray-600 body-font">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
<h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-black-900 ">Cheers all, I'm Muhammad Aqib 👋 </h1>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
      <img class="object-cover object-center rounded" alt="hero" :src="require('assets/images/mypic.jpeg' )">
    </div>
    <div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Before you ignore
        <br class="hidden lg:inline-block">know more about me
      </h1>
      <p class="mb-8 leading-relaxed">A passionate Full Stack Software Developer 🚀 having an experience of
building Web and Mobile applications with JavaScript / Flutter /Python
Django and some other cool libraries and frameworks.</p>
      <div class="flex justify-center">
      <a href="https://drive.google.com/drive/u/1/folders/1wO2gDk1a48jIh1kZPuK7QMOWKrEMoosJ"> <button class="inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg">Resume</button></a>
      <nuxt-link class="menu-item" :to="{name: 'contact'}">
      <button class="ml-4 inline-flex text-white-700 bg-indigo-100 hover:bg-voilet-600 border-0 py-2 px-6 focus:outline-none rounded text-lg">Contact</button>
      </nuxt-link>
      </div>
    </div>
  </div>
</section>
</body>
</template>

<script>

export default {

    }
</script>
<style lang"css">
.heading{
    margin:3% 3% 0% 2%;
    padding: auto;
    display: flex;
    text-align: center;
}

</style>
