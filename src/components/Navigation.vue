<template>
    <nav>
      <div class="nav-wrapper">
        <div class="nav-title"><h1>Caturday</h1></div>

        <div class="nav">
          <ul>
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
