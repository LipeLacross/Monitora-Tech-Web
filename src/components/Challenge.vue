<template>
  <section class="bg-gradient-to-b from-[#e0f7ff] to-[#f5f7fa] py-24 relative overflow-hidden">
    <div class="container mx-auto text-center relative z-10 animate-fade-in-up">
      <h2 class="text-5xl font-extrabold text-[#194f82] mb-12 tracking-wider leading-tight">
        O Problema que Solucionamos
      </h2>
      <p class="text-2xl text-[#333333] max-w-3xl mx-auto mb-16 leading-relaxed animate-fade-in-up delay-300">
        Estações de tratamento de água enfrentam desafios críticos devido à falta de automatização. A medição manual da vazão hídrica resulta em baixa eficiência, desperdício de recursos, e atrasos na tomada de decisões, comprometendo a qualidade e aumentando os custos operacionais.
      </p>
      <p class="text-lg text-[#555555] max-w-4xl mx-auto animate-fade-in-up delay-500">
        A Monitora Tech surgiu para resolver este problema, oferecendo uma solução automatizada que permite monitoramento contínuo da vazão hídrica em tempo real. Dessa forma, as decisões sobre o uso de aditivos químicos podem ser feitas com precisão, evitando desperdícios e aumentando a eficiência em mais de 60%. Além disso, nossa solução elimina a necessidade de verificações manuais demoradas, liberando tempo valioso para outras tarefas e reduzindo erros humanos.
      </p>
    </div>

    <div class="absolute inset-0 overflow-hidden z-0">
      <div class="absolute top-0 left-0 w-[600px] h-[600px] bg-gradient-radial from-[#ffffff33] to-transparent rounded-full blur-3xl opacity-40 transform -translate-x-1/2 -translate-y-1/2"></div>
      <div class="absolute bottom-0 right-0 w-[700px] h-[700px] bg-gradient-radial from-[#ffffff33] to-transparent rounded-full blur-3xl opacity-40 transform translate-x-1/2 translate-y-1/2"></div>
    </div>
  </section>
</template>

<style scoped>
@keyframes fade-in-up {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in-up {
  animation: fade-in-up 1.5s ease-out forwards;
}

.delay-300 {
  animation-delay: 0.3s;
}

.delay-500 {
  animation-delay: 0.5s;
}
</style>
