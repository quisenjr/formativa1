# Usar uma imagem base do Python
FROM python:3.8-slim-buster

# Definir o diretório de trabalho no container
WORKDIR /app

# Copiar o conteúdo local para o container
COPY . /app

# Instalar as dependências
RUN pip install --no-cache-dir -r requirements.txt

# Comando para executar a aplicação
CMD ["python", "app.py"]
