<template>
  <section class="py-24 bg-gradient-to-b from-[#f5f7fa] to-[#e0f7ff] relative overflow-hidden">
    <div class="container mx-auto text-center relative z-10">
      <h2 class="text-5xl font-extrabold text-[#194f82] mb-20 tracking-wider leading-tight animate-slide-up">
        Por que Escolher a Monitora Tech?
      </h2>
      <ul class="grid grid-cols-1 md:grid-cols-3 gap-16">
        <li class="bg-white p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-200">
          <div class="flex items-center justify-center mb-8 text-[#56ace0]">
            <i class="fas fa-chart-line text-8xl drop-shadow-xl animate-pulse-once"></i>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">
            Monitoramento em Tempo Real
          </h3>
          <p class="text-lg text-[#333333]">
            Automatize o controle de vazão com dados precisos e em tempo real, proporcionando uma eficiência nunca vista.
          </p>
        </li>
        <li class="bg-white p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-400">
          <div class="flex items-center justify-center mb-8 text-[#56ace0]">
            <i class="fas fa-chart-pie text-8xl drop-shadow-xl animate-pulse-once"></i>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">
            Visualização Intuitiva
          </h3>
          <p class="text-lg text-[#333333]">
            Visualize gráficos e tabelas detalhadas de forma clara e simples, facilitando as análises e decisões.
          </p>
        </li>
        <li class="bg-white p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-600">
          <div class="flex items-center justify-center mb-8 text-[#56ace0]">
            <i class="fas fa-lock text-8xl drop-shadow-xl animate-pulse-once"></i>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">
            Conexão Segura
          </h3>
          <p class="text-lg text-[#333333]">
            Transmissão de dados via LoRa com total segurança e confiabilidade, mantendo suas operações tranquilas.
          </p>
        </li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
@keyframes rotate-slow {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

@keyframes bounce-slow {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}

@keyframes slide-up {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes pulse-once {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.1);
  }
  100% {
    transform: scale(1);
  }
}

.animate-rotate-slow {
  animation: rotate-slow 30s linear infinite;
}

.animate-bounce-slow {
  animation: bounce-slow 15s ease-in-out infinite;
}

.animate-slide-up {
  animation: slide-up 1.5s ease-out forwards;
}

.animate-pulse-once {
  animation: pulse-once 1.5s ease-in-out;
}

.delay-200 {
  animation-delay: 0.2s;
}

.delay-400 {
  animation-delay: 0.4s;
}

.delay-600 {
  animation-delay: 0.6s;
}
</style>
