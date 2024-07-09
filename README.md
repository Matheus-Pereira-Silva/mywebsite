# 2º Desafio | NODE.JS + AWS_MAY 24:

Uma API para gerenciamento de sessões de cinema, incluindo funcionalidades para listar, criar, atualizar e deletar sessões.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **[Implantação](#-implanta%C3%A7%C3%A3o)** para saber como implantar o projeto.

### 📋 Pré-requisitos

-Node.js (versão 14 ou superior)
-npm (versão 6 ou superior)
-SQLite (para banco de dados)

### 🔧 Instalação
-Clone o repositório:
git clone git clone https://github.com/Levi-21545/API_Cinema.git
cd API_Cinema

-Instale as dependências do projeto:
npm install

-Copie o arquivo .env.example para .env e configure suas variáveis de ambiente:
cp .env.example .env

-Execute as migrações do banco de dados:
npm run typeorm migration:run

-Inicie o servidor:
npm run dev

## ⚙️ Executando os testes

Para rodar os testes automatizados do sistema, utilize o comando abaixo:
npx vitest run

### 🔩 Analise os testes de ponta a ponta
Esses testes verificam o fluxo completo da aplicação, garantindo que todos os componentes funcionem corretamente juntos.

bash
Copiar código
npx vitest run --e2e

## 📦 Implantação

Adicione notas adicionais sobre como implantar isso em um sistema ativo

## 🛠️ Construído com

-Node.js - Ambiente de execução JavaScript
-TypeScript - Superconjunto de JavaScript que adiciona tipagem estática
-TypeORM - ORM para TypeScript e JavaScript
-SQLite - Banco de dados SQL leve
-Swagger - Ferramenta para documentação de APIs
-ESLint - Linter para identificar e corrigir problemas no código
-Prettier - Formatador de código
-Vitest - Framework de testes

## 📌 Versão

Nós usamos o GitHub para controle de versão.

## ✒️ Autores
# Equipe: Node Ninjas
Este time é composto por: <br>
[Levi](https://github.com/Levi-21545) <br>
[Ygor](https://github.com/farvillage) <br>
[Matheus](https://github.com/Matheus-Pereira-Silva) <br>
[Guilherme](https://github.com/guilhermeswarowksi) <br>
[Felipe](https://github.com/FelipeDetoni) <br>

## 📄 Licença


