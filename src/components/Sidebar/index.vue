<template>
    <div id="sidebar">
        <div class="logo">
            <img src="@/assets/logo.png" alt="">
        </div>

        <nav class="sidebar-nav">
            <ul class="menu">
                <li v-for="social in socials" :key="social.icon">
                    <a :href="social.link" target="_blank">
                        <i class="icon" :class="social.icon"></i>
                        {{ social.title }}
                    </a>
                </li>
            </ul>
        </nav>

        <div class="credit">
            <div>
                © Negar Jamalifard | 2019
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: "sidebar",

        data() {
            return {
                socials: [
                    {
                        icon: "yi-medium-color",
                        title: "Medium",
                        link: "https://medium.com/@negarjf"
                    },
                    {
                        icon: "yi-linkedin",
                        title: "Linkedin",
                        link: "https://www.linkedin.com/in/negarjamalifard/"
                    },
                    {
                        icon: "yi-youtube",
                        title: "Youtube",
                        link: "https://www.youtube.com/channel/UCbUgyn-Vzr1U12x4o_k2n2Q"
                    },
                    {
                        icon: "yi-github",
                        title: "Github",
                        link: "https://github.com/negarjf"
                    },
                    {
                        icon: "yi-twitter",
                        title: "Twitter",
                        link: "http://twitter.com/negarjamalifard"
                    },
                ]
            }
        },
    }
</script>

<style scoped>

</style>
