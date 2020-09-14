<template>
  <div id="app">
    <div id="nav">
        <router-link to="/menu">Menu</router-link>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dosis:wght@600&display=swap');

html{
  background-color: #d0d65c;
}

#app {
  font-family: 'Dosis', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

#nav {
  padding: 30px;
  text-align: center;
  background-color: lightblue; 
}

#nav a {
  margin: 30px;
  padding: 10px;
  background-color: white;
  border-style: outset;
  border-color: lightblue;
  font-weight: bold;
  color: #2c3e50;
}

#nav a:hover {
  background-color: lightcoral;
}

#nav a:active{
  border-style: inset;
}

#nav a.router-link-exact-active {
  background-color: lightcoral;
  border-style: inset;
  color: #42b983;
}
</style>
