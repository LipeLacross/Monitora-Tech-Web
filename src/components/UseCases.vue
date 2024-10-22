<template>
  <section class="bg-gradient-to-b from-[#e0f7ff] to-[#f5f7fa] py-24 relative overflow-hidden">
    <div class="container mx-auto text-center">
      <h2 class="text-5xl font-extrabold mb-16 text-[#194f82] tracking-wider leading-tight animate-slide-in">
        Quem Pode se Beneficiar?
      </h2>
      <ul class="grid grid-cols-1 md:grid-cols-3 gap-16">
        <li class="bg-gradient-to-b from-[#ffffff] to-[#f0f4f8] p-10 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <div class="flex items-center justify-center mb-8">
            <div class="bg-[#56ace0] p-4 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </div>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Estações de Tratamento</h3>
          <p class="text-lg text-[#444]">
            Automatize o controle e economize recursos, garantindo maior eficiência e qualidade no tratamento de água.
          </p>
        </li>
        <li class="bg-gradient-to-b from-[#ffffff] to-[#f0f4f8] p-10 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <div class="flex items-center justify-center mb-8">
            <div class="bg-[#fbb040] p-4 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 20l9-5-9-5-9 5 9 5z" />
              </svg>
            </div>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Pequenos Agricultores</h3>
          <p class="text-lg text-[#444]">
            Monitore a vazão de água para otimizar o uso, aumentar a produtividade e evitar desperdícios.
          </p>
        </li>
        <li class="bg-gradient-to-b from-[#ffffff] to-[#f0f4f8] p-10 rounded-[2rem] shadow-lg hover:shadow-2xl transform transition-all duration-500 hover:scale-105">
          <div class="flex items-center justify-center mb-8">
            <div class="bg-[#56ace0] p-4 rounded-full">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h18v18H3V3z" />
              </svg>
            </div>
          </div>
          <h3 class="text-3xl font-bold text-[#194f82] mb-6">Indústrias</h3>
          <p class="text-lg text-[#444]">
            Soluções que garantem o monitoramento hídrico eficiente, reduzindo custos e aumentando a confiabilidade nos processos.
          </p>
        </li>
      </ul>
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
<script setup lang="ts">
</script>