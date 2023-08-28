<template>
    <div class="container">
<ul class="menu">
    <li><router-link to ="/">Home</router-link></li>
    <li><router-link to ="/about">about</router-link></li>
    <li><router-link to ="/contact">contact</router-link></li>
</ul>
<h1>saya fajar dari praktisi politeknik bisnis digital </h1>
<ul class="contact">
    <li>facebook</li>
    <li>instagram</li>
    <li>tiktok</li>
</ul>
    </div>
</template>

</script>
<style scoped>
  .container {
    width: 75%;
    margin: 100x auto;
    text-align: center;
  }
  .menu {
    list-style: none;
    margin-bottom: 20x;
  }
  .menu li {
    display: inline;
  }
  .menu li a {
    padding: 20px;
    text-decoration: none;
    }
