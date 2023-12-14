<template>

  </template>
  
  <script>
  
  export default {
    name: 'App',
    components: {
    },
    methods: {
      scroll(id) {
        const el = document.getElementById(id);
        el.scrollIntoView({ behavior: "smooth" });
      }
    }
  }
  </script>
  
  <style>
  @import "@/style.css";
  </style>
  