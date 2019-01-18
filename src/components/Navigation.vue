<template>
    <nav>
      <div class="nav-wrapper">
        <div class="nav-title"><h1>Caturday</h1></div>

        <div class="nav">

          <label for="show-menu" class="show-menu">Menu</label>
          <input type="checkbox" id="show-menu" role="button">

          <div class="container" onclick="myFunction(this)">
            <div class="bar1"></div>
            <div class="bar2"></div>
            <div class="bar3"></div>
          </div>

          <ul id="menu" class="menu-list">
              <li>
                  <router-link to="/">Home</router-link>
              </li>
              <li>
                <router-link to="/new">New</router-link>
              </li>
              <li>
                  <router-link to="/about">About</router-link>
              </li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<style>
  @import "../assets/css/navigation.css";
</style>
