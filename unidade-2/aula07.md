# 📗 Unidade 2: Lógica Proposicional e Tabelas Verdade  
## 7️⃣ Aula 7: Construção e Interpretação da Tabela Verdade

> 🧠 **"A clareza de um raciocínio depende da transparência de sua estrutura. A tabela verdade é o mapa que revela essa estrutura."**

---

## 🎯 Objetivos da Aula

Ao final desta aula, você será capaz de:

- ✅ Entender a estrutura e função de uma **tabela verdade**;
- ✅ Construir tabelas verdade para proposições simples e compostas;
- ✅ Interpretar os **valores lógicos** atribuídos a diferentes proposições;
- ✅ Identificar **tautologias, contradições e contingências**;
- ✅ Relacionar tabelas verdade à **validação lógica de argumentos**.

---

## 📘 7.1. O Que é uma Tabela Verdade?

A **Tabela Verdade** é uma ferramenta lógica utilizada para representar **todos os possíveis valores de verdade** de uma proposição ou de uma expressão composta. Ela mostra como a **verdade ou falsidade de uma sentença** depende da verdade ou falsidade de suas partes.

Ela é **essencial** no estudo da lógica proposicional porque permite:
- Verificar se uma proposição composta é **sempre verdadeira**, **sempre falsa** ou **variável**;
- Analisar a **validade de argumentos**;
- Automatizar decisões lógicas em **programas e algoritmos**.

---

## 🔢 7.2. Estrutura da Tabela Verdade

A quantidade de **linhas** da tabela depende da **quantidade de proposições simples (variáveis)**:

- 1 proposição → 2 linhas (2¹)
- 2 proposições → 4 linhas (2²)
- 3 proposições → 8 linhas (2³)
- 4 proposições → 16 linhas (2⁴)
- ...

🔍 A cada nova proposição adicionada, **o número de combinações dobra**.

---

### ✅ Exemplo com 1 Proposição (p)

| p    | ¬p   |
| ---- | ---- |
| V    | F    |
| F    | V    |

---

### ✅ Exemplo com 2 Proposições (p ∧ q)

| p    | q    | p ∧ q |
| ---- | ---- | ----- |
| V    | V    | V     |
| V    | F    | F     |
| F    | V    | F     |
| F    | F    | F     |

---

### ✅ Exemplo com 3 Proposições (¬p ∨ (q → r))

| p    | q    | r    | ¬p   | q → r | ¬p ∨ (q → r) |
| ---- | ---- | ---- | ---- | ----- | ------------ |
| V    | V    | V    | F    | V     | V            |
| V    | V    | F    | F    | F     | F            |
| V    | F    | V    | F    | V     | V            |
| V    | F    | F    | F    | V     | V            |
| F    | V    | V    | V    | V     | V            |
| F    | V    | F    | V    | F     | V            |
| F    | F    | V    | V    | V     | V            |
| F    | F    | F    | V    | V     | V            |

📌 Note como a tabela se expande à medida que adicionamos mais operadores.

---

## 🔍 7.3. Construção Passo a Passo

### Etapas para construir uma Tabela Verdade:

1️⃣ **Identifique as proposições simples (variáveis)**  
Exemplo: `p`, `q`, `r`.

2️⃣ **Determine o número de linhas da tabela**  
→ Use `2^n`, onde `n` é o número de proposições simples.

3️⃣ **Preencha as colunas com todas as combinações possíveis de V e F**  
→ Comece com a variável mais à esquerda alternando V e F a cada metade das linhas.

4️⃣ **Adicione colunas intermediárias com os resultados dos conectivos**  
→ Resolva de dentro para fora, respeitando a hierarquia lógica.

5️⃣ **Calcule a coluna final com o resultado da proposição composta**

---

## 🧠 7.4. Determinação da Veracidade: Tautologia, Contradição e Contingência

### 🔹 **Tautologia**
- A proposição composta é **sempre verdadeira**, independentemente dos valores das variáveis.
- Exemplo: `p ∨ ¬p`

| p    | ¬p   | p ∨ ¬p |
| ---- | ---- | ------ |
| V    | F    | V      |
| F    | V    | V      |

📌 Resultado final: **Sempre V → Tautologia**

---

### 🔹 **Contradição**
- A proposição composta é **sempre falsa**.
- Exemplo: `p ∧ ¬p`

| p    | ¬p   | p ∧ ¬p |
| ---- | ---- | ------ |
| V    | F    | F      |
| F    | V    | F      |

📌 Resultado final: **Sempre F → Contradição**

---

### 🔹 **Contingência**
- A proposição é **verdadeira em algumas situações e falsa em outras**.
- Exemplo: `p → q`

| p    | q    | p → q |
| ---- | ---- | ----- |
| V    | V    | V     |
| V    | F    | ❌ F   |
| F    | V    | V     |
| F    | F    | V     |

📌 Resultado final: **Misto → Contingência**

---

## 🖥 Aplicações Computacionais

A tabela verdade está por trás de diversas tecnologias do dia a dia:

| 💻 Aplicação              | 🧠 Como a lógica é usada                             |
| ------------------------ | --------------------------------------------------- |
| Condições de um programa | `if (x > 10 && y < 5)` → Avaliação booleana         |
| Sistemas especialistas   | Tomam decisões baseadas em proposições lógicas      |
| Jogos e IA               | Verificam condições para mover, atacar ou interagir |
| Engenharia de circuitos  | Portas lógicas (AND, OR, NOT) simulam tabelas       |

---

## 📢 Conclusão

A **Tabela Verdade** é uma ferramenta essencial para quem deseja dominar a lógica proposicional. Ela nos permite:

- Ver todas as **possibilidades de verdade** de uma proposição;
- Comprovar se uma ideia é **sempre válida** ou **dependente das condições**;
- Construir **códigos, algoritmos e argumentos sólidos**.

🚀 **Na próxima aula**, vamos aprofundar esse conhecimento, criando **tabelas para expressões mais complexas**, aprendendo as **Leis da Lógica** e explorando **a validação de argumentos** com base nessa estrutura.

---