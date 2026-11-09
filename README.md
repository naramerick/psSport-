## psSport — Backend API 

API REST desenvolvida para o gerenciamento completo de escolinhas e centros de treinamento esportivo. O sistema permite o controle de atletas, responsáveis, colaboradores, turmas, categorias, períodos letivos, matrículas e registro de presenças.

> **Projeto Colaborativo:** Este sistema foi desenvolvido **em equipe**. O repositório atual representa a migração da versão finalizada do backend para o portfólio individual, mantendo os créditos e o reconhecimento a todos os integrantes que participaram da arquitetura, desenvolvimento e testes da aplicação.

## Funcionalidades Principais

- Autenticação e Autorização: Login seguro com controle de acesso e permissões por perfil (colaboradores e responsáveis).
- Gestão de Atletas e Responsáveis: Cadastro de alunos, responsáveis financeiros/legais e vínculo entre eles.
- Gestão de Turmas e Categorias: Organização de modalidades, faixas etárias/categorias e horários de treino.
- Matrículas e Períodos: Controle de períodos letivos e gerenciamento de matrículas ativas.
- Controle de Frequência: Registro e acompanhamento de presença dos atletas nas aulas.
- Gestão de Colaboradores: Administração de professores, treinadores e equipe técnica.

## Tecnologias Utilizadas

- Node.js & Express — Estruturação do servidor e rotas da API REST.
- Banco de Dados Relacional (SQL) — Modelagem e persistência de dados (database/schema.sql).
- Middlewares Customizados — Tratamento global de erros, validação de rotas inexistentes (notFound) e autenticação/autorização via tokens.
- Dotenv — Gerenciamento de variáveis de ambiente.

## Como Executar o Projeto Localmente

1. Pré-requisitos

- Node.js instalado na máquina.
- Gerenciador de banco de dados SQL configurado (conforme especificado em database/schema.sql).

2. Instalação

- Clone este repositório e acesse a pasta do projeto:

git clone https://github.com/SEU-USUARIO/psSport-.git
cd psSport-


## Instale as dependências:

- npm install


3. Configuração do Ambiente

- Crie um arquivo .env na raiz do projeto baseado no arquivo .env.example e preencha com as credenciais do seu banco de dados e chaves de autenticação:

cp .env.example .env


## Execute o script localizado em database/schema.sql no seu banco de dados para criar as tabelas necessárias.

4. Iniciar o Servidor

Para rodar a aplicação em ambiente de desenvolvimento ou produção:

npm start


## (Verifique os scripts disponíveis no arquivo package.json, como npm run dev, caso utilize Nodemon).
