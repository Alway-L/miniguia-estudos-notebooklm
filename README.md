# miniguia-estudos-notebooklm
miniguia-estudos-notebooklm para estudos da DIO


# 📚 Caderno Temático: Automação de Service Desk com Python

## 🎯 Contexto e Objetivos
Como profissional de suporte N1 lidando com alto volume de tickets diários, o objetivo deste estudo é explorar como a linguagem Python pode ser utilizada para automatizar tarefas repetitivas, extrair métricas de atendimento e interagir diretamente com a API do Jira.
**Objetivos:**
* Entender os fundamentos da biblioteca `requests` em Python.
* Mapear como autenticar e consumir endpoints da API REST do Jira.
* Criar scripts simples para triagem e atualização de chamados em lote.

## 📖 Curadoria de Fontes
Os seguintes materiais foram inseridos no NotebookLM para embasar este guia:
1. [Documentação Oficial da API REST do Jira] (Inserir link/PDF)
2. [Guia de Início Rápido da biblioteca Requests (Python)] (Inserir link/PDF)
3. [Artigo: Boas práticas de automação em ITIL e Service Desk] (Inserir link/PDF)

## 🛠️ Engenharia de Prompts e "Cicatrizes"

**Teste 1: Busca de conceitos básicos**
* **Prompt:** "Com base nos documentos, como posso usar Python para pegar a lista de chamados abertos hoje no Jira?"
* **Resultado:** A IA deu um código genérico, sem focar na autenticação.
* **Cicatriz (Ajuste):** Percebi que precisava ser mais específico sobre a segurança.
* **Prompt Refinado:** "Considerando o documento da API do Jira, crie um script Python usando 'requests' que inclua a autenticação por token e faça um GET nos chamados com status 'Open' da fila de suporte N1."

*(Adicione mais 2 ou 3 exemplos de testes, erros e acertos aqui)*

## 🚀 Miniguia de Estudo

### 1. Resumo Estruturado
*(Cole aqui o resumo gerado pelo NotebookLM sobre como estruturar a automação, quais bibliotecas usar e os cuidados com segurança de credenciais).*

### 2. Glossário
* **Endpoint:** URL específica onde a API disponibiliza um recurso.
* **JQL (Jira Query Language):** Linguagem usada para filtrar chamados no Jira.
* **Token de API:** Chave de segurança usada no script Python para provar sua identidade ao sistema.
* *(Adicione mais termos...)*

### 3. Prompts Reutilizáveis para Revisão
* "Atue como um Engenheiro de Software Sênior e revise este script Python para consumo de API, apontando melhorias na tratativa de erros (try/except)."
* "Gere 5 perguntas de múltipla escolha sobre autenticação de APIs baseadas nos documentos que fizemos upload."
