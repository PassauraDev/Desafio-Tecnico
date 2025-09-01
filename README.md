# Desafio Técnico - CRUD de Produtos

Este é um desafio simples, com o objetivo de avaliar seus conhecimentos e habilidades no desenvolvimento de sistemas web com Python!

---

## Introdução

Seu desafio é criar um pequeno sistema **CRUD (Criar, Ler, Atualizar e Deletar)** de produtos com uma interface web simples.  
Você pode usar HTML/CSS puro ou um framework como **Bootstrap** ou **TailwindCSS** (opcional).

O back-end deve ser desenvolvido em **Python**, utilizando frameworks e bibliotecas de sua preferência.  
O banco de dados pode ser **MySQL** ou **SQLite**.

> *Não existe uma forma certa ou errada de resolver este desafio!*  
> Serão avaliados pontos como:
> - Qualidade e organização do código
> - Clareza e legibilidade
> - Estrutura do projeto
> - Segurança básica da aplicação

---

## Definição do Desafio

### Requisitos Gerais

- O projeto **deve estar no GitHub**
- Envie apenas o link do repositório
- O projeto não pode fazer fork com outros projetos

---

## Login de Usuário

- Página de login com **usuário e senha**
- As credenciais devem ser validadas via **banco de dados**
- Apenas **usuários autenticados** podem acessar o CRUD
- Não é necessário criar tela de cadastro (o usuário pode ser inserido diretamente no banco)

---

## Tela Inicial (Home)

- Após o login, o usuário deve ser redirecionado para uma tela com a **lista de produtos cadastrados**
- Deve conter **botões** para:
  - Adicionar novo produto
  - Editar produto existente
  - Excluir produto

---

## Cadastro de Produto

Cada produto deve conter os seguintes campos:

- `Nome do produto`
- `Descrição`
- `Quantidade em estoque`
- `Preço`

---

## Funcionalidades do CRUD

- **Criar**: Formulário para adicionar um novo produto
- **Ler**: Lista de todos os produtos cadastrados
- **Atualizar**: Formulário para editar os dados de um produto existente
- **Deletar**: Botão para remover um produto do banco de dados

---

## Estrutura Sugerida do Projeto

crud_produtos/
│
├── app/ # Código principal da aplicação (rotas, conexão banco de dados, static etc.)
│
├── templates/ # Arquivos HTML (login, dashboard, formulários)
│
│
├── README.md # Descrição do projeto e instruções
│
└── requirements.txt # Bibliotecas necessárias 


Boa sorte! 🍀
