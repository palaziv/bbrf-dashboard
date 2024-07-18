<template>
    <span v-html="content"></span>
  </template>
  
  <script>
  export default {
    props: {
      content: {
        type: String,
        required: true
      }
    }
  };
  </script>