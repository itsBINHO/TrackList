<template>
  <div class="info">
      <h1 class="text-h3 font-weight-bold mt-11 ml-6 mb-10">{{ nome }}</h1>
      <h4 class="ml-7">With "Bad Guy", she became the first <br> 
        artist born in the 21st century and third <br>
        Gen Z artist <a href="#">MORE</a></h4>
      </div>
</template>
<script>
  export default {
    name: 'Info',
      data() {
        return {
          nome: 'Billie Eilish',
      }
    }
  }
</script>

<style>
  a {
    text-decoration: none;
    color: #6687FF;
  }

  h4 {
    color: rgb(152, 158, 163);
  }
</style>