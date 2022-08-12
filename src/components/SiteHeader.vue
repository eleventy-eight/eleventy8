<script setup></script>

<template>
    <header>
        <a
            href="/"
            title="Eleventy8 | Three men in their 40s talk about... stuff"
        >
            <img
                src="../assets/images/android-chrome-512x512.png"
                alt="Eleventy8 | Three men in their 40s talk about... stuff"
            />
        </a>
        <h1>
            Eleventy8
            <span>Three men in their 40s talk about... stuff </span>
        </h1>
        <p>
            Justin brings wry observations and points out continuity errors,
            Paul hosts and does the technical stuff, and Samir brings facts and
            trivia.
        </p>
    </header>
</template>

<style scoped>
header {
    text-align: center;
    margin: 1.5rem 0 0 0;
}
header a {
    display: inline-block;
}
header a img {
    width: 100px;
    border: 2px solid white;
    border-radius: 50%;
    box-shadow: 3px 3px 1px black;
}
header h1 span {
    display: block;
    font-size: 1rem;
    color: var(--brand-secondary);
    margin-top: 0.5rem;
}
header p {
    max-width: 540px;
    margin: 0 auto;
}
</style>
