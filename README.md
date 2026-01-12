# 🚀 RAG API com IA Local

Este projeto faz parte da minha jornada de aprendizado em Engenharia de Dados para IA. Aqui, construí uma API de **Geração Aumentada de Recuperação (RAG)** que utiliza o Ollama para rodar modelos de linguagem localmente.

## 🧠 Sobre o Projeto
A API foi desenvolvida com **FastAPI** e permite que novos conhecimentos sejam injetados dinamicamente. Durante os testes, "ensinei" à IA fatos sobre minha vida, como minha paixão por skate e meus planos para 2027, e ela foi capaz de responder com precisão baseada nesse contexto.

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem base.
- **FastAPI**: Criação dos endpoints da API.
- **Ollama (Llama 3)**: Motor de IA local.
- **Git/GitHub**: Versionamento e portfólio.

## 📍 Contexto
Projeto desenvolvido em Curitiba, a "Europa brasileira".

## 🚀 Como rodar
1. Instale o [Ollama](https://ollama.com/) e baixe o modelo: `ollama run llama3`.
2. Instale as dependências: `pip install -r requirements.txt`.
3. Rode a API: `uvicorn app:app --reload`.
4. Acesse o Swagger em: `http://127.0.0.1:8000/docs`.

## 📈 Próximos Passos
- [x] Fase 1: Build da RAG API.
- [ ] Fase 2: Containerização com Docker.
- [ ] Fase 3: Deploy com Kubernetes.
- [ ] Fase 4:Automate with GitHub Actions
- [ ] Fase 5:Monitor and detect issues