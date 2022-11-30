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

        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eos ex facilis natus necessitatibus numquam odio omnis qui quis sequi soluta.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias asperiores consequatur corporis iure nobis nulla odio quibusdam reiciendis similique voluptates!</p>
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
