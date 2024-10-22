<template>
  <footer class="bg-gradient-to-r from-[#194f82] via-[#56ace0] to-[#194f82] py-16 md:py-20 text-white text-center relative overflow-hidden">
    <div class="container mx-auto text-center px-4 md:px-8 relative z-10">
      <div class="w-full h-1 bg-white mb-8 md:mb-12"></div>

      <div class="flex flex-col items-center space-y-8 md:space-y-12">
        <h2 class="text-3xl md:text-4xl font-bold tracking-wider animate-slide-in">
          Fique Conectado com a Monitora Tech
        </h2>

        <div class="flex space-x-4 md:space-x-6 justify-center animate-slide-in delay-200">
          <a href="https://www.instagram.com/monitoratechofc/" target="_blank" class="bg-white p-3 md:p-4 rounded-full hover:bg-[#fbb040] transition-all duration-500 shadow-lg transform hover:scale-110">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 md:h-8 md:w-8 text-[#194f82] hover:text-white transition-colors duration-500" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 2.2c3.2 0 3.6 0 4.9.1 1.2.1 2 .3 2.7.6.7.3 1.3.8 1.9 1.4.6.6 1.1 1.2 1.4 1.9.3.7.5 1.5.6 2.7.1 1.3.1 1.7.1 4.9s0 3.6-.1 4.9c-.1 1.2-.3 2-.6 2.7-.3.7-.8 1.3-1.4 1.9-.6.6-1.2 1.1-1.9 1.4-.7.3-1.5.5-2.7.6-1.3.1-1.7.1-4.9.1s-3.6 0-4.9-.1c-1.2-.1-2-.3-2.7-.6-.7-.3-1.3-.8-1.9-1.4-.6-.6-1.1-1.2-1.4-1.9-.3-.7-.5-1.5-.6-2.7C2.2 15.6 2.2 15.2 2.2 12s0-3.6.1-4.9c.1-1.2.3-2 .6-2.7.3-.7.8-1.3 1.4-1.9.6-.6 1.2-1.1 1.9-1.4.7-.3 1.5-.5 2.7-.6 1.3-.1 1.7-.1 4.9-.1m0-2.2C8.6 0 8.1 0 6.8.1 5.5.2 4.4.5 3.4.9 2.4 1.3 1.5 2 0.9 2.6.3 3.2-.1 4.1 0 5c.1 1.3.1 1.8.1 5.1s0 3.8-.1 5.1c-.1.9.3 1.8.9 2.5.6.6 1.5 1.4 2.5 1.8 1 .4 2.1.7 3.4.8 1.3.1 1.8.1 5.1.1s3.8 0 5.1-.1c1.3-.1 2.4-.4 3.4-.8 1-.4 1.9-1.1 2.5-1.8.6-.6.9-1.5.9-2.5-.1-1.3-.1-1.8-.1-5.1s0-3.8.1-5.1c.1-.9-.3-1.8-.9-2.5-.6-.6-1.5-1.4-2.5-1.8C18.4.5 17.3.2 16 .1 14.7 0 14.2 0 12 0zM12 5.8a6.2 6.2 0 1 0 0 12.4 6.2 6.2 0 1 0 0-12.4zm0 10.3a4.1 4.1 0 1 1 0-8.2 4.1 4.1 0 1 1 0 8.2zm6.4-11.8a1.4 1.4 0 1 0 0 2.8 1.4 1.4 0 1 0 0-2.8z"/>
            </svg>
          </a>
        </div>

        <div class="text-base md:text-lg mt-6 md:mt-8 animate-slide-in delay-400">
          <p>&copy; 2024 Monitora Tech. Todos os direitos reservados.</p>
        </div>

        <div class="flex flex-wrap justify-center space-x-4 md:space-x-8 mt-6 md:mt-8 animate-slide-in delay-600">
          <a href="#" class="hover:underline transition-all duration-300">Termos de Serviço</a>
          <a href="#" class="hover:underline transition-all duration-300">Política de Privacidade</a>
          <a href="#" class="hover:underline transition-all duration-300">Contato</a>
        </div>
      </div>
    </div>
    <div class="absolute bottom-0 left-0 w-full h-16 md:h-20 bg-gradient-to-b from-transparent to-[#194f82] opacity-50"></div>
  </footer>
</template>

<style scoped>
@keyframes slide-in {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-slide-in {
  animation: slide-in 1.5s ease-out forwards;
}

.hover\:shadow-lg:hover {
  box-shadow: 0 25px 35px -10px rgba(0, 0, 0, 0.15);
}

.hover\:bg-[#fbb040]:hover {
                      background-color: #fbb040;
                    }
</style>
<script setup lang="ts">
</script>
