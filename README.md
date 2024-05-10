# bulario-eletronico

## Como executar o programa:
1. Clone este repositório em sua máquina local:

```
git clone https://github.com/marcusvcalves/bulario-eletronico
```

2. Navegue até o diretório raiz do projeto:

```
cd bulario-eletronico
```

### Utilizando Docker:
1. Execute o comando Docker Compose para iniciar o aplicativo (certifique-se de ter o Docker e o Docker Compose instalados em sua máquina):

```
docker-compose up --build
```

### Sem a utilização do Docker:

1. Instalar o servidor para a API e rodar o servidor local

```
npm install -g json-server; json-server api/dotlib.json -s ./api/public
```
2. Iniciar o frontend
   
```
cd frontend; npm i; npm run dev
```

### O aplicativo estará disponível em http://localhost:8080.
