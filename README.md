# 🍽️ Sistema de Gerenciamento para Restaurantes

Este projeto é um sistema completo para gerenciamento de restaurantes, oferecendo funcionalidades como gestão de pedidos, cardápio online, pagamentos, controle financeiro, gerenciamento de mesas, cadastro de produtos e controle de estoque.

## 🚀 Tecnologias Utilizadas

O sistema é desenvolvido com as seguintes tecnologias:

- **Frontend:** [Next.js](https://nextjs.org/), [TailwindCSS](https://tailwindcss.com/), [Shadcn/UI](https://ui.shadcn.com/)
- **Backend:** [Go](https://go.dev/) com [Gin](https://gin-gonic.com/)
- **Banco de Dados:** [PostgreSQL](https://www.postgresql.org/)
- **Containerização:** [Docker](https://www.docker.com/)

## 📌 Funcionalidades Principais

✅ **Gerenciamento de Pedidos** - Registre, acompanhe e finalize pedidos dos clientes.\
✅ **Cardápio Online** - Permita que os clientes visualizem o menu pelo celular.\
✅ **Pagamentos Online** - Integração com métodos de pagamento digital.\
✅ **Dashboard Financeiro** - Exibição de estatísticas e resultados do restaurante.\
✅ **Gerenciamento de Mesas** - Organização de mesas e reservas no estabelecimento.\
✅ **Cadastro de Produtos** - Adicione e edite itens do cardápio.\
✅ **Controle de Estoque** - Monitore a quantidade de ingredientes e produtos disponíveis.

Mais funcionalidades serão adicionadas futuramente! 🚧

## 📂 Estrutura do Projeto

```
📦 restaurant-system
├── 📂 Front # Código do Next.js
├── 📂 Back   # Código do Go + Gin
├── 📂 database  # Configuração do PostgreSQL
├── 📄 docker-compose.yml  # Configuração do Docker
├── 📄 README.md  # Documentação do projeto
└── ...
```

## 🛠️ Como Rodar o Projeto Localmente

### Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) e [npm](https://nodejs.org/en/download)
- [Go](https://go.dev/)
- [Docker](https://www.docker.com/)

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/nicuoss/JetManager
   ```
2. Suba os containers com Docker:
   ```bash
   docker compose up --build -d
   ```
3. Acesse o backend:
   ```bash
   cd Back
   ./scripts/run.sh
   go run ./scripts/seed.go
   ```
4. Inicie o frontend:
   ```bash
   cd Front
   npm install
   npm run dev
   ```
5. O sistema estará disponível em [**http://localhost:3000**](http://localhost:8080) 🚀

## 📌 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

💡 \*Desenvolvido por \*[*Vinícius Sales e Thiago Marinho*](https://github.com/niciuoss)





