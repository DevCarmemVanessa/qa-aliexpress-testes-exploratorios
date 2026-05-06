# 📋 Relatório de Testes Exploratórios — AliExpress

## 🎯 Objetivo

Realizar testes exploratórios nas principais funcionalidades do AliExpress, avaliando comportamento do sistema, estabilidade, experiência do usuário e possíveis inconsistências.

# 🔍 Funcionalidades Testadas


## ✅ Busca vazia

### Resultado:
Ao pesquisar sem inserir conteúdo, o sistema redirecionou para a última pesquisa realizada anteriormente.

### Observação:
Nenhuma falha crítica identificada.

---

## ✅ Busca com caracteres especiais

### Entrada utilizada:
@@@@@@@@@@@@@@

### Resultado:
O sistema apresentou sugestões e resultados sem relação clara com os caracteres inseridos.

### Observação:
Possível inconsistência na relevância das sugestões da busca.

---

## ✅ Busca com texto extenso

### Resultado:
O sistema limitou corretamente a quantidade máxima de caracteres no campo de busca.

### Observação:
O sistema manteve estabilidade e não apresentou falhas visuais.

---

## ✅ Cliques rápidos no carrinho

### Resultado:
O sistema respondeu adequadamente às interações rápidas sem inconsistências.

---

## ✅ Filtros combinados

### Resultado:
Os filtros funcionaram corretamente, atualizando os resultados de forma consistente.

---

## ✅ Navegação entre páginas e abas

### Resultado:
O carrinho manteve o estado corretamente durante navegação, atualização da página e troca de abas.

---

## ✅ Compra sem autenticação

### Resultado:
O sistema permitiu adicionar produtos ao carrinho sem login, solicitando autenticação apenas no momento de finalizar a compra.

### Observação:
Comportamento coerente para fluxo de e-commerce.

---

## ✅ Limite de quantidade de produtos

### Resultado:
O sistema respeitou corretamente o limite máximo permitido por produto.

### Observação:
As restrições variaram conforme disponibilidade do item.

---

# 📌 Resultado Geral

Durante os testes realizados, o sistema apresentou comportamento estável e consistente, sem falhas críticas identificadas.

Foram observados possíveis pontos de melhoria relacionados à relevância da busca em entradas inválidas ou sem significado.
