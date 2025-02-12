# nodets-canil

# iniciar o projeto

`npm init`

# instalar typescript em desenvolvimento

`npm install -D typescript`

# inicia o typescript

`npx tsc --init`

`descomentar "rootDir": "./src"`
`descomentar "outDir": "./dist"`
`descomentar "moduleResolution": "node10"`

# instalar as dependências

`npm install express mustache-express dotenv`
`npm install --save-dev @types/express @types/mustache-express @types/node`
`npm install --save-dev nodemon`
`npm i ts-node-dev --save-dev`

# acrescentar no scripts do packege.json

`"dev": "nodemon -e ts,json,mustache src/server.ts"`

# instalação

`npm install`

# para rodar o projeto

`npm run dev`
