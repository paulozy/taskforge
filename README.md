# Backend Detonado - TaskForge

O **Backend Detonado** é um laboratório público onde o **TaskForge** é construído e evoluído, com foco em arquitetura de backend, boas práticas e evolução sob pressão. O projeto busca ensinar como um sistema começa simples e se torna robusto à medida que cresce.

## 🚀 Visão Geral

- **Produto**: Sistema colaborativo de gerenciamento de projetos e tarefas.
- **Objetivo**: Ensinar práticas de backend, arquitetura evolutiva e como resolver problemas reais de sistemas.
- **Stack**:
  - **Backend**: Node.js + Fastify + TypeScript
  - **Banco de Dados**: PostgreSQL
  - **Ferramentas**: Docker, ORM, Query Builder, CI simples.

## 🎯 Como Rodar Localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/paulozy/taskforge.git
   ```
2. Instale as dependências:

   ```bash
   cd taskforge
   npm install
   ```
3. Configure o banco de dados:

   - Crie um banco PostgreSQL local.
   - Configure as variáveis de ambiente no `.env`.
4. Rode o projeto:

   ```bash
   npm run dev
   ```
5. Acesse o sistema no seu navegador em `http://localhost:3000`.

## 🤝 Como Contribuir

Estamos sempre abertos a contribuições! Para ajudar:

1. Faça um fork do repositório.
2. Crie uma branch com sua feature ou correção: `git checkout -b minha-nova-feature`
3. Comite suas alterações: `git commit -am 'Adicionando nova feature'`
4. Envie seu PR para a branch `main`.

## 🔧 Ferramentas

- **GitHub Actions**: Para rodar testes e garantir a qualidade do código.
- **Docker**: Para facilitar a configuração do ambiente local.
- **PostgreSQL**: Banco de dados relacional utilizado no projeto.

## 📝 Roadmap

O projeto evolui através das temporadas:

1. **Temporada 1 - Fundação**: Modular monolith, backend simples.
2. **Temporada 2 - Assíncrono**: Adicionando processamento assíncrono e filas.
3. **Temporada 3 - Escala**: Melhorias de performance com cache e observabilidade.
4. **Temporada 4 - Distribuição**: Arquitetura distribuída com workers e microservices.

## 🗣 Contribuidores

Agradecemos a todos os contribuidores que ajudam a manter esse projeto evoluindo. Para ver a lista de contribuidores, acesse o arquivo [CONTRIBUTORS.md](CONTRIBUTORS.md).

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais informações.

## 📣 Discussões

Participe da discussão no [GitHub Discussions](https://github.com/seu-usuario/backend-detonado/discussions) para sugestões, dúvidas ou para colaborar com novas ideias.
