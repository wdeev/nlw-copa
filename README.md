# nlw-copa
reactjs-react-native-nextjs-nodejs

# iniciando o projeto 

    - npm init -y

# dependencias de desenvolvimento

    - npm i typescript -D

    - yarn add prisma -D

# dependencias de produção

    - npm i fastify

    - yarn add @prisma/client

# criando o setup do typescript

    - npx tsc --init


# Datasoucer

    - npx prisma init --datasource-provider SQLite 
        * codigo que inicia a configuração do prisma para que se utilize o SQLite

# criando uma migration com prisma

    - npx prisma migrate dev

# Visualização de tabela via navegador

    - yarn prisma studio

# Crianção do MER pelo prisma

    - yarn add i prisma-erd-generator @mermaid-js/mermaid-cli -D
    - npx prisma generate

# Prisma

    - yarn add @fastify/cors