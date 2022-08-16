<script setup>
import VideoPlayer from "../components/VideoPlayer.vue";
</script>

<template>
    <main>
        <VideoPlayer />
        <footer>
            <h3>Engage</h3>
            <ul>
                <li>
                    <a
                        href="https://www.facebook.com/Eleventy8-108409931517198"
                        title="Follow us on Facebook"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/facebook.svg"
                            alt="Follow us on Facebook"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://gettr.com/user/11ty8"
                        title="Follow us on GETTR"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/gettr.svg"
                            alt="Follow us on GETTR"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.instagram.com/eleventy_8/"
                        title="Follow us on Instagram"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/instagram.svg"
                            alt="Follow us on Instagram"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://truthsocial.com/@eleventy8"
                        title="Follow us on Truth Social"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/truth-social.svg"
                            alt="Follow us on Truth Social"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://twitter.com/Eleventy81"
                        title="Follow us on Twitter"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/twitter.svg"
                            alt="Follow us on Twitter"
                        />
                    </a>
                </li>
            </ul>
            <h3>Watch</h3>
            <ul>
                <li>
                    <a
                        href="https://odysee.com/@Eleventy8:5"
                        title="Watch on Odysee"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/odysee.svg"
                            alt="Watch on Odysee"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://rumble.com/c/Eleventy8"
                        title="Watch on Rumble"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/rumble.svg"
                            alt="Watch on Rumble"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.twitch.tv/eleventy_8"
                        title="Watch on Twitch"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/twitch.svg"
                            alt="Watch on Twitch"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://www.youtube.com/c/Eleventy8"
                        title="Subscribe on YouTube"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/youtube.svg"
                            alt="Subscribe on YouTube"
                        />
                    </a>
                </li>
            </ul>
            <h3>Listen</h3>
            <ul>
                <li>
                    <a
                        href="https://podcasts.apple.com/gb/podcast/eleventy8/id1572987138"
                        title="Listen on Apple Podcasts"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/apple-podcasts.svg"
                            alt="Listen on Apple Podcasts"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://open.spotify.com/show/0qyafuXnqprjWP5zs5wBKj?si=3bcdc0f5d8c347c9"
                        title="Listen on Spotify"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/spotify.svg"
                            alt="Listen on Spotify"
                        />
                    </a>
                </li>
                <li>
                    <a
                        href="https://podcasts.google.com/feed/aHR0cHM6Ly9hZG1pbjE2MTExLnBvZG9tYXRpYy5jb20vcnNzMi54bWw"
                        title="Listen on Google Podcasts"
                        rel="noopener noreferrer"
                        target="_blank"
                    >
                        <img
                            src="../assets/icons/google-podcasts.svg"
                            alt="Listen on Google Podcasts"
                        />
                    </a>
                </li>
            </ul>
        </footer>
    </main>
</template>

<style scoped>
main {
    max-width: 540px;
    margin: 2rem auto 4rem auto;
}
main footer {
    text-align: center;
}
main footer h3 {
    position: relative;
    display: inline-block;
    text-transform: uppercase;
    font-family: "Anton";
    font-style: italic;
    font-size: 1.3rem;
    letter-spacing: 1px;
    transform: rotate(-6deg);
    text-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
}
main footer h3:after {
    position: absolute;
    top: -8px;
    left: -35px;
    content: "";
    width: 150px;
    height: 50px;
    background-image: url("../assets/images/paint-slash.svg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    z-index: -1;
    transform: rotate(6deg);
}
main footer ul {
    list-style: none;
    padding: 0;
}
main footer ul li {
    display: inline-block;
    margin: 0 0.3rem;
}
main footer ul li a {
    display: block;
    color: white;
    text-decoration: none;
}
main footer ul li a img {
    width: 35px;
    height: 35px;
}
</style>
