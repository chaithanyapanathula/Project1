<template>
<div>
    <header>
    <div class="container">
      <h1 class="logo"></h1>

      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Login</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Cart</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
</div>
  
</template>

<script>
export default {
    name:'HomePageDetails'

}
</script>

<style>
body {
	margin: 0;
	background: rgb(218, 215, 215);
	font-family: 'Work Sans', sans-serif;
	font-weight: 800;
}

.container {
	width: 80%;
	margin: 0px;
}

header {
  background:grey;
}

header::after {
  content: '';
  display: table;
  clear: both;
}

.logo {
  float: left;
  padding: 10px 0;
}

nav {
  float: right;
}

nav ul {

  margin: 0;
  padding: 0;
  list-style: none;
}

nav li {
  display: inline-block;
  margin-left: 70px;
  padding-top: 23px;

  position: relative;
}

nav a {
  color:white;
  text-decoration: none;
  text-transform: uppercase;
  font-size: 14px;
}

nav a:hover {
  color: #000;
}

nav a::before {
  content: '';
  display: block;
  height: 5px;
  background-color:white;
  position: absolute;
  top: 0;
  width: 0%;
  transition: all ease-in-out 250ms;
}

nav a:hover::before {
  width: 100%;
}


</style>