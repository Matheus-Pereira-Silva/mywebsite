# 2º Desafio | NODE.JS + AWS_MAY 24:

Uma API para gerenciamento de sessões de cinema, incluindo funcionalidades para listar, criar, atualizar e deletar sessões.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.
### 🗂️ Estrutura de pastas
- `index.js`: Arquivo principal da aplicação.
- `routes/`: Contém as definições de rotas.
- `controllers/`: Contém os controladores que lidam com a lógica de negócios.
- `services/`: Serviços que encapsulam a lógica de negócios e interagem com os repositórios.
- `entities/`: Definições das entidades do TypeORM que representam as tabelas do banco de dados.
- `repositories/`: Gerenciam a interação direta com o banco de dados utilizando as entidades.
- `migrations/`: Scripts para atualizar o esquema do banco de dados de forma controlada.
- `tests/`: Testes automatizados para garantir a qualidade e a confiabilidade do código.

### 📋 Pré-requisitos

- Node.js (versão 14 ou superior)
- npm
- SQLite (para banco de dados)

### 🔧 Instalação
1. Clone o repositório:
  ```bash
  git clone git clone https://github.com/Levi-21545/API_Cinema.git
  ```

  ```bash
  cd API_Cinema
  ```

2. Instale as dependências do projeto:
  ```
  bash
  npm install
  ```

3. Copie o arquivo `.env.example` para `.env` e configure suas variáveis de ambiente:
```bash
cp .env.example .env
```

4. Execute as migrações do banco de dados:
```bash
npm run typeorm migration:run
```

5. Inicie o servidor:
```bash
npm run dev
```

## ⚙️ Executando os testes

Para rodar os testes automatizados do sistema, utilize o comando abaixo:
```bash
npx vitest run
```

## 🛠️ Construído com

- Node.js - Ambiente de execução JavaScript
- TypeScript - Superconjunto de JavaScript que adiciona tipagem estática
- TypeORM - ORM para TypeScript e JavaScript
- SQLite - Banco de dados SQL leve
- Swagger - Ferramenta para documentação de APIs
- ESLint - Linter para identificar e corrigir problemas no código
- Prettier - Formatador de código
- Vitest - Framework de testes

## ✒️ Autores
# Equipe: Node Ninjas
Este time é composto por: <br>
[Levi](https://github.com/Levi-21545) <br>
[Ygor](https://github.com/farvillage) <br>
[Matheus](https://github.com/Matheus-Pereira-Silva) <br>
[Guilherme](https://github.com/guilhermeswarowksi) <br>
[Felipe](https://github.com/FelipeDetoni) <br>



