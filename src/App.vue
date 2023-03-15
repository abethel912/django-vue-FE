<template>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
    <div id="wrapper">
      <nav class="navbar is-dark">
        <div class="navbar-brand">
          <router-link to="/" class="navbar-item"><strong>Amanda's Jackets</strong></router-link>
          <a class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbar-menu">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div class="navbar-menu" id="navbar-menu">
        <div class="navbar-end">
          <router-link to="/summer" class="navbar-item">Summer</router-link>
          <router-link to="/winter" class="navbar-item">Winter</router-link>

          <div class="navbar-item">
            <div class="buttons">
              <router-link to="/login" class="btn btn-light">Login</router-link>

              <router-link to="/cart" class="btn btn-success">
              <span class="icon"><i class="bi bi-cart"></i></span>
              <span>Cart</span>
            </router-link>
            </div>
          </div>
        </div> 
        </div>
      </nav>
        
      <section class="section">
        <router-view/>
      </section>

      <footer class="footer">
        <p class="text-center"> Made by:Amanda Bethel </p>
      </footer>
      
    </div>
    </template>
        


<style>
@import '../node_modules/bootstrap';

</style>
