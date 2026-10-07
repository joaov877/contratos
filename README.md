API de Gestão de Contratos

API REST desenvolvida em Node.js e TypeScript para gerenciamento de contratos, integrada com PostgreSQL e Redis, totalmente containerizada com Docker.

---

##  Tecnologias Utilizadas

- **Node.js** (v20)
- **TypeScript**
- **PostgreSQL 15** (Banco de dados relacional)
- **Redis 7** (Cache / Gerenciamento de filas)
- **Docker & Docker Compose** (Containerização)

---

##  Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

---

### 1. Clocar o repositório e configurar variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto com base no `.env.example`:

```bash
cp .env.example .env
