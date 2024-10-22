<template>
  <div class="font-sans antialiased">
    <Header />
    <Intro />
    <Features />
    <Challenge />
    <SolutionOverview />
    <UseCases />
   <!-- <ClientFeedback /> -->
    <Team />
    <CallToAction />
    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue';
import Intro from './components/Intro.vue';
import Features from './components/Features.vue';
import Challenge from './components/Challenge.vue';
import SolutionOverview from './components/SolutionOverview.vue';
import UseCases from './components/UseCases.vue';
import ClientFeedback from './components/ClientFeedback.vue';
import Team from './components/Team.vue';
import CallToAction from './components/CallToAction.vue';
import Footer from './components/Footer.vue';
</script>

<style>
@import './assets/main.css';
</style>
