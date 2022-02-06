# PetDevShop
Projeto realizado no curso B7Web - Node + TS

### Pré-requisitos globais:
> npm install -g nodemon typescript ts-node

### Instalação
> npm install

### Para rodar o projeto
> npm run start-dev




# #################################################
# Todos os comandos e configurações utilizadas
   > npm init -y
   > tsc --init
      tsconfig.json
         > "target": "es2016"
         > "outDir": "./dist"
         > "rootDir": "./src"
         > "moduleResolution": "node"

   # Dependências
   > npm install express mustache-express dotenv

   # Dependências de Dev
   > npm install --save-dev @types/express @types/mustache-express @types/node

   # Dependências globais (Caso não já tenha instalado)
   > npm install -g nodemon typescript ts-node

   # Atalho para rodar projeto (package.json)
   "scripts": {
      "start-dev": "nodemon -e ts,json,mustache src/server.ts"
   }

