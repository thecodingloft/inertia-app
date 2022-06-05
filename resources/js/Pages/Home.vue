<template>
    <h1>Hello {{ name }}</h1>
    <Nav></Nav>
</template>

<script>

import { Link } from '@inertiajs/inertia-vue3';
import Nav from '../Shared/Nav.vue'

export default{
    components: {
        Link,
        Nav
    }
};
</script>

<style>

</style>