# IA Fitness Coach 

Modelo inteligente para **geração automatizada de planos de treino personalizados em PDF**, integrando **LLM**, **RAG (Retrieval-Augmented Generation)** e **orquestração com n8n**.

> Projeto desenvolvido no contexto de **mestrado profissional**, com foco na aplicação prática de **IA generativa** na área de Educação Física.

---

## ✦ Visão Geral

O **IA Fitness Coach** automatiza a criação de planos de treino de musculação a partir de dados do usuário, combinando:
- **Conhecimento técnico estruturado**
- **Modelos de linguagem**
- **Fluxos automatizados**

O resultado é um documento técnico, padronizado e personalizado, entregue em **PDF**.

---

## ✦ Objetivos

- 🧩 Automatizar a geração de planos de treino personalizados  
- 📚 Integrar **LLM + base de conhecimento (RAG)**  
- ⚙️ Orquestrar todo o fluxo de ponta a ponta  
- 📄 Gerar documentos finais padronizados em PDF  
---

## ✦ Arquitetura do Sistema

### Entrada de Dados
- Nome  
- Sexo  
- Idade  
- Peso  
- Altura  
- Frequência semanal  
- Objetivo do treino
- Dicas

### Camada Inteligente
- **LLM (LLaMA / Mixtral – Groq)**  
- **RAG** com bases técnicas em PDF por objetivo:
  - Hipertrofia  
  - Força  
  - Emagrecimento  
  - Condicionamento Físico  
  - Mobilidade  

### Orquestração
- **n8n** coordena:
  - Seleção da base correta  
  - Execução do RAG  
  - Geração do texto pela LLM  
  - Tratamento e formatação  
  - Criação do PDF final  

---

## ✦ Fluxo de Execução

1. Coleta dos dados do usuário  
2. Identificação do objetivo de treino  
3. Consulta à base de conhecimento correspondente  
4. Geração do plano pela LLM  
5. Sanitização e formatação do conteúdo  
6. Inserção em template  
7. Geração e entrega do PDF  

---

## ✦ Estrutura do Documento Gerado

- Informações pessoais  
- Objetivo do treino  
- Organização semanal  
- Descrição técnica dos treinos  
- Orientações complementares  
- Header e footer personalizados  

---

## ✦ Tecnologias

- 🧠 **LLM** — LLaMA / Mixtral (Groq)  
- 📚 **RAG** — Bases técnicas em PDF  
- 🔄 **n8n** — Orquestração de fluxos  
- 🗄️ **Supabase / Vector Store**   
- 📄 **PDF Generator** — Documento final  


