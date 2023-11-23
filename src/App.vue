<script>
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue'
import AppNavigation from './components/AppNavigation.vue'
import AppTopFooter from './components/AppTopFooter.vue'
import AppBottomFooter from './components/AppBottomFooter.vue'

export default {
    components: {
        AppHeader,
        AppContent,
        AppNavigation,
        AppTopFooter,
        AppBottomFooter,
    }
}
</script>

<template>
    <AppHeader />
    <AppContent />
    <AppNavigation />
    <AppTopFooter />
    <AppBottomFooter />
</template>

<style lang="scss">
    @use "./style/general.scss";
</style>
