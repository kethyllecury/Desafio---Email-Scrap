# Coletor de Filmes via OMDb API com Envio por E-mail

Este projeto é um script backend em Python que consulta dados de filmes pela [OMDb API](https://www.omdbapi.com/) e envia essas informações por e-mail automaticamente. Ele é ideal para automatizar notificações de dados sobre filmes. Você pode rodá-lo facilmente no Google Colab.

## Funcionalidades

- 🔍 Busca dados completos de um filme via API OMDb
- 📧 Envia esses dados por e-mail com formatação simples
- ☁️ Roda 100% na nuvem via Google Colab

## Tecnologias Utilizadas

- Python 3 (Colab)
- `requests` (requisições HTTP)
- `smtplib` e `email` (envio de e-mail via SMTP)
- API pública [OMDb](https://www.omdbapi.com/)


## 🚀 Como Usar

### 1. Clone ou abra o código no [Google Colab](https://colab.research.google.com/)

### 2. Instale as dependências
```python
!pip install requests
