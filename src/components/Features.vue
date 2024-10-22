<template>
  <section class="py-16 md:py-24 bg-gradient-to-b from-[#f5f7fa] to-[#e0f7ff] relative overflow-hidden">
    <div class="container mx-auto text-center px-4 md:px-8 relative z-10">
      <h2 class="text-3xl md:text-5xl font-extrabold text-[#194f82] mb-12 md:mb-20 tracking-wider leading-tight animate-slide-up">
        Por que Escolher a Monitora Tech?
      </h2>
      <ul class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10 md:gap-16">
        <li class="bg-white p-8 md:p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-200">
          <div class="flex items-center justify-center mb-6 md:mb-8 text-[#56ace0]">
            <img
                src="https://cdn.pixabay.com/photo/2015/12/03/22/15/tablet-1075790_1280.jpg"
                alt="Monitoramento em Tempo Real"
                class="w-48 h-48 md:w-64 md:h-64 object-contain drop-shadow-xl animate-pulse-once border-4 border-[#56ace0] rounded-full"
            />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold text-[#194f82] mb-4 md:mb-6">
            Monitoramento em Tempo Real
          </h3>
          <p class="text-base md:text-lg text-[#333333]">
            Automatize o controle de vazão com dados precisos e em tempo real, proporcionando uma eficiência nunca vista.
          </p>
        </li>
        <li class="bg-white p-8 md:p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-400">
          <div class="flex items-center justify-center mb-6 md:mb-8 text-[#56ace0]">
            <img
                src="https://images.unsplash.com/photo-1599658880436-c61792e70672?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt="Visualização Intuitiva"
                class="w-48 h-48 md:w-64 md:h-64 object-contain drop-shadow-xl animate-pulse-once border-4 border-[#56ace0] rounded-full"
            />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold text-[#194f82] mb-4 md:mb-6">
            Visualização Intuitiva
          </h3>
          <p class="text-base md:text-lg text-[#333333]">
            Visualize gráficos e tabelas detalhadas de forma clara e simples, facilitando as análises e decisões.
          </p>
        </li>
        <li class="bg-white p-8 md:p-12 rounded-3xl shadow-2xl transform transition-all duration-700 hover:scale-105 hover:-translate-y-4 hover:shadow-4xl border-b-8 border-[#56ace0] hover:border-[#fbb040] animate-slide-up delay-600">
          <div class="flex items-center justify-center mb-6 md:mb-8 text-[#56ace0]">
            <img
                src="https://cdn.pixabay.com/photo/2018/07/14/11/28/blockchain-3537389_1280.jpg"
                alt="Conexão Segura"
                class="w-48 h-48 md:w-64 md:h-64 object-contain drop-shadow-xl animate-pulse-once border-4 border-[#56ace0] rounded-full"
            />
          </div>
          <h3 class="text-2xl md:text-3xl font-bold text-[#194f82] mb-4 md:mb-6">
            Conexão Segura
          </h3>
          <p class="text-base md:text-lg text-[#333333]">
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
