<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top" id="mainNav">
      about
    </nav>
    <nuxt/>
    <hr>
    <!-- Footer -->
    <footer>
      ...
    </footer>
  </div>
</template>

<script>
  export default {
  }
</script>

<style>
  a {
    color: #212529;
    transition: all 0.2s;
  }

  #mainNav {
    position: absolute;
    border-bottom: 1px solid #e9ecef;
    background-color: white;
    font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }

  footer {
    padding: 50px 0 65px;
    text-align: center;
  }
</style>