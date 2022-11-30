<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A deserunt dolorum eius facere facilis, inventore nesciunt obcaecati rem repellat saepe.</p>
    </div>
</template>


<script setup>
    const { id } = useRoute().params;
</script>


<style scoped>

</style>
