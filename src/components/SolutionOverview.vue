<template>
  <section class="py-24 bg-gradient-to-b from-[#f5f7fa] to-[#e0f7ff] relative overflow-hidden">
    <div class="container mx-auto text-center">
      <h2 class="text-5xl font-extrabold mb-12 text-[#194f82] tracking-wider leading-tight animate-slide-in">
        Nossa Solução Automatizada
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-16 mt-12">
        <div class="bg-gradient-to-r from-[#ffffff] to-[#f0f4f8] p-12 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Monitoramento Avançado</h3>
          <p class="text-lg text-[#444]">
            Monitoramento contínuo da vazão hídrica com sensores de precisão, proporcionando dados confiáveis em tempo real.
          </p>
        </div>
        <div class="bg-gradient-to-r from-[#ffffff] to-[#f0f4f8] p-12 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Hardware Inteligente</h3>
          <p class="text-lg text-[#444]">
            Hardware integrado que coleta e transmite dados automaticamente para nossa plataforma web, garantindo praticidade e eficiência.
          </p>
        </div>
        <div class="bg-gradient-to-r from-[#ffffff] to-[#f0f4f8] p-12 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Visualização em Tempo Real</h3>
          <p class="text-lg text-[#444]">
            A plataforma web oferece visualização de dados em tempo real, gráficos dinâmicos e análises precisas para tomada de decisão.
          </p>
        </div>
      </div>
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

.animate-slide-in {
  animation: slide-in 1.5s ease-out forwards;
}

.hover\:shadow-2xl:hover {
  box-shadow: 0 25px 35px -10px rgba(0, 0, 0, 0.1);
}

.hover\:scale-105:hover {
  transform: scale(1.05);
}
</style>
