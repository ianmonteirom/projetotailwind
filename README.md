# Instaland os pacotes do TailWind
npm install -D tailwindcss postcss autoprefixer

# Criando os arquivos de configuração do tailwind

npx tailwindcss init -p

# Colocando as configurações de content no tailwind.config

content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

# colocando as dependencias de estilzização do tailwind no index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

# Extensão para utilizar as classes do tailwind

TailWind CSS IntelliSense



# Colocar o cdn no index.html
  <script src="https://cdn.tailwindcss.com"></script>


# Provedor de hospedagem de projetos React

https://www.netlify.com


# para fazer o deploy é preciso subir o projeto para o github e conectar o netlify com seu github