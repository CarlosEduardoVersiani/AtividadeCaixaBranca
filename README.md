# Teste de Caixa Branca – Análise do Código `User.java`

Este repositório contém a atividade da disciplina **UX/UI e Testes de Software**, referente ao tema **Teste de Caixa Branca**
---

## 📌 1. Código-Fonte Analisado

O código analisado é o método `verificarUsuario()` da classe `User`, responsável por realizar autenticação em um banco MySQL.

O arquivo original foi incluído no repositório e **com comentários adicionais** que explicam cada etapa da execução.

---

## 📌 2. Planilha de Testes (Caixa Branca – Estático)

A planilha criada na etapa anterior encontra-se no repositório com o nome:

➡️ **revisao_codigo.xlsx**

Ela contém:

- Verificação de documentação  
- Nomenclatura  
- Tratamento de NullPointer  
- Tratamento de exceções  
- Aderência à arquitetura  
- Análise de variáveis  
- Indicação dos erros encontrados  
- Orientação das correções  

---

# 🧩 3. Notação do Grafo de Fluxo

```
(1) ──► (2) ──► (3) ──► (4) ──┬──► (5) ──► (7)
                             │
                             └──► (6) ──► (7)
```

---

# 🧩 4. Complexidade Ciclomática

### Método 1 – E – N + 2
- N = 7  
- E = 8  

```
M = 8 – 7 + 2 = 3
```

### Método 2 – Decisões + 1
- If → 1  
- Catch → 1  

```
M = 2 + 1 = 3
```

✔️ **Complexidade Final = 3**

---

# 🧩 5. Caminhos Básicos

### Caminho 1 — Usuário encontrado
```
1 → 2 → 3 → 4(TRUE) → 5 → 7
```

### Caminho 2 — Usuário não encontrado
```
1 → 2 → 3 → 4(FALSE) → 7
```

### Caminho 3 — Exceção
```
1 → 2 → 3 → 6 → 7
```

---





# 📌 6. Autor

**Nome:** Caros Eduardo Versiani de Lima 
**RA:** 248955  


