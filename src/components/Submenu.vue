<template>
<nav class="container">
    <a href="#home">Home</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
  
</template>
<script>
export default {
    
}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
  font-family: 'Quicksand', sans-serif;
  color: #555;
}

.container {
  padding-left: 15%;
  padding-right: 15%;
  margin: auto;
}


nav {
  height: 70px;
  line-height: 80px;
text-align: center;
  
  width: 100%;
  z-index: 999;
  background: #fff;

  box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.2);
  
}

nav a {
  display: inline-block;
  text-decoration: none;
  margin-right: 45px;
  color: #555;
  font-size: 1em;
  font-weight: 900;
  float: left;
}
nav :hover {
  border-bottom: 1px solid #6c1cff;
 border-bottom-color: #6c1cff;
  
}

@media (max-width: 40rem) {

.container {
   
 
  margin: auto;
}

nav {
  
  width: 100%;
  background: #fff;
 box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.2);
  
}

nav a {
  
  text-decoration: none;
  color: #555;
  font-size: 10px;
  font-weight: 900;
   margin: auto;
 
  padding: 0 5px;
}
 
  }





</style>