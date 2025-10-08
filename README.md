# Newsletter Automatizada de Notícias de TI

## Visão Geral
Este projeto tem como objetivo criar uma **newsletter automatizada** que reúne notícias de tecnologia da informação, realiza tradução quando necessário e distribui para assinantes. O sistema é híbrido, utilizando **Python** para scraping e processamento de notícias, **C#** para orquestração via API e **SQL Server + Hangfire** para persistência e agendamento de tarefas.

O projeto ainda está em construção, mas a arquitetura já foi definida.

## Funcionalidades Principais
- Scraping de sites de notícias de TI utilizando Python  
- Processamento de conteúdo, incluindo tokenização com SOAP4  
- Tradução automatizada (em implementação)  
- API em C# para receber dados do Python e gerenciar o envio de notícias  
- Persistência em SQL Server, com Hangfire para agendamento de tarefas periódicas  
- Estrutura modular para facilitar futuras integrações e expansão  

## Estrutura do Projeto
A estrutura do projeto foi organizada para separar responsabilidades e facilitar manutenção:

| Pasta / Arquivo               | Descrição                                                                                  |
|-------------------------------|-------------------------------------------------------------------------------------------|
| `PythonScraper/`              | Código Python responsável por scraping, tokenização e tradução de notícias                 |
| `CSharpAPI/`                  | Projeto C# que expõe a API para receber dados do Python e gerenciar envio                  |
| `Database/`                   | Scripts de criação e manutenção do banco SQL Server                                        |
| `Hangfire/`                   | Configuração de agendamento de tarefas periódicas no SQL Server                             |
| `Website/`                    | Site básico do projeto, permitindo visualização das notícias coletadas                     |
| `README.md`                   | Documento explicativo sobre o projeto e sua estrutura                                      |

> Observação: O projeto está em desenvolvimento, portanto algumas funcionalidades, como tradução automática, ainda não estão concluídas.

## Conceitos Aplicados
- Python para scraping e processamento de dados  
- Tokenização de conteúdo utilizando SOAP4  
- C# e Web API para orquestração e integração entre sistemas  
- SQL Server para armazenamento de notícias  
- Hangfire para agendamento de tarefas recorrentes  
- Arquitetura modular e integração entre múltiplas tecnologias  

## Como Funciona (Atualmente)
1. Python realiza scraping em sites de notícias de TI e gera dados estruturados.  
2. Conteúdo é processado com tokenização SOAP4 (pré-tradução).  
3. API em C# recebe os dados via requisições e armazena no banco SQL Server.  
4. Hangfire será utilizado para agendar o envio periódico da newsletter.  
5. Futuramente, será implementada a tradução automática e envio final aos assinantes.

## Status do Projeto
- Site básico funcionando  
- Scraping e tokenização implementados  
- API C# criada, mas integração completa ainda em desenvolvimento  
- Tradução automática ainda não implementada  
- Sistema em construção, arquitetura já definida para futuras melhorias  

## Observações
Este projeto demonstra habilidades em **Python, C#, SQL Server e integração de múltiplas tecnologias**, além de conceitos de scraping, processamento de linguagem e agendamento de tarefas. Serve como base para desenvolvimento de um sistema de newsletter profissional e escalável.
