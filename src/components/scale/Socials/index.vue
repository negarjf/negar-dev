<template>
    <div class="socials">
        <a v-for="(social, index) in socials"
           :key="index"
           :href="social.link"
           class="social"
           target="_blank"
        >
            <i class="icon" :class="social.icon"></i>
        </a>
    </div>
</template>

<script>
    export default {
        name: 'Socials',

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
                    {
                        icon: "yi-codepen",
                        title: "Codepen",
                        link: "https://codepen.io/negarjf"
                    },
                ]
            }
        },
    };
</script>
