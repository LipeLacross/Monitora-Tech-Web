## 🌐 [Versão em Português do README](README_PT.md)

# Monitora Tech Landing Page

This project is a landing page for Monitora Tech, focused on solving the problem of automated water flow monitoring in parshall flumes and small to medium-sized weirs. The web platform allows real-time data plotting, visualization of flow charts, and flow history.

## 🔨 Project Features

- **Real-Time Monitoring**: Continuous visualization of water flow data in charts and tables.
- **Full Automation**: Display of data acquired through the developed hardware.
- **Solution for Small Farmers and Industries**: Save resources and optimize processes with precise data.

### Visual Example of the Project

![chrome-capture-2024-10-22](https://github.com/user-attachments/assets/0f830c43-63c5-4bfc-85fd-4c7ff6b52451)

## ✔️ Technologies and Techniques Used

- **Vue.js**: JavaScript framework used for creating reactive and modular components.
- **Vite**: Fast build tool for agile development with Vue.js, offering HMR (Hot Module Replacement) for instant feedback during development.
- **Tailwind CSS**: Utility-first CSS framework for rapid, responsive styling with custom classes.
- **JavaScript (ES6+)**: Used for event handling, interactivity, and front-end logic with Vue.js.
- **Responsive Design & Mobile-First Approach**: Techniques used to ensure the application works well on mobile devices and various screen sizes.

## 📁 Project Structure

- **public/**
    - `favicon.ico`: Website icon.
    - `img/`: Images used on the site (logo, team photos, etc.).
- **src/**
    - `App.vue`: Main component rendering the base layout.
    - **assets/**
        - `base.css`: Base styles and color palette.
        - `main.css`: Global project styles, including Tailwind CSS.
    - **components/**: Contains all reusable components like `Header.vue`, `Footer.vue`, `Team.vue`, among others.

## 🛠️ Running the Project

To start the project locally, follow the steps below:

1. **Make sure Node.js is installed**:
    - [Node.js](https://nodejs.org/) is required to run the project. You can check if it’s already installed with:
      ```bash
      node -v
      ```
    - If not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and run the following command in your terminal:
      ```bash
      git clone <REPOSITORY_URL>
      ```

3. **Install the dependencies**:
    - Navigate to the project folder and install the dependencies with:
      ```bash
      npm install
      ```

4. **Start the development server**:
    - Run the command:
      ```bash
      npm run dev
      ```
    - The development server will start, and the application will be available in your browser at: [http://localhost:3000](http://localhost:3000).

## 🌐 Deployment

The project can be easily deployed on platforms like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/). Just connect the repository, choose the main branch, and configure the build and deploy commands:

- **Build Command**: `npm run build`
- **Output Directory**: `dist`

Now your project is ready and available online!
