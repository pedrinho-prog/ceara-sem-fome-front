# 🚀 Sistema de Crédito Social Comunitário

## Visão Geral do Projeto

O **Sistema de Crédito Social Comunitário** é uma plataforma digital projetada para facilitar a distribuição e o uso de **créditos internos (sociais)** em uma comunidade ou rede de comércios locais. O objetivo principal é promover o consumo em estabelecimentos parceiros, gerenciar o fluxo de produtos e créditos, e coletar dados para análise nutricional e social da comunidade.

---

## 🏗️ Estrutura e Módulos do Sistema

O sistema é dividido em **oito módulos funcionais** principais, organizados para garantir uma clara separação de responsabilidades.

| Módulo | Foco Principal | Telas Chave | Funcionalidade Principal |
| :--- | :--- | :--- | :--- |
| **1. Autenticação e Acesso** | Login e Segurança | Login, Cadastro, Recuperação de Senha. | Controle de permissões por tipo de usuário. |
| **2. Perfil de Usuário/Comerciante** | Gestão de Dados | Meu Perfil, Informações do Comércio, Gestão de Perfis (Admin). | Edição de dados pessoais e cadastro de informações do comércio. |
| **3. Catálogo de Produtos** | Comércio e Exibição | Catálogo de Produtos, Detalhe do Produto, Gestão de Produtos. | Cadastro, atualização e exibição de produtos para compra. |
| **4. Carrinho e Créditos** | Transações Financeiras | Carrinho de Compras, Checkout, Extrato, Distribuição de Créditos (Admin). | Finalização da compra via créditos internos e registro de transações. |
| **5. Comunicação e Notificações** | Alertas e Avisos | Avisos/Pedidos Recebidos, Caixa de Entrada/Notificações, Comunicados Globais (Admin). | Aviso de novos pedidos (Comerciante) e confirmação de compra (Usuário). |
| **6. Painel Administrativo** | Controle e Supervisão | Dashboard Admin Principal, Validação de Comerciantes, Gestão de Usuários. | Cadastro, validação, ativação/bloqueio de usuários e acesso a relatórios básicos. |
| **7. Relatórios e Análise Nutricional** | Insights e Dados | Formulário de Produto (Tabela Nutricional), Relatório de Análise Nutricional. | Vinculação de Tabela Nutricional e identificação de déficits nutricionais. |
| **8. Expansão e Integrações Futuras** | Crescimento e Novas Tecnologias | Configurações de Pagamento (PIX), Acompanhamento de Pedido, Configurações de Integração. | Preparação para integração com PIX, IA e sistemas públicos. |

---

## 👤 Perfis de Acesso

O sistema é customizado para atender a três perfis distintos, cada um com um conjunto específico de permissões e telas:

| Perfil | Responsabilidades |
| :--- | :--- |
| **Usuário Padrão** | Busca e compra de produtos, gestão do próprio perfil, consulta ao extrato de créditos. |
| **Comerciante** | Cadastro e gestão de produtos, recebimento e acompanhamento de pedidos, gestão das informações do seu comércio. |
| **Administrador** | Validação de comerciantes, gestão de todos os usuários, distribuição de créditos sociais e análise de relatórios do sistema. |

---

## 🗺️ Principais Fluxos de Tela

Os fluxos de navegação garantem uma experiência de usuário eficiente:

### 1. Fluxo de Compra (Usuário Padrão)
`Login` → `Catálogo de Produtos` → `Detalhe do Produto` → `Carrinho de Compras` → `Checkout (Confirmação)` → `Acompanhamento de Pedido`.

### 2. Fluxo de Gestão de Vendas (Comerciante)
`Login` → `Informações do Comércio` → `Gestão de Produtos` → `Formulário de Produto` (com Tabela Nutricional) → `Avisos/Pedidos Recebidos` → `Gestão de Entregas`.

### 3. Fluxo de Controle (Administrador)
`Login` → `Dashboard Admin Principal` → `Validação de Comerciantes` / `Gestão de Usuários` / `Distribuição de Créditos` / `Relatório de Análise Nutricional`.

---

## 🛠️ Tecnologias Sugeridas

A ser definido pela equipe, mas a arquitetura deve ser robusta e escalável, suportando um alto volume de transações e a coleta de dados para análise.

---

## 📝 Contato

Para dúvidas ou contribuições, contate o mantenedor do projeto.

***
*Este README será atualizado à medida que o projeto avança nas fases de desenvolvimento e prototipagem.*
