# 📗 Unidade 2: Lógica Proposicional e Tabelas Verdade  
## 8️⃣ Aula 8: Aplicações da Tabela Verdade em Expressões Complexas

> 🧠 **"A lógica não é apenas uma ferramenta de raciocínio; ela é a ponte entre o que parece confuso e o que se torna compreensível."**

---

## 🎯 Objetivos da Aula

Ao final desta aula, você será capaz de:

- ✅ Construir tabelas verdade para expressões com múltiplos conectivos lógicos;
- ✅ Aplicar **leis fundamentais da lógica proposicional** para simplificação de expressões;
- ✅ Entender e utilizar as **Leis de De Morgan** com clareza e precisão;
- ✅ Validar argumentos lógicos por meio da tabela verdade;
- ✅ Compreender quando uma expressão representa **tautologia**, **contradição** ou **contingência** mesmo em estruturas mais complexas.

---

## 📘 8.1. Tabelas Verdade para Expressões com Múltiplos Conectivos

À medida que adicionamos mais proposições e conectivos lógicos a uma expressão, a construção da **tabela verdade** se torna mais detalhada, porém segue os mesmos princípios já aprendidos.

### 🔹 Exemplo 1:  
Construa a tabela verdade da proposição composta:  
**(¬p ∨ q) ∧ (r → p)**

- Variáveis: `p`, `q`, `r` → Total de linhas: 2³ = 8
- Estrutura: deve conter colunas intermediárias para `¬p`, `¬p ∨ q`, `r → p` e o resultado final.

Essa abordagem ajuda o aluno a entender **como as colunas intermediárias servem de apoio** para alcançar o valor lógico final da proposição composta.

---

## ⚖️ 8.2. Leis da Lógica Proposicional

Assim como as **regras da matemática** ajudam a simplificar expressões numéricas, as **leis da lógica** nos permitem **transformar, reduzir ou provar equivalências** entre proposições. Abaixo, listamos as principais:

### ✅ **Leis Fundamentais**

| 🧠 Lei                  | 📌 Exemplo                         | 🔄 Equivalente                        |
| ---------------------- | --------------------------------- | ------------------------------------ |
| Identidade             | `p ∧ V ≡ p` / `p ∨ F ≡ p`         | Proposição mantém seu valor          |
| Dominação (ou Nula)    | `p ∧ F ≡ F` / `p ∨ V ≡ V`         | Conectivo é dominado por V ou F      |
| Dupla Negação          | `¬(¬p) ≡ p`                       | Negação dupla anula o efeito         |
| Idempotência           | `p ∧ p ≡ p` / `p ∨ p ≡ p`         | Repetição não altera valor lógico    |
| Inversão (Contradição) | `p ∧ ¬p ≡ F` / `p ∨ ¬p ≡ V`       | Proposição e sua negação             |
| Comutatividade         | `p ∧ q ≡ q ∧ p` / `p ∨ q ≡ q ∨ p` | Ordem não altera o resultado         |
| Associatividade        | `(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)`       | Agrupamento pode mudar               |
| Distributividade       | `p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)` | Semelhante à distributiva matemática |

---

### 🧠 **Leis de De Morgan**

As **Leis de De Morgan** são fundamentais para a **simplificação de negações** que envolvem conjunções (∧) e disjunções (∨). Elas afirmam que:

| Proposição original | Equivalência pela Lei de De Morgan |
| ------------------- | ---------------------------------- |
| ¬(p ∧ q)            | ≡ ¬p ∨ ¬q                          |
| ¬(p ∨ q)            | ≡ ¬p ∧ ¬q                          |

💡 **Aplicação prática:** Ao aplicar uma negação sobre uma proposição composta, **invertemos o conectivo** e **negamos cada proposição**.

#### 🔸 Exemplo:
> ¬(Está quente ∨ Está úmido) ≡ Não está quente ∧ Não está úmido

Essas leis são amplamente utilizadas na **programação**, especialmente na negação de condições compostas.

---

## 🔍 8.3. Validação de Argumentos Lógicos

Um **argumento lógico** é um conjunto de premissas que levam a uma conclusão. Para determinar se ele é **válido**, podemos usar a tabela verdade para verificar **se toda vez que as premissas forem verdadeiras, a conclusão também será verdadeira**.

### ✅ Estrutura formal:

Sejam:
- **Premissa 1:** `p → q`
- **Premissa 2:** `p`
- **Conclusão:** `q`

**Argumento completo:**  
((p → q) ∧ p) → q

### 📊 Procedimento:
1. Construa a tabela com `p` e `q` (4 linhas)
2. Calcule:
   - `p → q`
   - `(p → q) ∧ p`
   - `((p → q) ∧ p) → q`
3. Analise a última coluna:  
   - Se **sempre for V**, o argumento é **válido** (tautologia).  
   - Se houver **alguma linha com F**, o argumento é **inválido**.

---

## 🧮 8.4. A Importância das Tabelas Verdade em Expressões Complexas

Mesmo que pareçam trabalhosas, as tabelas verdade são uma **ferramenta visual poderosa** para entender como **expressões complexas se comportam** logicamente. Elas ajudam a:

- 📌 Confirmar **equivalências lógicas**;
- 🔍 Identificar **erros em argumentos**;
- ⚙️ **Otimizar estruturas de decisão** em algoritmos e fluxos de programas;
- 🧠 Desenvolver **clareza no raciocínio lógico e matemático**.

---

## 📢 Conclusão

Nesta aula, vimos como as tabelas verdade são utilizadas para **analisar e validar expressões lógicas mais complexas**, e como as **leis da lógica**, especialmente as **Leis de De Morgan**, são ferramentas indispensáveis para transformar e interpretar proposições.

Ao dominar essas técnicas, você será capaz de:
- 🔓 Compreender expressões com múltiplos conectivos;
- 💡 Verificar a validade lógica de argumentos complexos;
- 🧠 Aplicar o raciocínio formal em computação, matemática e até na vida cotidiana.

🚀 **Na próxima aula, integraremos os 4 Pilares do Pensamento Computacional com a Lógica Proposicional**, mostrando como abstração, padrões, algoritmos e decomposição se relacionam com o raciocínio lógico formal.

---