<!-- Team.vue -->
<template>
  <section class="team-section py-16 bg-[#f8f8f8]">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold text-[#194f82] mb-10">Nosso Time</h2>
      <div class="flex flex-wrap justify-center gap-8">
        <div
            v-for="member in team"
            :key="member.id"
            class="max-w-xs bg-white shadow-md rounded-lg p-6 transform transition duration-500 hover:scale-105"
        >
          <div class="image-container w-32 h-32 mx-auto mb-4">
            <img
                :src="member.image"
                :alt="member.name"
                class="w-full h-full object-cover rounded-full"
            />
          </div>
          <h3 class="text-2xl font-semibold text-[#194f82]">{{ member.name }}</h3>
          <p class="text-[#56ace0]">{{ member.role }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Team',
  data() {
    return {
      team: [
        {
          id: 1,
          name: 'Gabriel Menezes',
          role: 'CEO & Fundador',
          image: '/img/gabriel.png',
        },
        {
          id: 2,
          name: 'Felipe Moreira',
          role: 'Desenvolvedor Fullstack',
          image: '/img/felipe.jpg',
        },
        {
          id: 3,
          name: 'Claybson Jordão',
          role: 'Engenheiro de Hardware',
          image: 'https://via.placeholder.com/150',
        },
      ],
    };
  },
};
</script>

<style scoped>
.team-section {
  background-color: var(--color-background-soft);
}

.container {
  max-width: 1200px;
  padding: 0 20px;
  margin: 0 auto;
}

.image-container {
  width: 8rem;
  height: 8rem;
}

@media (min-width: 768px) {
  .team-section .flex-wrap {
    justify-content: space-between;
  }
}
</style>
