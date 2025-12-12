# 📊 Projeto Alura Store: Análise Estratégica de Vendas

**Analista de Dados:** Vanessa Faria
**Ferramentas:** Python, Pandas, Matplotlib, Seaborn
**Status:** Concluído ✔️

---

## 🎯 Objetivo do Projeto
O objetivo deste desafio foi analisar os dados de vendas, logística e satisfação de 4 lojas da rede **Alura Store** para auxiliar o proprietário (Sr. João) a tomar uma decisão estratégica: **identificar qual loja possui o menor desempenho e deve ser vendida para gerar capital de investimento.**

---

## 🔍 Análise Exploratória e Métricas

Utilizando a biblioteca **Pandas** para manipulação de dados e **Matplotlib** para visualização, analisamos quatro pilares fundamentais:

### 1. Faturamento (Receita) 💰
O indicador financeiro foi o fator decisivo na comparação:
* **Loja 1:** Apresentou o **maior faturamento** da rede, consolidando-se como a líder de vendas.
* **Loja 4:** Apresentou o **menor faturamento total**, ficando significativamente abaixo das demais filiais.

### 2. Logística e Frete 🚚
Analisamos a relação entre o custo de envio e o volume de vendas:
* Curiosamente, a **Loja 4** possui o **menor custo médio de frete**.
* Teoricamente, um frete barato deveria atrair mais clientes. O fato de a Loja 4 ter frete barato e *ainda assim* vender pouco indica uma **baixa atratividade dos produtos ou ineficiência comercial**.

### 3. Satisfação do Cliente (Avaliações) ⭐
* A média de avaliações se manteve estável em torno de **4.0** para todas as unidades.
* A **Loja 1** teve uma nota levemente inferior (3.98), mas isso não impactou seu alto volume de vendas.
* A **Loja 4** manteve a nota 4.0, provando que o problema não é o atendimento, mas sim a conversão de vendas.

---

## 📍 BÔNUS: Análise de Desempenho Geográfico

Realizamos um estudo extra de **Dispersão Geográfica (Latitude x Longitude)** para entender a abrangência das lojas.

**Insights do Mapa:**
* A análise revelou que a **Loja 4**, apesar de faturar como uma loja pequena, possui uma operação logística espalhada por todo o território (similar à Loja 1).
* Isso aponta para uma **ineficiência logística**: a loja arca com a complexidade de entregar em locais distantes, mas não tem o volume de vendas massivo da Loja 1 para justificar essa operação.

---

## 💡 Conclusão e Recomendação Final

Com base na análise de dados quantitativa e visual, a recomendação estratégica para o Sr. João é:

### 🛑 **VENDER A LOJA 4**

**Justificativa:**
A unidade apresenta o pior desempenho do grupo, caracterizado por:
1.  **Baixo Retorno Financeiro:** É a lanterna em faturamento.
2.  **Ineficiência Comercial:** Mesmo com fretes competitivos (baratos), não consegue converter vendas.
3.  **Complexidade sem Retorno:** Opera em território nacional (conforme análise geográfica) sem ter a densidade de vendas necessária para sustentar essa operação.

A venda desta unidade permitirá redirecionar capital e foco para as Lojas 1, 2 e 3, que demonstram maior solidez e potencial de crescimento.

---
