<template>
  <header :class="['bg-gradient-to-b from-[#56ace0] to-[#194f82] p-4 shadow-lg text-white fixed w-full z-50 transition-all duration-500 transform', { 'translate-y-0': showHeader, '-translate-y-full': !showHeader }]">
    <nav class="container mx-auto flex flex-wrap justify-between items-center px-4 md:px-8">
      <div class="flex items-center space-x-4">
        <img
            src="/img/logo.png"
            alt="Monitora Tech Logo"
            class="h-12 md:h-16 w-auto transition-transform duration-300 hover:scale-110 animate-fade-in-down"
        />
      </div>

      <button @click="toggleMenu" class="md:hidden text-white focus:outline-none">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" class="w-8 h-8">
          <path v-if="!isMenuOpen" stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
          <path v-else stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>

      <ul :class="['flex flex-col md:flex-row items-center md:space-x-8 space-y-4 md:space-y-0', isMenuOpen ? 'block' : 'hidden', 'w-full md:w-auto mt-4 md:mt-0']">
        <li>
          <a href="#sobre" class="text-base md:text-lg font-semibold hover:text-[#fbb040] transition duration-300 hover:underline underline-offset-4 animate-slide-in-left">Sobre</a>
        </li>
        <li>
          <a href="https://wa.me/55989910562" target="_blank" rel="noopener noreferrer" class="bg-[#fbb040] text-[#194f82] py-2 px-4 md:px-6 rounded-full font-semibold transition duration-300 hover:bg-[#56ace0] hover:text-white shadow-md animate-slide-in-right">Entre em Contato</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
      lastScrollY: 0,
      showHeader: true,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    },
    handleScroll() {
      const currentScrollY = window.scrollY;
      this.showHeader = currentScrollY < this.lastScrollY || currentScrollY < 10;
      this.lastScrollY = currentScrollY;
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
ul {
  transition: all 0.3s ease-in-out;
}

@media (min-width: 768px) {
  ul {
    display: flex !important;
  }
}

@keyframes fade-in-down {
  0% {
    opacity: 0;
    transform: translateY(-20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slide-in-left {
  0% {
    opacity: 0;
    transform: translateX(-20px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes slide-in-right {
  0% {
    opacity: 0;
    transform: translateX(20px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.animate-fade-in-down {
  animation: fade-in-down 1s ease-out forwards;
}

.animate-slide-in-left {
  animation: slide-in-left 1s ease-out forwards;
}

.animate-slide-in-right {
  animation: slide-in-right 1s ease-out forwards;
}
</style>
