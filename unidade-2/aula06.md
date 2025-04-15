# 📗 Unidade 2: Lógica Proposicional e Tabelas Verdade  
## 6️⃣ Aula 6: Introdução à Lógica Proposicional

> 🧠 **"Pensar logicamente é como afiar a lâmina da razão: quanto mais afiada, mais clara é a compreensão do mundo."**

---

## 🎯 Objetivos da Aula

Ao final desta aula, você será capaz de:

- ✅ Entender o que é **lógica proposicional** e reconhecer sua importância no raciocínio lógico;
- ✅ Compreender o conceito fundamental de **proposição** e diferenciar de outros tipos de sentenças;
- ✅ Identificar os **principais conectivos lógicos** e suas aplicações;
- ✅ Relacionar a lógica proposicional com **situações reais e algoritmos computacionais**.

---

## 📘 6.1. O Que é Lógica Proposicional?

A **Lógica Proposicional** é um ramo da lógica matemática que estuda **as proposições** e as **relações lógicas** que podem ser estabelecidas entre elas por meio de **conectivos lógicos**. Seu foco está **na forma dos argumentos**, e não no seu conteúdo.

Essa lógica é usada para:
- Avaliar se um raciocínio é **válido** ou **inválido**;
- Determinar **valores de verdade** de frases compostas;
- Apoiar **decisões computacionais**, **provas matemáticas**, **análises filosóficas** e muito mais.

### 🧠 Pensamento Computacional e Lógica
A lógica proposicional é uma ferramenta fundamental no Pensamento Computacional. Ela nos ajuda a:

- Construir **algoritmos com condições**;
- Avaliar **verdadeiro ou falso** em tomadas de decisão;
- Garantir que os passos de um código **sigam uma lógica válida**;
- Automatizar tarefas com base em **decisões condicionais**.

---

### 🖥 Aplicações da Lógica Proposicional

| 🌐 Área                    | 📌 Aplicação                                                  |
| ------------------------- | ------------------------------------------------------------ |
| 💻 Computação              | Condições em programação (ex: `if`, `else`)                  |
| 🧮 Matemática              | Provas lógicas e deduções com sentenças matemáticas          |
| 📚 Filosofia               | Análise de argumentos e validade de raciocínios              |
| 🤖 Inteligência Artificial | Representação e avaliação de decisões lógicas de um sistema de IA |
| ⚖ Direito                 | Avaliação de argumentos jurídicos e contradições             |

---

## 🧩 6.2. O Que é uma Proposição?

### 🟩 **Definição Formal**
Uma **proposição** é um **enunciado declarativo** que pode ser **classificado como verdadeiro (V)** ou **falso (F)**, mas **nunca os dois ao mesmo tempo**.

🔍 Uma proposição **afirma algo sobre o mundo**, e essa afirmação deve poder ser **testada** para verificar se é **verdadeira ou falsa**.

### ✅ Exemplos de Proposições:
| Enunciado                       | É proposição? | Valor lógico possível |
| ------------------------------- | ------------- | --------------------- |
| "A Terra gira em torno do Sol." | ✅ Sim         | Verdadeiro            |
| "2 é um número par."            | ✅ Sim         | Verdadeiro            |
| "5 é maior que 10."             | ✅ Sim         | Falso                 |

Esses enunciados **podem ser verificados**, e por isso, **são proposições**.

---

### ❌ O que **não é** uma proposição?

Nem todo enunciado é uma proposição. Alguns não podem ser classificados como verdadeiro ou falso. Veja:

| Enunciado              | É proposição? | Justificativa                                   |
| ---------------------- | ------------- | ----------------------------------------------- |
| "Feche a janela!"      | ❌ Não         | É uma ordem, não possui valor lógico            |
| "Como você está hoje?" | ❌ Não         | É uma pergunta                                  |
| "x + 2 = 5"            | ❌ Não         | Sentença aberta: depende do valor de **x**      |
| "Essa frase é falsa."  | ❌ Não         | Paradoxo: não pode ser avaliada de forma lógica |

➡ Sentenças que dependem de variáveis (como x) são chamadas de **sentenças abertas** e só se tornam proposições quando os valores são definidos.

---

## 🧠 6.3. Proposições Simples e Compostas

### 🔹 Proposição Simples
É uma **única afirmação indivisível**. Não possui conectivos lógicos.

📌 *Exemplo:*  
> “O céu está nublado.”

Esta frase afirma algo direto, e pode ser avaliada como verdadeira ou falsa. Não há partes conectadas.

---

### 🔹 Proposição Composta
É formada por **duas ou mais proposições simples**, unidas por **conectivos lógicos**.

📌 *Exemplo:*  
> “O céu está nublado **e** vai chover.”

Essa proposição é composta por:
- p: “O céu está nublado.”
- q: “Vai chover.”

Unidas pelo conectivo **"e" (∧)**.

A validade lógica da frase composta depende dos **valores de verdade de cada parte**.

---

## 🔗 6.4. Conectivos Lógicos Fundamentais

Os **conectivos lógicos** são operadores que ligam proposições e **formam novas proposições compostas**. Eles **alteram ou combinam valores lógicos**.

### 🧮 Principais Conectivos:

| 🔢 Símbolo | Nome Técnico  | Representação Verbal | Significado                                                  |
| --------- | ------------- | -------------------- | ------------------------------------------------------------ |
| ∧         | Conjunção     | “e”                  | Verdadeiro **apenas se ambos forem verdadeiros**             |
| ∨         | Disjunção     | “ou”                 | Verdadeiro se **pelo menos um** for verdadeiro               |
| ¬         | Negação       | “não”                | Inverte o valor lógico (V ↔ F)                               |
| →         | Condicional   | “se... então”        | Falso **apenas se o antecedente for V e o consequente for F** |
| ↔         | Bicondicional | “se, e somente se”   | Verdadeiro se **ambos tiverem o mesmo valor lógico**         |

---

### 🧪 Exemplos Detalhados por Conectivo

#### ✅ **1. Conjunção ( ∧ )**
> “Estudo **e** trabalho.”

📌 Representação: `p ∧ q`  
📊 Verdadeira **somente quando p e q são ambos verdadeiros.**

| p (Estudo) | q (Trabalho) | p ∧ q |
| ---------- | ------------ | ----- |
| V          | V            | V     |
| V          | F            | F     |
| F          | V            | F     |
| F          | F            | F     |

---

#### ✅ **2. Disjunção ( ∨ )**
> “Estudo **ou** descanso.”

📌 Representação: `p ∨ q`  
📊 Verdadeira se **pelo menos uma das partes for verdadeira.**

| p (Estudo) | q (Descanso) | p ∨ q |
| ---------- | ------------ | ----- |
| V          | V            | V     |
| V          | F            | V     |
| F          | V            | V     |
| F          | F            | F     |

---

#### ✅ **3. Negação ( ¬ )**
> “**Não** gosto de matemática.”

📌 Representação: `¬p`  
📊 Inverte o valor lógico de `p`.

| p    | ¬p   |
| ---- | ---- |
| V    | F    |
| F    | V    |

---

#### ✅ **4. Condicional ( → )**
> “**Se** você estudar, **então** passará.”

📌 Representação: `p → q`  
📊 Falsa **apenas quando p é V e q é F**.

| p (Estudar) | q (Passar) | p → q |
| ----------- | ---------- | ----- |
| V           | V          | V     |
| V           | F          | ❌ F   |
| F           | V          | V     |
| F           | F          | V     |

*Essa é a mais "polêmica" das conectivas, pois sua interpretação lógica nem sempre coincide com a intuição natural da linguagem.*

---

#### ✅ **5. Bicondicional ( ↔ )**
> “Você só sai **se, e somente se** terminar o dever.”

📌 Representação: `p ↔ q`  
📊 Verdadeiro quando `p` e `q` possuem o **mesmo valor lógico**.

| p (Saiu) | q (Terminou dever) | p ↔ q |
| -------- | ------------------ | ----- |
| V        | V                  | V     |
| V        | F                  | F     |
| F        | V                  | F     |
| F        | F                  | V     |

---

## 📚 6.5. Conclusão da Aula

A **lógica proposicional** é uma linguagem precisa e poderosa que nos permite **avaliar e construir argumentos de forma estruturada**. Ela está presente tanto na computação quanto nas decisões humanas cotidianas.

- **Proposições** são blocos fundamentais do raciocínio lógico.
- **Conectivos** nos permitem formar frases mais complexas e avaliar diferentes cenários.
- Saber usar essas ferramentas é essencial para **pensar com clareza**, **programar com lógica** e **analisar ideias com critério**.

🚀 **Na próxima aula**, aprenderemos a construir e interpretar a **Tabela Verdade**, uma ferramenta indispensável na lógica proposicional!

---