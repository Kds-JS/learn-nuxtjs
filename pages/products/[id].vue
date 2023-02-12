<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Repellendus similique sunt eum veritatis aut possimus autem, unde vitae sapiente explicabo consequatur doloremque dicta eos, temporibus eveniet commodi error expedita dolores.</p>
    </div>
</template>

<script setup>
    const {id} = useRoute().params;

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>