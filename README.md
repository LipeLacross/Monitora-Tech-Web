## 🌐 [English Version of README](README_EN.md)

# Monitora Tech Landing Page

Este projeto é uma landing page para a Monitora Tech, focada na resolução do problema de monitoramento da vazão hídrica em calha parshall e vertedouros de pequeno e médio porte de maneira automatizada. A plataforma web permite a plotagem de dados em tempo real, visualização de gráficos e históricos de vazões.

## 🔨 Funcionalidades do Projeto

- **Monitoramento em Tempo Real**: Visualização contínua da vazão hídrica em gráficos e tabelas.
- **Automatização Completa**: Exibição de dados adquiridos pelo hardware desenvolvido.
- **Solução para Pequenos Agricultores e Indústrias**: Economize recursos e otimize processos com dados precisos.

### Exemplo Visual do Projeto

![chrome-capture-2024-10-22](https://github.com/user-attachments/assets/0f830c43-63c5-4bfc-85fd-4c7ff6b52451)

## ✔️ Técnicas e Tecnologias Utilizadas

- **Vue.js**: Framework JavaScript utilizado para a criação de componentes reativos e modulares.
- **Vite**: Ferramenta de build rápida para desenvolvimento ágil com Vue.js, que oferece HMR (Hot Module Replacement) para feedback instantâneo durante o desenvolvimento.
- **Tailwind CSS**: Framework de CSS utilitário que permite estilização rápida, responsiva e com classes personalizadas.
- **JavaScript (ES6+)**: Utilizado para manipulação de eventos, interatividade e lógica no front-end com Vue.js.
- **Responsividade e Design Mobile-First**: Técnicas utilizadas para garantir que a aplicação funcione bem em dispositivos móveis e telas de diferentes tamanhos.

## 📁 Estrutura do Projeto

- **public/**
    - `favicon.ico`: Ícone do site.
    - `img/`: Imagens utilizadas no site (logo, fotos de membros da equipe, etc.).
- **src/**
    - `App.vue`: Componente principal que rende o layout base.
    - **assets/**
        - `base.css`: Estilos base e paleta de cores.
        - `main.css`: Estilos globais do projeto, incluindo Tailwind CSS.
    - **components/**: Contém todos os componentes reutilizáveis, como `Header.vue`, `Footer.vue`, `Team.vue`, entre outros.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:
      ```bash
      node -v
      ```
    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:
      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Instale as dependências**:
    - Navegue até a pasta do projeto e instale as dependências com:
      ```bash
      npm install
      ```

4. **Inicie o servidor de desenvolvimento**:
    - Execute o comando:
      ```bash
      npm run dev
      ```
    - O servidor de desenvolvimento será iniciado e a aplicação estará disponível no navegador no endereço: [http://localhost:3000](http://localhost:3000).

## 🌐 Deploy

O projeto pode ser facilmente implantado em plataformas como [Vercel](https://vercel.com/) ou [Netlify](https://www.netlify.com/). Basta conectar o repositório, escolher a branch principal e configurar os comandos de build e deploy:

- **Comando de Build**: `npm run build`
- **Diretório de Saída**: `dist`

Agora, seu projeto estará pronto e disponível online!
