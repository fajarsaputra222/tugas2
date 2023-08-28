<template>
    <div class="container">
        <ul class="menu">
    <li><router-link to ="/">Home</router-link></li>
    <li><router-link to ="/about">about</router-link></li>
    <li><router-link to ="/contact">contact</router-link></li>
         </ul>
        <section class="content">
            <p>
                chill keep enjoyy
            </p>
        </section>
    </div>
</template>

</script>
<style scoped>
  .container {
    width: 100%;
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
