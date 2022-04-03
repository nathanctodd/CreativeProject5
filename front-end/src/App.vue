<template>
<div id="app">
  <div style="margin:10px;"></div>
    <h1 class="skislip">Ski Slip</h1>
    <nav>
      <router-link class="HomeLink" to="/admin">Browse</router-link> |
      <router-link class="OtherLink" to="/">Cart</router-link>
    </nav>
    
    <router-view/>
  </div>
  
</template>

<style>

.HomeLink {
  font-size: 30px;
}

.OtherLink {
  font-size: 30px;
}

.skislip {
  font-size: 90px;
  padding-top: 20px;
  margin: 10px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  margin-bottom: 20px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #22c67d;
  font-size: 37px;
}
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #5BDEFF;
  color: #1C454F;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
