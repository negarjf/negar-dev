<template>
    <div id="app">
        <default-layout>
            <router-view></router-view>
        </default-layout>
    </div>
</template>

<script>
    import DefaultLayout from '@/views/layout/Default'

    export default {
        name: "app",
        components: {
            DefaultLayout
        }
    }
</script>

<style lang="scss">

</style>
