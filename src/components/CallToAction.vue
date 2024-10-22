<template>
  <section id="contato" class="bg-gradient-to-r from-[#194f82] via-[#56ace0] to-[#194f82] py-20 text-white text-center relative overflow-hidden">
    <div class="container mx-auto relative z-10">
      <h2 class="text-5xl font-extrabold mb-12 tracking-wider leading-tight animate-slide-in">
        Pronto para Automatizar seu Monitoramento Hídrico?
      </h2>
      <p class="text-lg mb-8 max-w-3xl mx-auto">
        A Monitora Tech está aqui para transformar o seu controle hídrico com soluções inovadoras e de ponta. Entre em contato e veja como podemos ajudar a otimizar seus processos.
      </p>
      <button class="bg-[#fbb040] text-[#194f82] py-4 px-12 rounded-full font-bold shadow-xl hover:bg-white hover:text-[#194f82] transition-all duration-500 transform hover:scale-110 animate-floating">
        Entre em Contato Agora
      </button>
    </div>
    <div class="absolute inset-0 overflow-hidden z-0">
      <svg class="absolute top-0 right-0 w-[300px] h-[500px] opacity-10 animate-spin-slow" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="none">
        <polygon points="50,0 100,100 0,100" fill="#ffffff" />
      </svg>
      <svg class="absolute bottom-0 left-0 w-[300px] h-[500px] opacity-10 animate-spin-slow-reverse" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" fill="none">
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
