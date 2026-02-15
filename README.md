<img src="https://github.com/Pierre-Mendes/First-Challenge-Bootcamp-Java-DIO/assets/63386178/da4a13ca-375c-4546-99e5-034786980e47" alt="Banner" style="width:100%;" />

---

# 🎂 Birthday Coupon Email Automation

![n8n](https://img.shields.io/badge/n8n-automation-orange)
![SendGrid](https://img.shields.io/badge/SendGrid-email-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Code%20Nodes-yellow)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-finalizado-brightgreen)

Este repositório contém uma automação completa de **Email Marketing** construída com **n8n**, responsável por enviar automaticamente **cupons de aniversário personalizados** para clientes.

> **n8n · Automação · Email Marketing · SendGrid · JavaScript · Integração de APIs**

---

# 🇧🇷 Versão em Português

## 🎯 Objetivo

Criar um workflow automatizado capaz de:

🔹 Buscar clientes em uma base JSON hospedada no GitHub
🔹 Identificar aniversariantes do mês atual
🔹 Gerar cupons únicos automaticamente
🔹 Enviar emails personalizados para cada cliente

Tudo isso rodando automaticamente sem intervenção manual.

---

## ⚙️ Como funciona o Workflow

A automação executa os seguintes passos:

1️⃣ Busca a base de clientes via HTTP Request (GitHub Gist)
2️⃣ Converte a string JSON em itens do n8n
3️⃣ Filtra clientes que fazem aniversário no mês atual
4️⃣ Gera um cupom exclusivo para cada cliente
5️⃣ Envia email individual usando SendGrid

---

## 🚀 Tecnologias e Ferramentas

* **Automação:** n8n Cloud
* **Envio de emails:** SendGrid (SMTP)
* **Base de dados:** GitHub Gist (JSON)
* **Lógica:** JavaScript (Code Nodes)

---

## 📁 Estrutura do Repositório

```
workflow/
 └── birthday-coupon-workflow.json

assets/
 └── workflow.png
```

---

## 📦 Como importar no n8n

1. Baixe o arquivo em `/workflow/birthday-coupon-workflow.json`
2. No n8n clique em **Import workflow**
3. Configure suas credenciais SMTP do SendGrid
4. Execute o workflow 🚀

---

## 💡 O que este projeto demonstra

✔ Automação de processos
✔ Integração entre múltiplos serviços
✔ Envio de emails transacionais
✔ Uso de JavaScript dentro do n8n
✔ Boas práticas de automação no-code/low-code

---

# 🇺🇸 English Version

## 🎯 Goal

Create an automated workflow capable of:

🔹 Fetching customers from a JSON database hosted on GitHub
🔹 Identifying customers with birthdays in the current month
🔹 Generating unique discount coupons automatically
🔹 Sending personalized emails to each customer

All running automatically with no manual intervention.

---

## ⚙️ How the Workflow Works

The automation performs the following steps:

1️⃣ Fetches customer data via HTTP Request (GitHub Gist)
2️⃣ Converts JSON string into n8n items
3️⃣ Filters customers with birthdays in the current month
4️⃣ Generates a unique coupon for each customer
5️⃣ Sends individual emails using SendGrid

---

## 🚀 Tech Stack

* **Automation:** n8n Cloud
* **Email delivery:** SendGrid (SMTP)
* **Database:** GitHub Gist (JSON)
* **Logic:** JavaScript (Code Nodes)

---

## 📦 How to import the workflow

1. Download `/workflow/birthday-coupon-workflow.json`
2. In n8n click **Import workflow**
3. Configure SendGrid SMTP credentials
4. Run the workflow 🚀

---

# 👨‍💻 Autor

Feito por [Pierre Mendes Salatiel](https://github.com/Pierre-Mendes)
