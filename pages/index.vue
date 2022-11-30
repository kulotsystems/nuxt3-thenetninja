<template>
    <div>
        <header>
            <nav>
                <nuxt-link to="/">Nuxt Dojo</nuxt-link>
                <ul>
                    <li><nuxt-link to="/">Home</nuxt-link></li>
                    <li><nuxt-link to="/about">About</nuxt-link></li>
                    <li><nuxt-link to="/products">Products</nuxt-link></li>
                </ul>
            </nav>
        </header>

        <h2>Home</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam eius eum facere ipsa iste iusto laborum veniam vero voluptates voluptatibus?</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid animi cumque debitis earum, et minima natus neque perferendis repellendus voluptas.</p>
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
