<template>
  <section id="contato" class="bg-gradient-to-r from-[#194f82] via-[#56ace0] to-[#194f82] py-16 md:py-20 text-white text-center relative overflow-hidden">
    <div class="container mx-auto px-4 md:px-8 relative z-10">
      <h2 class="text-3xl md:text-5xl font-extrabold mb-8 md:mb-12 tracking-wider leading-tight animate-slide-in">
        Pronto para Automatizar seu Monitoramento Hídrico?
      </h2>
      <p class="text-base md:text-lg mb-6 md:mb-8 max-w-2xl md:max-w-3xl mx-auto">
        A Monitora Tech está aqui para transformar o seu controle hídrico com soluções inovadoras e de ponta. Entre em contato e veja como podemos ajudar a otimizar seus processos.
      </p>
      <a href="https://wa.me/55989910562" target="_blank" rel="noopener noreferrer">
        <button class="bg-[#fbb040] text-[#194f82] py-3 md:py-4 px-8 md:px-12 rounded-full font-bold shadow-xl hover:bg-white hover:text-[#194f82] transition-all duration-500 transform hover:scale-110 animate-floating">
          Entre em Contato Agora
        </button>
      </a>
    </div>
    <div class="absolute inset-0 overflow-hidden z-0">
      <svg class="absolute top-0 right-0 w-[200px] md:w-[300px] h-[300px] md:h-[500px] opacity-10 animate-spin-slow" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="none">
        <polygon points="50,0 100,100 0,100" fill="#ffffff" />
      </svg>
      <svg class="absolute bottom-0 left-0 w-[200px] md:w-[300px] h-[300px] md:h-[500px] opacity-10 animate-spin-slow-reverse" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="none">
        <polygon points="50,0 100,100 0,100" fill="#ffffff" />
      </svg>
    </div>
  </section>
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

@keyframes spin-slow {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes spin-slow-reverse {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(-360deg);
  }
}

@keyframes floating {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
}

.animate-slide-in {
  animation: slide-in 1.5s ease-out forwards;
}

.animate-spin-slow {
  animation: spin-slow 30s linear infinite;
}

.animate-spin-slow-reverse {
  animation: spin-slow-reverse 30s linear infinite;
}

.animate-floating {
  animation: floating 3s ease-in-out infinite;
}
</style>
