<template>
  <div>
    <header>
        <nav>
            <NuxtLink to="/">Nuxt Dojo</NuxtLink>
            <ul>
                <li> <NuxtLink to="/">Home</NuxtLink> </li>
                <li> <NuxtLink to="/about">About</NuxtLink> </li>
                <li> <NuxtLink to="/products">Products</NuxtLink> </li>
            </ul>
        </nav>
    </header>

    <div>
        <slot></slot>
    </div>

    <footer>
        <h3>Footer</h3>
        <p>Build par kds-js</p>
    </footer>
  </div>
</template>

<script setup>

</script>

<style scoped>
     .router-link-exact-active {
        color: #12b488;
    }
</style>
