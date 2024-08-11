<template>
    <div>
      <a href="/"><img src="https://placehold.co/1000x150"/></a>
      <nav>
        <ul>
          <li><NuxtLink to="/music">Music</NuxtLink></li>
          <li><NuxtLink to="/games">Games</NuxtLink></li>
          <li><NuxtLink to="/dev">Web&nbsp;Dev</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/resume">Resume</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </nav>
    </div>
</template>

<style>
ul {
    display: flex;
    list-style-type: none;
    width: 100%;
    padding: 0;
    margin: 0;
}

li {
    display: inline;
    padding: 20px;
    width: 100%;
    text-align: center;
    background-color: lightblue;
}

a {
    text-decoration: none;
}
</style>