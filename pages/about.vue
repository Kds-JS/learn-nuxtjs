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

            <a href="/about">Normal link -- about page</a>
        </nav>
    </header>

    <h2>About</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Obcaecati
      commodi ex laudantium beatae, quaerat ut, repudiandae, similique quos nam
      sapiente culpa doloremque neque. Dolores, suscipit reprehenderit
      consequuntur asperiores maiores tempora!
    </p>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Obcaecati
      commodi ex laudantium beatae, quaerat ut, repudiandae, similique quos nam
      sapiente culpa doloremque neque. Dolores, suscipit reprehenderit
      consequuntur asperiores maiores tempora!
    </p>
  </div>
</template>

<script setup>

</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}

p {
  margin: 20px 0;
}
</style>
