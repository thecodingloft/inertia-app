<template>
    <nav>
        <ul>
            <li><Link href="/">Home</Link></li>
            <li><Link href="/Users">Users</Link></li>
            <li><Link href="/Settings">Settings</Link></li>
        </ul>
    </nav>
</template>

<script>

import { Link } from '@inertiajs/inertia-vue3';

export default{
    components: {
        Link
    }
};
</script>

<style>

</style>