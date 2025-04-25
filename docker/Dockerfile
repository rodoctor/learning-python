FROM alpine:latest

# Instala Python 3 e pip
RUN apk add --no-cache python3 py3-pip

# Define diretório de trabalho
WORKDIR /app

# Copia arquivos da aplicação (opcional)
COPY . .

# Comando padrão
CMD ["python3"]