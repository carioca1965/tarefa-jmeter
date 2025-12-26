# Tarefa JMeter – Teste de Carga YouTube

Este repositório contém um script de teste de carga desenvolvido com **Apache JMeter**, conforme solicitado no exercício.

## 📌 Objetivo
Executar um teste de carga simulando múltiplos usuários realizando buscas no YouTube, utilizando massa de dados externa.

## ⚙️ Configurações do Teste

- **Ferramenta:** Apache JMeter
- **Endpoint:** https://www.youtube.com/results
- **Método:** GET
- **Usuários (Threads):** 20
- **Ramp-up:** 60 segundos
- **Duração:** 3 minutos (180 segundos)
- **Massa de dados:** Arquivo CSV com 10 palavras

## 📁 Estrutura do Projeto

