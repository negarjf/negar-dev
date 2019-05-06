<template>
    <div class="main-wrapper">
        <n-loading v-if="false"/>
        <n-header />
        <n-sidebar />

        <div id="main-content">
            <slot></slot>
        </div>
    </div>
</template>

<script>
    import NSidebar from '@/components/Sidebar'
    import NHeader from '@/components/Header'
    import NLoading from '@/components/Loading'

    export default {
        name: "Default",

        components: {
            NSidebar,
            NHeader,
            NLoading,
        }
    }
</script>

<style scoped>

</style>
