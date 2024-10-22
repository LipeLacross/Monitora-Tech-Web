<template>
  <button
      v-if="isVisible"
      @click="scrollToTop"
      class="fixed bottom-8 right-8 bg-[#fbb040] text-[#194f82] p-4 rounded-full shadow-lg transition-all duration-300 hover:bg-[#56ace0] hover:text-white z-50 flex items-center justify-center"
  >
    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
      <path stroke-linecap="round" stroke-linejoin="round" d="M5 15l7-7 7 7" />
    </svg>
  </button>
</template>

<script>
export default {
  data() {
    return {
      isVisible: false,
    };
  },
  methods: {
    scrollToTop() {
      window.scrollTo({top: 0, behavior: 'smooth'});
    },
    handleScroll() {
      this.isVisible = window.scrollY > 200;
    },
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.handleScroll);
  },
};
</script>

<style scoped>
</style>
