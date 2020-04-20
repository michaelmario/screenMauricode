<template>
  <div id="app">
    <div class="w3-bar w3-black w3-border" id="navigation">
  <a href="#" class="w3-bar-item w3-button">
 <img  src="https://firebasestorage.googleapis.com/v0/b/mauricodeacademy.appspot.com/o/images%2FTransLogo.png?alt=media&amp;token=4e62cd1f-5fb9-42f2-ad90-060a9a11a6a3" alt="logo"></a>
</div>
  <div class="w3-sidebar w3-bar-block" style="width:25%">
  <li  class="w3-bar-item w3-button"><router-link to="/">Home</router-link> </li>
  <li  class="w3-bar-item w3-button"> <router-link to="/about">About</router-link></li>
  <a href="#" class="w3-bar-item w3-button">Link 3</a>
</div>

<div style="margin-left:25%">
  <router-view/>
... page content ...
</div>
    </div>
</template>

<style lang="scss">
body{
  margin:0px;
  left:0;
  right:0px;
}
#navigation{
  height:80px;
  width:100%;
}
</style>
