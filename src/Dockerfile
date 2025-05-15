FROM ubuntu:22.04
ARG NODE_MAJOR=20

# Dependências e instalação via script NodeSource
RUN apt-get update && \
    apt-get install -y curl ca-certificates gnupg && \
    curl -fsSL https://deb.nodesource.com/setup_${NODE_MAJOR}.x | bash - && \
    apt-get install -y nodejs

# Define diretório da aplicação
WORKDIR /app

# Copia e instala dependências do projeto
COPY . .
RUN npm install

# Define ponto de entrada
ENTRYPOINT [ "node", "server.js" ]