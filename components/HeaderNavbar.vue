<template lang="html">
  <header class="inner-column header-nav">
  <span class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <nuxt-link :to="{name: 'index'}" class="logo">
     <img :src="require('assets/images/logo.png')"/>
    </nuxt-link>
        <span class="ml-3 text-xl">Muhammad Aqib</span>
      </a>
</span>
     <span class="menu">
     <nuxt-link class="menu-item inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg" :to="{name: 'contact'}">
        Contact Me
      </nuxt-link>
      <nuxt-link class="menu-item inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg" :to="{name: 'projects'}">
        Work Experience
      </nuxt-link>
      <nuxt-link class="menu-item inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg" :to="{name: 'certification'}">
        Certification
      </nuxt-link>
      </nuxt-link>
      <nuxt-link class="menu-item inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg" :to="{name: 'achievements'}">
        Achievements
      </nuxt-link>
      <nuxt-link class="menu-item inline-flex text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg" :to="{name: 'programming'}">
        Programming Skills
      </nuxt-link>
</span>
    </nav>
  </header>

</template>

<script>
export default {}
</script>

<style>
.logo {
    padding: $pad 0;
    width:50px;
    height:10px;
    margin: 12% 0% 0% 8%;
}
.header-nav {
    display: flex;
    justify-content: space-between;
}
.menu {
    display: inline-block;
margin:2% 3% 1% 0%;


}
.menu-item {

  border-radius:5px;



    &:last-child {

    }
}
</style>
