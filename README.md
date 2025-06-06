# 📆 Agenda Web

Agenda Web é uma aplicação desenvolvida em **Laravel** que permite ao usuário cadastrar e acompanhar compromissos de forma prática, integrada com **WhatsApp**, **Telegram** e uma **interface web intuitiva**.

## ✨ Funcionalidades

* ✅ Cadastro de compromissos via WhatsApp, Telegram e Web
* 📲 Sincronização em tempo real com WhatsApp e Telegram
* 🔔 Envio de lembretes automáticos quando o compromisso estiver próximo
* 🌐 Plataforma web para gerenciamento completo dos compromissos
* 🔒 Sistema de autenticação para garantir a segurança do usuário

## 🚀 Tecnologias Utilizadas

* **Laravel** 
* **Bootstrap** 
* **API do WhatsApp** 
* **Bot do Telegram** 
* **MySQL** 
* **Blade** 

## 🛠️ Instalação e Configuração

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/agenda-web.git
   cd agenda-web
   ```

2. Instale as dependências:

   ```bash
   composer install
   ```

3. Copie o arquivo `.env` e configure suas variáveis:

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. Configure o banco de dados no `.env` e rode as migrations:

   ```bash
   php artisan migrate
   ```

5. Inicie o servidor:

   ```bash
   php artisan serve
   ```

6. Configure os bots do WhatsApp e Telegram conforme a documentação interna.

## 📦 Estrutura do Projeto

```
agenda-web/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
└── ...
```

## 🔔 Notificações

O sistema envia lembretes automáticos aos usuários via WhatsApp e Telegram quando um compromisso estiver se aproximando, garantindo que você nunca perca um evento importante.

## 🙋‍♂️ Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📝 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo `LICENSE` para mais detalhes.