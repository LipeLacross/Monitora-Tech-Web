<template>
  <section id="sobre" class="bg-gradient-to-b from-[#194f82] via-[#56ace0] to-[#194f82] py-32 md:py-40 lg:py-52 relative overflow-hidden">
    <div class="container mx-auto text-center px-4 md:px-8 lg:px-16 relative z-10 animate-fade-in-up">
      <div class="flex flex-col items-center space-y-6 sm:space-y-8 md:space-y-12">
        <h1 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl font-extrabold text-white tracking-widest leading-tight drop-shadow-2xl transition-transform duration-1000 hover:scale-110">
          Monitora Tech
        </h1>

        <p class="text-lg sm:text-xl md:text-2xl lg:text-3xl xl:text-3xl text-white max-w-md sm:max-w-lg md:max-w-2xl lg:max-w-4xl drop-shadow-lg animate-fade-in-once">
          Soluções inovadoras que utilizam tecnologia de ponta, monitoramento contínuo e visualização de dados em tempo real para revolucionar o seu controle hídrico.
        </p>

        <a href="https://wa.me/55989910562" target="_blank" rel="noopener noreferrer">
          <button class="bg-[#fbb040] text-[#194f82] py-2 sm:py-3 md:py-4 px-8 sm:px-10 md:px-16 rounded-full shadow-2xl hover:bg-[#ffffff] hover:text-[#56ace0] transition-all duration-500 transform hover:scale-110 hover:shadow-4xl animate-floating font-bold">
            Solicite uma Demonstração
          </button>
        </a>
      </div>
    </div>

    <div class="absolute inset-0 z-0 overflow-hidden">
      <svg class="absolute -top-32 -left-24 opacity-20 w-48 sm:w-56 md:w-[300px] lg:w-[400px] xl:w-[500px] h-48 sm:h-56 md:h-[300px] lg:h-[400px] xl:h-[500px] animate-spin-slow" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <circle fill="#ffffff" cx="50" cy="50" r="50" />
      </svg>
      <svg class="absolute bottom-0 -right-20 opacity-20 w-40 sm:w-48 md:w-[250px] lg:w-[350px] xl:w-[450px] h-40 sm:h-48 md:h-[250px] lg:h-[350px] xl:h-[450px] animate-bounce" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <polygon fill="#ffffff" points="50,0 100,100 0,100" />
      </svg>
    </div>
  </section>
</template>

<style scoped>
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
