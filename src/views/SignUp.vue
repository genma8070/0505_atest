<script>
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
<div>
    <h1>SignUp</h1>
    </div>
    <nav>
        <RouterLink to="/sign-up/by-google">Google</RouterLink>
        <RouterLink to="/sign-up/by-facebook">FaceBook</RouterLink>
    </nav>
    <RouterView />
</template>
<style>

</style>