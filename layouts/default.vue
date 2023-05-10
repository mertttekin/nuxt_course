<template>
    <header>
      <nav class="bg-purple-700 text-white">
        <ul class="navbar">
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
          <li><NuxtLink to="/profile">Profile</NuxtLink></li>
          <li><NuxtLink to="/modify">Modify</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <slot></slot>
  </template>
  
  <style>
      .navbar{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
        
  </style>