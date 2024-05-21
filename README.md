# 📱 Social Media Go

Bem-vindo ao projeto **Social Media Go**, uma rede social desenvolvida utilizando Golang. Este projeto aplica os conceitos principais do Go e oferece uma interface web intuitiva e moderna.

## 🚀 Introdução

O **Social Media Go** é uma aplicação de rede social que permite aos usuários se conectar, compartilhar atualizações e interagir uns com os outros. Este projeto é ideal para quem quer aprender Golang na prática, explorando desde a construção de APIs até a criação de uma interface web dinâmica.

## ✨ Funcionalidades Principais

- **Autenticação de Usuários**: Registro, login e gerenciamento de sessões.
- **Perfis de Usuários**: Criação e personalização de perfis.
- **Postagens**: Criação, edição e exclusão de postagens.
- **Comentários e Likes**: Interação com postagens através de comentários e likes.
- **Feed de Notícias**: Exibição das atualizações mais recentes dos usuários seguidos.
- **Mensagens Privadas**: Comunicação direta entre usuários.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Golang
- **Banco de Dados**: MySQL
- **Front-End**: HTML, CSS, JavaScript
- **Autenticação**: JWT (JSON Web Tokens)

## 📦 Instalação

Para rodar este projeto localmente, siga as instruções abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/wagnerdsc/social-media-go.git
   cd social-media-go

2. Configure as variáveis de ambiente no arquivo .env:
   ```go
    DB_USUARIO=golang
    DB_SENHA=golang
    DB_NOME=devbook
    API_PORT=5000

4. Instale as dependências:
   ```
   go mod tidy

5. Execute as migrações do banco de dados:
   ```bash
   go run migrations/main.go

7. Inicie o servidor:
   ```bash
   go run main.go

## 💻 Uso
Com o servidor rodando, você pode acessar a aplicação no seu navegador em http://localhost:5000. 
A partir daí, você pode se registrar, fazer login e explorar todas as funcionalidades da rede social.

## 📄 Licença
Este projeto está licenciado sob a MIT License.

