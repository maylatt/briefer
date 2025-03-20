# Usa a imagem oficial do Node.js 18
FROM node:18-bullseye

# Define o diretório de trabalho
WORKDIR /workspace

# Instala o Yarn globalmente
RUN corepack enable && corepack prepare yarn@stable --activate

# Copia os arquivos do projeto
COPY . .

# Define o usuário padrão como "node"
USER node