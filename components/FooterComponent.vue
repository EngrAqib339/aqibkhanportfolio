<template lang="html">
  <footer class="footer-component">
    <div class="inner-column">
      <nav>
        <footer class="text-black-600 body-font" >
  <div class="container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-nowrap flex-wrap flex-col">
    <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <nuxt-link :to="{name: 'index'}" class="logo">
     <img :src="require('assets/images/logo.png')"/>
    </nuxt-link>
        <span class="ml-3 text-xl ">Muhammad Aqib</span>
      </a>
      <p class=" adjust mt-2 text-sm text-balck-500">Software Engineer,UET Mardan</p>
    </div>

      <span class="inner-column footer-nav">
<nav class="main" role="navigation" >
      <nuxt-link class="menu-items" :to="{name: 'contact'}">
        Contact Me
      </nuxt-link>
      <nuxt-link class="menu-items" :to="{name: 'projects'}">
        Work Experience
      </nuxt-link>
      <nuxt-link class="menu-items" :to="{name: 'certification'}">
        Certification
      </nuxt-link>
      </nuxt-link>
      <nuxt-link class="menu-items" :to="{name: 'achievements'}">
        Achievements
      </nuxt-link>
      <nuxt-link class="menu-items" :to="{name: 'programming'}">
        Programming Skills
      </nuxt-link>

    </nav>
      </span>

  </div>
  <div class="bg-black-100">
    <div class="p-2 w-full pt-8 mt-8 border-t border-gray-200 text-center">
      <span class="inline-flex">
            <a class="text-gray-500">
             <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" hover:text-purple-700 stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
           <a href="https://www.linkedin.com/in/muhammad-aqib-922456188"> <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path></a>
            <circle cx="4" cy="4" r="2" stroke="none"></circle>
          </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
              </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
            <a class="ml-4 text-gray-500">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
              </svg>
            </a>
          </span>
    </div>
  </div>
</footer>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style>
.logo {
    padding: $pad 0;
    width:25%;
    height:5%;
    margin-top:2%;
}
.footer-component {
    text-align: center;
}
.footer-nav {
    display: flex;
    justify-content: space-between;
}
.main {
    display: inline-block;
white-space: main-menu ;
margin-top:4.5%;
margin-left:5px ;


}
.menu-items {
display: inline-block;
border: 2px solid gray;
  border-radius: 25px;
hover: bg-blue-600;
    &:last-child {

    }
}
.adjust{
  margin-left:25%;
}
</style>
