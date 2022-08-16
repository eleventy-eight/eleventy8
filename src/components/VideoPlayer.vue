<script setup></script>

<template>
    <div class="player-container">
        <h2>Latest Video</h2>
        <div class="player-embed">
            <iframe
                src="https://www.youtube-nocookie.com/embed?listType=playlist&list=UUMwhK00OKytB3cCPpHjPY9g"
                allowfullscreen
            >
            </iframe>
        </div>
    </div>
</template>

<style scoped>
.player-container {
    text-align: center;
}
.player-container h2 {
    position: relative;
    display: inline-block;
    text-transform: uppercase;
    font-family: "Anton";
    font-style: italic;
    letter-spacing: 1px;
    transform: rotate(-6deg);
    text-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}
.player-container h2:after {
    position: absolute;
    top: -12px;
    left: -20px;
    content: "";
    width: 180px;
    height: 60px;
    background-image: url("../assets/images/paint-slash.svg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    z-index: -1;
    transform: rotate(6deg);
}
.player-container .player-embed {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 */
    padding-top: 25px;
    height: 0;
    margin: 2rem 0;
}
.player-container .player-embed iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 2px solid rgba(255, 255, 255, 0.2);
}
</style>
