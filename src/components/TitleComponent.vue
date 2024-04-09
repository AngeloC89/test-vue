<template>
    <div>
      <h1>{{ title }}</h1>
    </div>
  </template>
  
  <script>
  export default {
    name: 'TitleComponent',
    data() {
      return {
        title: 'Vite Hello World',
      };
    },
  };
  </script>
  
  <style scoped>
  h1 {
    font-size: 50px;
    color: green;
    text-align: center;
    text-shadow: 0 0 15px rgb(40, 72, 40);
  }
  </style>