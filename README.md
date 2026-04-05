# 📈 Ed Seykota: O Guia do Trader Sistemático

## 🔵 Contexto e Objetivos
Este repositório é o resultado de um estudo aprofundado sobre a metodologia de **Ed Seykota**, um dos maiores pioneiros do *trend following* computadorizado. Meu objetivo foi dissecar a lógica matemática e os gatilhos psicológicos que permitem a execução de um sistema de trading com consistência estatística.

**Objetivos deste material:**
- Consolidar as regras de **Trend Following** aplicadas ao trading moderno.
- Analisar a matemática do **Portfolio Heat** e gestão de risco avançada.
- Documentar o processo de **Engenharia de Prompts** utilizado para extrair insights de fontes complexas.

---

## 🟢 Curadoria de Fontes
Para garantir a fidelidade técnica, este guia foi construído com base em 5 fontes fundamentais:

1.  **Seykota.com (FAQ & Resources):** Repositório oficial com décadas de insights diretos do autor. [Acesse aqui](https://www.seykota.com/).
2.  **Market Wizards (Jack Schwager):** Entrevista clássica que detalha a transição do trading manual para o sistemático. [Acesse aqui](https://www.youtube.com/watch?v=LUJex56D0PE).
3.  **Determining Optimal Risk (Seykota & Druz):** Whitepaper técnico sobre a matemática do risco e o conceito de "Uncle Point". [Ver PDF](https://www.trendfollowing.com/whitepaper/DETERMI.PDF).
4.  **The Trading Tribe Process (TTP):** Documentação sobre a integração de emoções no processo de decisão. [Acesse aqui](https://www.seykota.com/tribe/TT_Process/index.htm).
5.  **The Whipsaw Song:** Lições sobre a disciplina de aceitar pequenas perdas como custo operacional. [Acesse aqui](https://tradergav.com/the-whipsaw-song-by-ed-seykota/).

---

## 🟡 Engenharia de Prompts e "Cicatrizes"
O uso de IA para este estudo exigiu um processo de refinamento iterativo. Abaixo, documento os aprendizados (cicatrizes) do processo:

### **Prompt de Extração de Lógica**
> *"Atue como um Engenheiro de Sistemas. Converta as regras de saída de Ed Seykota em um algoritmo de pseudocódigo, priorizando a volatilidade do ativo (ATR) em vez de stops fixos."*

- **Cicatriz (Troubleshooting):** Inicialmente, a IA gerou stops baseados em porcentagem fixa do preço. Tive que corrigir o prompt especificando que **Seykota utiliza a volatilidade do mercado** para definir o espaço de respiro do ativo, evitando saídas prematuras em ruídos (whipsaws).

### **Prompt de Auditoria Psicológica**
> *"Com base no TTP, analise o comportamento de um trader que hesita em entrar em um sinal de rompimento após três perdas seguidas. Quais perguntas Ed Seykota faria para identificar a intenção subconsciente?"*

- **Aprendizado:** O mercado valoriza o raciocínio por trás da execução. A dificuldade foi fazer a IA não dar conselhos motivacionais genéricos, mas sim focar na **"Intenção Positiva"** do sentimento, conforme a metodologia original.

---

## 🔴 Miniguia de Estudo (Entrega Final)

### **1. Resumos Estruturados**
- **Trend Following:** Não prevemos o futuro; reagimos ao presente. Se a tendência é de alta, compramos. Se o stop é atingido, saímos sem questionar.
- **Gestão de Risco (Heat):** O risco total da conta (Portfolio Heat) deve ser controlado para que o trader nunca atinja o seu **Uncle Point** (ponto de ruptura emocional).
- **Psicologia:** "Todo mundo ganha o que quer do mercado". Perdas persistentes muitas vezes escondem uma busca subconsciente por drama ou validação de crenças.

### **2. Glossário de Conceitos**
- **Portfolio Heat:** Risco total somado de todas as posições abertas.
- **Uncle Point:** O nível de prejuízo que faz o trader abandonar o sistema.
- **Whipsaw:** Movimento volátil que aciona o stop antes do mercado seguir a tendência original.
- **TTP:** Processo de sentir as emoções para que elas não virem comportamentos reativos.

### **3. Prompts Reutilizáveis**
- **Revisão de Risco:** *"Calcule o tamanho da posição para uma conta de R$ 50k, com risco de 1% e stop posicionado a 2 ATR de distância."*
- **Análise Comportamental:** *"Aja como um mentor do Trading Tribe. Ajude-me a processar a frustração de um dia de fúria no Scalp M1."*

---
*Este material foi desenvolvido para fins de estudo pessoal e aprimoramento técnico em Trading.*
