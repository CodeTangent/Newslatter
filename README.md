# 📰 Automated Tech Newsletter (Python + .NET + Hangfire)

## 🚀 Descrição

Sistema automatizado para coleta, processamento e distribuição de notícias de tecnologia, utilizando uma arquitetura multi-stack com Python, .NET e SQL Server.

---

## 🧠 Problema resolvido

Automatizar o processo de coleta e distribuição de conteúdo, eliminando a necessidade de curadoria manual de notícias.

---

## 🛠 Tecnologias

* Python (web scraping e processamento)
* C# / .NET (Web API)
* SQL Server (persistência)
* Hangfire (agendamento de tarefas)

---

## ⚙️ Arquitetura

```text
Scraper (Python)
        ↓
Processamento de Conteúdo
        ↓
API (.NET)
        ↓
Banco de Dados (SQL Server)
        ↓
Hangfire (Jobs agendados)
        ↓
Distribuição de conteúdo
```

---

## 🔌 Como funciona

* Scripts em Python coletam notícias de fontes externas
* Os dados são processados e estruturados
* A API em .NET recebe e armazena os dados
* Hangfire gerencia tarefas recorrentes (coleta e envio)
* O sistema prepara o conteúdo para distribuição automatizada

---

## ⚙️ Funcionalidades

* Coleta automatizada de notícias
* Processamento e estruturação de conteúdo
* Integração entre Python e API REST
* Persistência em banco relacional
* Agendamento de tarefas com Hangfire

---

## ▶️ Como executar (parcial)

```bash id="l2uv6y"
# Backend .NET
dotnet run

# Python (scraper)
python scraper.py
```

---

## 📊 Status do projeto

* Pipeline de coleta implementado
* API criada e funcional
* Integração parcial entre serviços
* Agendamento com Hangfire configurado
* Sistema em evolução

---

## 🎯 Objetivo do projeto

Demonstrar a construção de um pipeline de dados distribuído, integrando múltiplas tecnologias para automação de tarefas.

---

## 📈 Melhorias futuras

* Sistema de envio de newsletter (email)
* Dashboard de administração
* Filtros inteligentes de conteúdo
* Deploy em cloud (Azure / AWS)

---
