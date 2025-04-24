# 📬 ContatoWeb

Formulário web simples e eficiente para coleta de contatos com nome, e-mail e telefone. Os dados são armazenados em um arquivo CSV, processados via Python para garantir organização, eliminação de duplicatas e futura validação dos dados.

---

## 🚀 Objetivo

Criar uma aplicação leve para captação de contatos online com foco em:

- ✅ Interface amigável para o usuário
- ✅ Armazenamento em CSV
- 🔄 Eliminação automática de contatos duplicados
- 📋 Validação de e-mails e números de telefone
- 📊 Dashboard para visualização e análise de dados

---

## 📁 Estrutura do Projeto

```bash
market-research-mailing/
│
├── index.html         # Página principal do formulário
├── admin.html         # Painel de visualização de contatos
├── body.css           # Estilização do formulário
│
├── submit.php         # Script PHP para enviar os dados
├── form-data.py       # Script Python para processar o CSV
├── form_data.csv      # Armazenamento dos contatos
│
└── success.html       # Página exibida após envio com sucesso

