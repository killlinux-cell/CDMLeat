<template>
    <nav-view></nav-view>
    <hero-view></hero-view>
    <card-view></card-view>
    <service-view></service-view>
    <grid-view></grid-view>
    <news-view></news-view>
    <footer-view></footer-view>
</template>

<script>

import NavView from './components/NavView.vue';
import HeroView from './components/HeroView.vue';
import CardView from './components/CardView.vue';
import ServiceView from './components/ServiceView.vue';
import GridView from './components/GridView.vue';
import NewsView from './components/NewsView.vue';
import FooterView from './components/FooterView.vue';

export default{
    components:{
        NavView,
        HeroView,
        CardView,
        ServiceView,
        GridView,
        NewsView,
        FooterView,
    }
}
</script>