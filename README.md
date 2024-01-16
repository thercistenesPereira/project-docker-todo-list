# project-docker-todo-list

Projeto de introdução ao Docker

## Sumário
- [Pré-requisitos](#pré-requisitos)
- [Primeiros Passos](#primeiros-passos)
  - [Instalação](#instalação)
  - [Uso](#uso)
- [Docker](#docker)
- [Contribuições](#contribuições)
- [Licença](#licença)

## Pré-requisitos

- Docker (se aplicável)
- Node.js e npm

## Primeiros Passos

### Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-nome-de-usuario/seu-repo.git
cd seu-repo
```

Instale as dependências:

```bash
npm install
```

### Uso
Execute a aplicação:
```
npm start
```

Acesse `http://localhost:3001` em seu navegador.

### Docker

Se preferir usar o Docker, siga estas etapas:

```bash
docker build -t nome-da-sua-aplicacao .
docker run -p 3001:3001 nome-da-sua-aplicacao
```

