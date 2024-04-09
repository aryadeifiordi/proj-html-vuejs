<template>
    <footer class="footer-container">
        <nav>
            <ul>
                <li v-for="item in menuItems" :key="item.label">
                    <a :href="item.link">{{ item.label }}</a>
                </li>
            </ul>
        </nav>
        <p>&copy; 2024 MyWebsite. All rights reserved.</p>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    props: {
        menuItems: {
            type: Array,
            required: true
        }
    }
};
</script>

<style scoped></style>