<template>
    <div>
        <h1>Product details</h1>
        <p>{{ product.title }}</p>
        <p>{{ product.price }}</p>
        <p>{{ product.id }}</p>
        
    </div>
</template>

<script setup>
    const {id} = useRoute().params;
    const uri = 'https://fakestoreapi.com/products/' + id;

    // fetch the product
    const {data: product} = await useFetch(uri);
    // const {data: product} = await useFetch(uri, {key: id});
    // console.log(product);

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>