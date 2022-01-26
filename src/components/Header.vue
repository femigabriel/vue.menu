<template>
    <header>
        <div class="header">
        <h4>What are you looking for?</h4>
      <div class="company-logo"></div>
      <nav class="navbar">
        <ul class="nav-items">
          <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Explore</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Listing</a></li>
          <li class="nav-item"><a href="#" class="nav-link">More</a></li>
        </ul>
      </nav>
      <div class="sign-in">
        <h4>Sign in or Register</h4>
      </div>
      <div class="menu-toggle">
        <button>Add a Listing</button>
      </div>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>
<style  >
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}



li {
  list-style: none;
}
a {
  text-decoration: none;
}

body {
font-family: 'Glacial Indifference Regular';
  font-size: 1rem;
}
.header {
  display: flex;
  background: #242429;
  padding: .5rem 1rem;
  height: 60px;
}

.nav-items {
  display: flex;
}
.nav-item {
  margin: 0 .5rem;

}
h4 {
  color: #fff;
  font-size: 6px;
  
 }
.nav-link {

  font-size: .8rem;
font-weight: 700;
  position: relative;
  color: plum;
}
.nav-link:hover {
  transition: all 0.25s;
  cursor: pointer;
   color: #f4f4f4;
   border-bottom: 4px solid blueviolet;
}

button {
  background: pink;
  color: blue;
  padding: 3px 2px;
  border-radius: 2px;
  font-size: 5px;
  margin: 7px 5px;
}

@media screen and (min-width: 480px) {
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #242429;
  padding: 1rem 2rem;
  height: 80px;
}
.company-logo {
  font-size: 2.5rem;
  color: plum;
}
.nav-items {
  display: flex;
 
}
.nav-item {
  margin: 0 2rem;

}
.navbar {
  left: 1em;
}
.sign-in h4 {
  color: #999;
  font-size: 14px;
}
.nav-link {
  font-size: 1em;
font-weight: 900;
  position: relative;
  color: #f4f4f4;
  cursor: pointer;
  transform-origin: bottom right;
  transition: all 0.25s;
}
.nav-link:hover {
  transition: all 0.25s;
  cursor: pointer;
   color: #f4f4f4;
   border-bottom: 4px solid blueviolet;
}

h4 {
 
  font-weight: 400;
  
  color: #fff;
  font-size: 15px;

}
button {
  background: #f4f4f4;
  color: blue;
  padding: 15px 30px;
  border-radius: 10px;
  font-size: 12px;
  font-weight: bolder;
  font-family: 'Glacial Indifference Regular';
}
}
</style>
