<script setup></script>

<template>
    <footer>
        <a
            href="/"
            title="Eleventy8 | Three men in their 40s talk about... stuff"
        >
            <img
                src="../assets/images/e8-logo.svg"
                alt="Eleventy8 | Three men in their 40s talk about... stuff"
            />
        </a>
        <p>
            Built by Paul of Eleventy8 using
            <a
                href="https://vuejs.org"
                rel="noopener noreferrer"
                target="_blank"
                >Vue.js</a
            >
        </p>
    </footer>
</template>

<style scoped>
footer {
    text-align: center;
}
footer img {
    width: 80px;
    margin-bottom: 0.5rem;
}
footer p {
    font-size: 0.8rem;
    margin: 0;
    color: var(--brand-secondary);
}
footer p a {
    color: var(--brand-secondary);
    text-decoration: none;
}
</style>
