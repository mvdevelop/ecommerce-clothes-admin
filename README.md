
## 👔 E-Commerce Clothes Admin
O eCommerce Clothes Admin é o centro de controle da plataforma de moda. Este painel administrativo foi desenvolvido com Vite e React para oferecer uma interface de alta performance, permitindo que gestores gerenciem estoque, monitorem pedidos e controlem toda a operação da loja de forma ágil e segura.

## 🚀 Funcionalidades
Dashboard de Métricas: Visualização rápida de vendas, novos pedidos e produtos em destaque.

Gestão de Inventário (CRUD): Controle total sobre o catálogo (Adicionar, editar, remover e listar roupas).

Controle de Pedidos: Acompanhamento de status de compras em tempo real.

Gestão de Categorias: Organização dinâmica de departamentos (Masculino, Feminino, Acessórios, etc).

Upload de Imagens: Integração para gerenciamento visual dos produtos.

Interface Responsiva: Painel totalmente adaptável para uso em tablets e desktops via TailwindCSS.

## 🛠️ Tecnologias Utilizadas
React (Vite): Biblioteca principal com ferramentas de build ultra-rápidas.

TailwindCSS: Estilização utilitária para uma interface administrativa limpa e profissional.

React Router Dom: Navegação entre as diferentes seções do painel.

Axios: Comunicação com o backend para sincronização de dados.

Lucide React: Conjunto de ícones minimalistas para facilitar a navegação.

Context API: Gerenciamento de estado global (Autenticação e dados do sistema).

## 📦 Como rodar o projeto
Clone o repositório:

Bash

git clone https://github.com/mvdevelop/ecommerce-clothes-admin.git
cd ecommerce-clothes-admin
Instale as dependências:

Bash

npm install
Configure o Backend: Certifique-se de que o ecommerce-clothes-backend está rodando e configure a URL base no arquivo de ambiente .env:

Snippet de código

VITE_API_URL=http://localhost:5000/api
Inicie a aplicação:

Bash

npm run dev
Acesse: http://localhost:5173

## 📂 Estrutura de Pastas
Plaintext

ecommerce-clothes-admin/
├── src/
│   ├── components/   # UI (Sidebar, Navbar, Table, Modal)
│   ├── pages/        # Telas (Dashboard, Products, Orders, Login)
│   ├── services/     # Integração com a API (Axios)
│   ├── context/      # Estados globais (AuthContext)
│   ├── hooks/        # Lógicas customizadas
│   └── App.jsx       # Definição de rotas e layout
├── public/           # Logos e favicon
└── tailwind.config.js # Configurações de tema e cores

## 🎨 Preview da Interface
Nota: Adicione aqui um print do seu dashboard principal mostrando os gráficos ou a tabela de produtos organizada.

## 👨‍💻 Autor
Desenvolvido com ❤️ por mvdevelop.

GitHub: @mvdevelop

## 📄 Licença
Este projeto está sob a licença MIT.
