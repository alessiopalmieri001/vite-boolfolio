<script>


import HeaderComponet from './components/HeaderComponet.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default{
    data() {
        return {
            message: 'ciao bro'
        }
    },

    components: {

        HeaderComponet,
        MainComponent,
        FooterComponent,
    }
};

</script>

<template>

    <HeaderComponet/>

    <MainComponent/>

    <FooterComponent/>

</template>

<style scoped>
</style>