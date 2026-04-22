# IAMentordeCarreiraDescubraSeuFuturoemTech
# 🚀 Career Path Finder & Roadmap Planner

Este projeto consiste num sistema de dois agentes inteligentes de IA desenhados para ajudar profissionais e estudantes a ingressarem no mercado de tecnologia. O fluxo é dividido em duas etapas principais: **Diagnóstico de Perfil** e **Planeamento de Carreira**.

## 📋 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Arquitetura do Sistema](#-arquitetura-do-sistema)
- [Funcionamento](#-funcionamento)
  - [Agente 1: Entrevistador de Carreira](#agente-1-entrevistador-de-carreira)
  - [Agente 2: Planeador de Roadmap](#agente-2-planeador-de-roadmap)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)

---

## 📖 Sobre o Projeto
O objetivo deste sistema é reduzir a paralisia de escolha para novos talentos em tecnologia. Através de uma entrevista estruturada, a IA identifica afinidades, analisa a viabilidade com base na disponibilidade do utilizador e entrega um plano de ação pronto para execução.

## 🏗 Arquitetura do Sistema

O projeto utiliza o conceito de **Handoff (Transferência)** entre agentes:
1. **Agent 1 (Recruiter)**: Foca na recolha de dados qualitativos e quantitativos.
2. **Agent 2 (Planner)**: Transforma os dados em execução técnica e cronograma de estudos.

---

## ⚙️ Funcionamento

### Agente 1: Entrevistador de Carreira
O primeiro agente atua como um especialista em perfis profissionais.
* **Missão:** Conduzir uma entrevista de 7 perguntas (uma de cada vez).
* **Critérios de Análise:** Utiliza uma matriz de decisão interna para avaliar afinidade, demanda de mercado e tempo de aprendizagem (*ramp-up*).
* **Output:** Sugere 3 carreiras ranqueadas com justificativas personalizadas, vantagens e desafios.

### Agente 2: Planeador de Roadmap
Após a escolha da carreira no Agente 1, os dados são transferidos para este especialista.
* **Missão:** Gerar um plano de estudos de 90 dias totalmente personalizado.
* **Personalização Dinâmica:** O roadmap adapta-se conforme a carga horária semanal e o nível de experiência do utilizador.
* **Conteúdo do Plano:**
    * **Visão do Dia a Dia:** O que o profissional realmente faz.
    * **Mapa de Skills:** Hard e soft skills essenciais.
    * **Roadmap de 90 dias:** Dividido em Fundamentos, Prática e Portfólio.
    * **Projeto de Portfólio:** Um desafio prático com entregáveis definidos.
    * **Guia de Entrevistas:** Perguntas comuns e como respondê-las.
    * **Indicação DIO:** Conexão direta com trilhas de aprendizagem na plataforma DIO.

---

## 🛠 Tecnologias Utilizadas
- **Engenharia de Prompts:** Técnicas de "Role Play", "Few-Shot Chain of Thought" e "Constraint Checklist".
- **LLM (Large Language Model):** Compatível com GPT-4, Claude ou Gemini.
- **Framework de Agentes:** Estrutura lógica de transição de contexto.

---

## 🚀 Como Utilizar
1. Inicie a conversa com o **Prompt do Agente 1**.
2. Responda às 7 perguntas sequencialmente.
3. Escolha uma das 3 carreiras sugeridas.
4. Utilize o **Prompt do Agente 2**, alimentando-o com os dados resumidos pelo primeiro agente para obter o seu roadmap.

---
> *Nota: Este projeto foi desenvolvido para fins educacionais e de mentoria de carreira automática.*
