<template>
  <router-view />
  <div id="nav">
    <router-link to="/">Home</router-link> 
    <!-- <router-link to="/about">About</router-link> -->
    <router-link to="/new-entry">+ Add Entry</router-link>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
@import url('https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&family=BenchNine:wght@300;400;700&family=Londrina+Outline&family=Megrim&family=Poiret+One&display=swap');
body {
  font-family: 'megrim';
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background: #F58255;
  background: -webkit-linear-gradient(top right, #F58255, #39ABB1);
  background: -moz-linear-gradient(top right, #F58255, #39ABB1);
  background: linear-gradient(to bottom left, #F58255, #39ABB1);
  text-align: center;
}
#nav {
  margin: 4rem 0;
  font-size: 1.25rem;
  display: flex;
  justify-content: space-around;
  text-align: center;
}
a {
  text-align: center;
  text-decoration: none;
  color: #000;
}
</style>
