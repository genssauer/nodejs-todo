# Aplicação Node.js com Fastify, Redis, Prisma e WebSocket

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/genssauer/nodejs-todo.git
```

2. Instale as dependências:

```bash
npm install
```

## Uso

1. Inicie o serviço:

```bash
npm run dev
```

2. Importar csv:

```bash
node streams/import-csv.js
```

## Funcionalidades

- API REST:
  POST /tasks
  GET /tasks
  PUT /tasks/:id
  PATCH /tasks/:id/complete
  DELETE /tasks/:id
- Importação de arquivo CSV
