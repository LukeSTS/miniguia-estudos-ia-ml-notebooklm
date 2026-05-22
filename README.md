# 🤖 Miniguia de Estudos: Inteligência Artificial & Machine Learning com NotebookLM

> **Desafio de Projeto — DIO | Explorando os Recursos de IA Generativa com Microsoft Copilot e OpenAI**  
> Caderno temático criado com auxílio do **Google NotebookLM**, explorando fundamentos, conceitos e aplicações de IA e Machine Learning.

---

## 📋 Sumário

1. [Contexto e Objetivos](#-contexto-e-objetivos)
2. [Curadoria de Fontes](#-curadoria-de-fontes)
3. [Engenharia de Prompts e Cicatrizes](#-engenharia-de-prompts-e-cicatrizes)
4. [Miniguia de Estudo — Entrega Final](#-miniguia-de-estudo--entrega-final)
   - [Resumos Estruturados](#-resumos-estruturados)
   - [Glossário](#-glossário)
   - [Prompts Reutilizáveis](#-prompts-reutilizáveis)

---

## 🎯 Contexto e Objetivos

### Por que Inteligência Artificial & Machine Learning?

Vivemos a maior transformação tecnológica desde a internet. Ferramentas como ChatGPT, Copilot, Gemini e NotebookLM já fazem parte do cotidiano profissional — e entender **como elas funcionam por dentro** é o diferencial que separa quem apenas usa de quem **constrói e inova**.

Este caderno temático foi criado para consolidar uma base sólida em IA e ML, partindo dos fundamentos matemáticos até chegar em aplicações práticas com modelos de linguagem (LLMs).

### Objetivos de Estudo

| # | Objetivo | Status |
|---|----------|--------|
| 1 | Compreender os tipos de aprendizado de máquina (supervisionado, não supervisionado e por reforço) | ✅ |
| 2 | Entender a arquitetura Transformer e sua relação com LLMs | ✅ |
| 3 | Explorar técnicas de engenharia de prompts aplicadas a modelos generativos | ✅ |
| 4 | Mapear aplicações práticas de IA no mercado de trabalho atual | ✅ |
| 5 | Construir um vocabulário técnico sólido para comunicação com equipes de dados e produto | ✅ |

---

## 📚 Curadoria de Fontes

As fontes abaixo foram selecionadas por serem **abertas, confiáveis e complementares** — cobrindo desde a teoria até a prática.

### Fonte 1 — Artificial Intelligence: A Modern Approach (Russel & Norvig) — Capítulos selecionados
> **Tipo:** PDF acadêmico (domínio público / acesso aberto via repositórios universitários)  
> **Link:** [https://aima.cs.berkeley.edu/](https://aima.cs.berkeley.edu/)  
> **Por que escolhi:** Referência canônica da área. Usei os capítulos sobre agentes inteligentes, busca e aprendizado para construir a base conceitual.

---

### Fonte 2 — Machine Learning Yearning (Andrew Ng)
> **Tipo:** PDF — e-book gratuito  
> **Link:** [https://info.deeplearning.ai/machine-learning-yearning-book](https://info.deeplearning.ai/machine-learning-yearning-book)  
> **Por que escolhi:** Escrito por um dos maiores nomes da área, foca em decisões práticas no desenvolvimento de projetos de ML — leitura essencial para quem quer ir além da teoria.

---

### Fonte 3 — Attention Is All You Need (Vaswani et al., 2017)
> **Tipo:** Paper científico em PDF (acesso aberto)  
> **Link:** [https://arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762)  
> **Por que escolhi:** O artigo que introduziu a arquitetura Transformer — a base de todos os LLMs modernos (GPT, Gemini, Claude, etc.). Entender este paper é fundamental.

---

### Fonte 4 — Prompt Engineering Guide (DAIR.AI)
> **Tipo:** Documentação técnica aberta (web + PDF)  
> **Link:** [https://www.promptingguide.ai/](https://www.promptingguide.ai/)  
> **Por que escolhi:** Guia prático e atualizado sobre técnicas de prompt engineering — diretamente aplicável ao uso do NotebookLM e outras ferramentas de IA generativa.

---

### Fonte 5 — Google — Introdução ao Machine Learning (Crash Course)
> **Tipo:** Material didático online (acesso gratuito)  
> **Link:** [https://developers.google.com/machine-learning/crash-course](https://developers.google.com/machine-learning/crash-course)  
> **Por que escolhi:** Didática visual e progressiva, ideal para solidificar conceitos de gradiente descendente, overfitting, métricas de avaliação e redes neurais.

---

## 🧪 Engenharia de Prompts e Cicatrizes

Esta seção documenta o **processo real** de interação com o NotebookLM — incluindo os prompts que funcionaram, os que falharam, e o que aprendi com cada tentativa.

---

### 🔹 Iteração 1 — Prompt Amplo (Não Recomendado)

**Prompt testado:**
```
Me explique Machine Learning.
```

**Resultado obtido:**  
Resposta genérica, longa e sem foco. O NotebookLM trouxe informações das 5 fontes de forma misturada, sem hierarquia conceitual. Difícil de usar para estudo.

**❌ Problema identificado:** Prompt sem escopo e sem estrutura de saída definida. A IA não sabe o que você já sabe nem o que você precisa.

**✅ Lição aprendida:** Sempre delimite o escopo, o nível de profundidade e o formato esperado da resposta.

---

### 🔹 Iteração 2 — Prompt com Contexto e Formato (Melhorado)

**Prompt testado:**
```
Com base nas fontes carregadas, explique os 3 principais tipos de 
aprendizado de máquina (supervisionado, não supervisionado e por reforço) 
em até 5 linhas cada, com um exemplo prático para cada tipo.
```

**Resultado obtido:**  
Resposta clara, estruturada e com referências citadas das fontes. O NotebookLM apontou exatamente quais trechos dos documentos embasavam cada definição.

**✅ O que funcionou:** Especificar o número de itens, o limite de linhas e pedir exemplos práticos forçou a IA a ser objetiva e didática.

---

### 🔹 Iteração 3 — Prompt de Comparação (Avançado)

**Prompt testado:**
```
Compare a arquitetura Transformer (paper Vaswani et al.) com redes neurais 
recorrentes (RNNs) em termos de: paralelismo, memória de longo prazo e 
eficiência computacional. Use uma tabela comparativa.
```

**Resultado obtido:**  
Tabela bem estruturada com 3 colunas e referências diretas ao paper "Attention Is All You Need". A resposta destacou o mecanismo de self-attention como diferencial.

**⚠️ Dificuldade encontrada:** O NotebookLM teve dificuldade em quantificar "eficiência computacional" sem dados numéricos nas fontes. Precisei reformular para: *"descreva qualitativamente as vantagens em termos de eficiência"*.

**✅ Lição aprendida:** Quando a pergunta exige dados quantitativos não presentes nas fontes, reformule para análise qualitativa ou forneça a métrica desejada explicitamente.

---

### 🔹 Iteração 4 — Prompt de Síntese para Revisão

**Prompt testado:**
```
A partir de todas as fontes carregadas, gere um guia de revisão rápida 
(no estilo "flashcard") com os 10 conceitos mais importantes de Machine 
Learning. Para cada conceito: nome do conceito, definição em 1 frase, 
e uma analogia do mundo real.
```

**Resultado obtido:**  
Lista excelente, com analogias criativas (ex: *"Overfitting é como decorar as respostas da prova em vez de aprender a matéria"*). Citou as fontes para cada conceito.

**✅ Destaque:** O formato "flashcard" com analogias é uma das melhores estratégias para estudo ativo — altamente recomendado.

---

### 🔹 Iteração 5 — Troubleshooting: Resposta com Alucinação

**Prompt testado:**
```
Quais são os autores do paper sobre Transformers e em que ano foi publicado?
```

**Resultado obtido (com problema):**  
O NotebookLM citou corretamente Vaswani et al. e o ano 2017, mas em uma segunda tentativa adicionou um co-autor inexistente na lista original — comportamento de alucinação.

**❌ Problema identificado:** Mesmo com fontes carregadas, o modelo pode misturar informações das fontes com seu conhecimento pré-treinado.

**✅ Solução aplicada:** Adicionei ao prompt: *"Responda APENAS com base nos documentos carregados. Se a informação não estiver nas fontes, diga explicitamente."* — o que eliminou a alucinação.

**💡 Regra de ouro:** Para fatos verificáveis (autores, datas, métricas), sempre instrua o modelo a citar a fonte exata e a não extrapolar.

---

## 📖 Miniguia de Estudo — Entrega Final

### 📝 Resumos Estruturados

---

#### Módulo 1 — Fundamentos de Machine Learning

**O que é Machine Learning?**  
Machine Learning é um subcampo da IA em que sistemas aprendem padrões a partir de dados, sem serem explicitamente programados para cada tarefa. Em vez de regras fixas, o modelo ajusta seus parâmetros internos para minimizar erros em um conjunto de exemplos.

**Os 3 paradigmas principais:**

| Tipo | Definição | Exemplo Prático |
|------|-----------|-----------------|
| **Supervisionado** | Aprende com pares (entrada → saída esperada) | Classificar e-mails como spam ou não-spam |
| **Não Supervisionado** | Encontra padrões sem rótulos | Segmentar clientes por comportamento de compra |
| **Por Reforço** | Agente aprende por tentativa, erro e recompensa | AlphaGo aprendendo a jogar xadrez |

**Conceitos-chave do ciclo de ML:**
- **Treinamento:** fase em que o modelo aprende com os dados
- **Validação:** ajuste de hiperparâmetros sem usar dados de teste
- **Teste:** avaliação final em dados nunca vistos
- **Overfitting:** modelo memoriza o treino mas falha no mundo real
- **Underfitting:** modelo é simples demais para capturar os padrões

---

#### Módulo 2 — Redes Neurais e Deep Learning

**Neurônio artificial:** unidade básica que recebe entradas, aplica pesos, soma e passa por uma função de ativação (ReLU, sigmoid, tanh).

**Por que "deep"?** Deep Learning usa redes com muitas camadas ocultas — cada camada aprende representações progressivamente mais abstratas (pixels → bordas → formas → objetos).

**Gradiente Descendente:** algoritmo de otimização que ajusta os pesos na direção que reduz o erro. A taxa de aprendizado (learning rate) controla o tamanho de cada passo.

**Backpropagation:** mecanismo que calcula o gradiente do erro em relação a cada peso da rede, propagando o erro da saída até a entrada.

---

#### Módulo 3 — A Revolução Transformer e os LLMs

**O problema das RNNs:** processamento sequencial (lento), dificuldade com dependências de longo prazo.

**A solução: Self-Attention**  
O mecanismo de atenção permite que cada token da sequência "olhe" para todos os outros simultaneamente, ponderando a relevância de cada um. Isso possibilita:
- Processamento paralelo (muito mais rápido)
- Captura de dependências de longa distância
- Escalabilidade para bilhões de parâmetros

**Arquitetura Transformer (simplificada):**
```
Entrada → Embedding + Positional Encoding
         → N × [Multi-Head Attention + Feed Forward + Norm]
         → Saída (próximo token)
```

**De Transformer para LLM:**  
Modelos como GPT, Claude e Gemini são Transformers treinados em trilhões de tokens de texto. O objetivo de pré-treino é simples: **prever o próximo token**. Essa tarefa aparentemente simples força o modelo a aprender gramática, fatos, raciocínio e até código.

---

#### Módulo 4 — Prompt Engineering na Prática

**Por que prompts importam?**  
LLMs são sistemas de completação de texto. A qualidade da saída depende diretamente da qualidade da entrada. Um bom prompt é uma instrução clara, contextualizada e estruturada.

**Técnicas fundamentais:**

| Técnica | Descrição | Quando Usar |
|---------|-----------|-------------|
| **Zero-shot** | Pergunta direta sem exemplos | Tarefas simples e bem definidas |
| **Few-shot** | Fornece 2-5 exemplos antes da pergunta | Quando precisa de formato específico |
| **Chain-of-thought** | Pede ao modelo para raciocinar passo a passo | Problemas complexos, matemática, lógica |
| **Role prompting** | Atribui um papel ao modelo ("Você é um especialista em...") | Respostas especializadas e com mais rigor |
| **Constrained output** | Especifica o formato exato da saída | Tabelas, JSON, listas numeradas |

---

### 📘 Glossário

| Termo | Definição |
|-------|-----------|
| **Agente Inteligente** | Sistema que percebe o ambiente e toma ações para maximizar uma função objetivo |
| **Algoritmo** | Conjunto finito de instruções que resolve um problema |
| **Atenção (Attention)** | Mecanismo que pondera a importância relativa de diferentes partes de uma sequência |
| **Backpropagation** | Algoritmo de cálculo de gradientes para treinar redes neurais |
| **Batch** | Subconjunto de dados usados em uma iteração de treinamento |
| **Benchmark** | Conjunto padronizado de tarefas para avaliar e comparar modelos |
| **BERT** | Modelo Transformer bidirecional do Google; base para tarefas de NLP |
| **Classificação** | Tarefa de ML que atribui uma categoria a uma entrada |
| **Dataset** | Conjunto de dados estruturado usado para treinar ou avaliar modelos |
| **Deep Learning** | Subconjunto de ML usando redes neurais com múltiplas camadas |
| **Embedding** | Representação vetorial densa de objetos (palavras, imagens) |
| **Epoch** | Uma passagem completa por todo o conjunto de treinamento |
| **Feature** | Variável de entrada usada pelo modelo para fazer previsões |
| **Fine-tuning** | Ajuste de um modelo pré-treinado para uma tarefa específica |
| **Função de Perda (Loss)** | Métrica que quantifica o erro do modelo durante o treinamento |
| **GPT** | Generative Pre-trained Transformer — família de LLMs da OpenAI |
| **Gradiente** | Derivada parcial da função de perda em relação aos pesos do modelo |
| **Hiperparâmetro** | Parâmetro configurado antes do treinamento (ex: learning rate, número de camadas) |
| **Inferência** | Processo de usar um modelo treinado para fazer previsões em novos dados |
| **LLM** | Large Language Model — modelo de linguagem de grande escala |
| **Matriz de Confusão** | Tabela que mostra acertos e erros por classe em classificação |
| **Modelo** | Representação matemática aprendida a partir dos dados |
| **NLP** | Natural Language Processing — Processamento de Linguagem Natural |
| **Overfitting** | Quando o modelo aprende o ruído do treino e não generaliza |
| **Parâmetro** | Peso aprendido pelo modelo durante o treinamento |
| **Pré-treinamento** | Fase inicial de treinamento em grande volume de dados não rotulados |
| **Prompt** | Instrução ou contexto fornecido a um LLM para direcionar sua resposta |
| **RAG** | Retrieval-Augmented Generation — combina recuperação de documentos com geração de texto |
| **Regressão** | Tarefa de ML que prevê um valor contínuo |
| **Rede Neural** | Modelo inspirado no cérebro humano com neurônios artificiais interconectados |
| **ReLU** | Rectified Linear Unit — função de ativação mais comum em redes profundas |
| **Self-Attention** | Mecanismo que relaciona cada posição de uma sequência com todas as outras |
| **Token** | Unidade básica de texto processada por LLMs (pode ser palavra, sílaba ou caractere) |
| **Transfer Learning** | Reutilização de um modelo treinado em uma tarefa para outra tarefa relacionada |
| **Transformer** | Arquitetura de rede neural baseada em mecanismo de atenção (Vaswani et al., 2017) |
| **Underfitting** | Quando o modelo é simples demais para capturar os padrões dos dados |
| **Validação Cruzada** | Técnica para avaliar modelos dividindo os dados em múltiplos subconjuntos |
| **Vetor** | Representação numérica multidimensional de dados |

---

### ♻️ Prompts Reutilizáveis

Estes prompts foram testados e refinados ao longo deste projeto. Copie, adapte e use em suas futuras revisões no NotebookLM ou em qualquer LLM.

---

#### 🔁 Para Geração de Resumos

```
Com base nas fontes carregadas, crie um resumo estruturado sobre [TÓPICO].
O resumo deve ter:
- Uma definição em 2 frases
- Os 3 pontos principais (com marcadores)
- Uma analogia do mundo real para facilitar a memorização
- Uma aplicação prática no mercado de trabalho
```

---

#### 🔁 Para Criação de Flashcards

```
Gere 10 flashcards de revisão sobre [TÓPICO] com base nas fontes.
Formato para cada card:
FRENTE: [conceito ou pergunta]
VERSO: [definição ou resposta em até 2 linhas]
ANALOGIA: [comparação com algo do cotidiano]
FONTE: [qual documento embasou esse card]
```

---

#### 🔁 Para Comparação de Conceitos

```
Compare [CONCEITO A] e [CONCEITO B] com base nas fontes carregadas.
Use uma tabela com as colunas: Critério | [Conceito A] | [Conceito B]
Inclua pelo menos 5 critérios de comparação relevantes.
Ao final, adicione uma recomendação: quando usar cada um?
```

---

#### 🔁 Para Revisão Ativa (Perguntas e Respostas)

```
Crie um quiz de revisão com 10 perguntas sobre [TÓPICO] em formato:
- 5 perguntas de múltipla escolha (4 alternativas, 1 correta)
- 3 perguntas de verdadeiro ou falso (com justificativa)
- 2 perguntas dissertativas curtas
Baseie todas as perguntas nas fontes carregadas.
```

---

#### 🔁 Para Mapa Mental em Texto

```
Com base nas fontes, crie um mapa mental textual sobre [TÓPICO].
Use a seguinte hierarquia:
TEMA CENTRAL
├── Subtema 1
│   ├── Conceito 1.1
│   └── Conceito 1.2
├── Subtema 2
│   ├── Conceito 2.1
│   └── Conceito 2.2
└── Subtema 3
```

---

#### 🔁 Para Identificar Lacunas de Conhecimento

```
Analise as fontes carregadas sobre [TÓPICO] e identifique:
1. Os 3 conceitos mais fundamentais (base obrigatória)
2. Os 3 conceitos intermediários (próximo passo)
3. Os 3 conceitos avançados (aprofundamento futuro)
4. Quais tópicos importantes NÃO estão cobertos pelas fontes atuais?
```

---

#### 🔁 Para Aplicações Práticas no Mercado

```
Com base nas fontes sobre [TÓPICO], descreva 5 aplicações práticas 
no mercado de trabalho atual. Para cada aplicação:
- Nome da aplicação / caso de uso
- Área ou setor de atuação
- Como [TÓPICO] resolve o problema
- Ferramentas ou tecnologias comumente associadas
```

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **[Google NotebookLM](https://notebooklm.google.com/)** — Criação do caderno temático e interação com as fontes
- **[GitHub](https://github.com/)** — Versionamento e documentação do projeto
- **Markdown** — Formatação da documentação

---

## 📌 Considerações Finais

Este projeto reforçou uma lição fundamental: **a qualidade do aprendizado com IA depende diretamente da qualidade das perguntas que fazemos**. Prompt engineering não é apenas uma habilidade técnica — é uma forma de pensar com clareza sobre o que sabemos, o que precisamos saber e como estruturamos o conhecimento.

O NotebookLM se mostrou especialmente poderoso por **citar as fontes de cada resposta**, o que permite verificar e aprofundar qualquer informação. Isso transforma a ferramenta em um parceiro de estudo ativo, não apenas um gerador de resumos passivo.

---

## 👤 Autor

Feito por: Lucas Pereira Dos Santos, para o Desafio de Projeto da **[DIO — Digital Innovation One](https://www.dio.me/)**

---

*⭐ Se este repositório foi útil para você, considere deixar uma estrela!*
