<template>
    <div>
        <p>product details for {{ id }}</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
            Facilis, quam quaerat. 
            Distinctio quae odit ex repellat, velit beatae a ducimus?
        </p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>

<style lang="scss" scoped>

</style>