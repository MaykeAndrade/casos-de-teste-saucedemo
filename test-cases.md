# 🧪 Casos de Teste - SauceDemo

## 📌 CT-001 — Login com sucesso

**Pré-condição:** Usuário cadastrado

**Passos:**

1. Acessar o site
2. Inserir usuário válido
3. Inserir senha válida
4. Clicar em "Login"

**Resultado esperado:**
Usuário deve acessar a página de produtos

**Prioridade:** Alta
**Tipo de teste:** Funcional

---

## 📌 CT-002 — Login com senha inválida

**Pré-condição:** Usuário cadastrado

**Passos:**

1. Acessar o site
2. Inserir usuário válido
3. Inserir senha inválida
4. Clicar em "Login"

**Resultado esperado:**
Sistema deve exibir mensagem de erro

**Prioridade:** Alta
**Tipo de teste:** Negativo

---

## 📌 CT-003 — Adicionar produto ao carrinho

**Pré-condição:** Usuário logado

**Passos:**

1. Acessar lista de produtos
2. Clicar em "Add to Cart"

**Resultado esperado:**
Produto deve ser adicionado ao carrinho

**Prioridade:** Alta
**Tipo de teste:** Funcional

---

## 📌 CT-004 — Remover produto do carrinho

**Pré-condição:** Produto já adicionado

**Passos:**

1. Acessar carrinho
2. Clicar em "Remove"

**Resultado esperado:**
Produto deve ser removido

**Prioridade:** Média
**Tipo de teste:** Funcional

---

## 📌 CT-005 — Finalizar compra

**Pré-condição:** Produto no carrinho

**Passos:**

1. Acessar carrinho
2. Clicar em checkout
3. Preencher dados
4. Finalizar compra

**Resultado esperado:**
Compra deve ser concluída com sucesso

**Prioridade:** Alta
**Tipo de teste:** Funcional
