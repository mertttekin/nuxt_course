<template>
  <header>
    <nav>
      <ul class="navbar">
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
        <li><NuxtLink to="/blog">Blog</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<style>
    .navbar{
      display: flex;
      align-items: center;
      justify-content: space-between;
      list-style-type: none;}
</style>