<template>
  <div class="about">
    <h1>This is an about page ajuda!{{title}}</h1>
  </div>
</template>
<script>
export default {
  name: 'About',
  data(){
    return{
      title: process.env.VUE_APP_TITLE
    }
  }
}
</script>

