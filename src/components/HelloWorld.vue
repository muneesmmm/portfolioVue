<template>
  <container>
  <Banner/>
  <BottomNav/>
  <About/>
  <Education/>
  <Projects/>
  </container>
</template>


<script>
import Bottomnav from './Bottomnav/bottomnav.vue';
export default {
  components :{
       Banner : ()=> import('./Banner/Banner.vue'),
       BottomNav : ()=> import('./Bottomnav/bottomnav.vue'),
       Education : ()=> import('./education/edu.vue'),
       About : ()=> import('./About/About.vue'),
       Projects : ()=> import('./projects/projects.vue')
    },
  name: "HelloWorld",
  data: () => ({value:"recent"}),
};
</script>
