<template>
  <section id="sobre" class="bg-gradient-to-b from-[#194f82] via-[#56ace0] to-[#e0f7ff] py-36 relative overflow-hidden">
    <div class="container mx-auto text-center relative z-10 animate-fade-in-up">
      <div class="flex flex-col items-center space-y-12">
        <!-- Título com Animação de Aparição -->
        <h1 class="text-6xl md:text-7xl font-extrabold text-white tracking-widest leading-tight drop-shadow-2xl transition-transform duration-1000 hover:scale-110">
          Automatize o Monitoramento de Vazão Hídrica
        </h1>

        <!-- Texto Descritivo com Animação de Aparição -->
        <p class="text-2xl md:text-3xl text-white max-w-4xl drop-shadow-lg animate-fade-in-once">
          Soluções inovadoras que utilizam tecnologia de ponta, monitoramento contínuo e visualização de dados em tempo real para revolucionar o seu controle hídrico.
        </p>

        <!-- Botão com Animação de Flutuação -->
        <button class="bg-[#fbb040] text-[#194f82] py-4 px-16 rounded-full shadow-2xl hover:bg-[#ffffff] hover:text-[#56ace0] transition-all duration-500 transform hover:scale-110 hover:shadow-4xl animate-floating font-bold">
          Solicite uma Demonstração
        </button>
      </div>
    </div>

    <!-- Formas SVG no Fundo -->
    <div class="absolute top-0 left-0 right-0 bottom-0 z-0 overflow-hidden">
      <svg class="absolute -top-32 -left-24 opacity-20 w-[600px] h-[600px] animate-spin-slow" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <circle fill="#ffffff" cx="50" cy="50" r="50" />
      </svg>
      <svg class="absolute bottom-0 -right-20 opacity-20 w-[500px] h-[500px] animate-bounce" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <polygon fill="#ffffff" points="50,0 100,100 0,100" />
      </svg>
    </div>
  </section>
</template>

<style scoped>
/* Animações Personalizadas Otimizadas */
@keyframes spin-slow {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes fade-in-up {
  0% {
    opacity: 0;
    transform: translateY(30px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}

@keyframes floating {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-15px);
  }
}

.animate-spin-slow {
  animation: spin-slow 20s linear infinite;
}

.animate-fade-in-once {
  animation: fade-in-up 1.5s ease-out forwards;
}

.animate-bounce {
  animation: bounce 10s ease-in-out infinite;
}

.animate-floating {
  animation: floating 4s ease-in-out infinite;
}
</style>
