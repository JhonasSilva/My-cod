# Análise de Vendas — Projeto de Data Analytics

Este projeto apresenta uma análise exploratória de dados (EDA) aplicada a um conjunto de dados de comportamento de compra de clientes.  
O objetivo é responder a **8 perguntas de negócio** utilizando Python, Pandas, Matplotlib e técnicas de análise descritiva.

A análise foi desenvolvida em um notebook Google Colab e organizada neste repositório para fins de estudo e portfólio.

---

# Arquivos do repositório

- **Analise_vendas.ipynb** — Notebook principal contendo todo o código, análises, gráficos e conclusões.

---

# Objetivo do projeto

Responder perguntas de negócio relacionadas ao comportamento de compra de clientes, identificando:

- categorias mais lucrativas  
- ticket médio  
- impacto de assinatura  
- métodos de pagamento mais usados  
- relação entre desconto e valor gasto  
- tipos de envio mais escolhidos  
- Estados com maior faturamento  
- relação entre idade e gasto  

A análise possibilita entender padrões importantes para estratégias comerciais, marketing e operação logística.

---

# Tecnologias utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab**

---

##  Perguntas de Negócio Respondidas

### **1. Qual categoria gera o maior faturamento total?**
A categoria que gera o maior faturamento é **Clothing**, com **US$ 104.264**.  
Essa categoria concentra o maior volume financeiro acumulado, destacando-se como a principal fonte de receita.

---

### **2. Qual é o ticket médio dos clientes?**
O ticket médio é de **US$ 59.76**, obtido dividindo o faturamento total pelo número de compras.  
Isso representa quanto, em média, cada cliente gasta por transação.

---

### **3. Clientes assinantes (“Subscription Status = Yes”) gastam mais do que não-assinantes?**
Surpreendentemente, **não-assinantes** gastam mais no total:

- Não assinantes: **US$ 170.436**
- Assinantes: **US$ 62.645**

Os não assinantes representam a maior parte do faturamento do período analisado.

---

### **4. Qual método de pagamento é o mais utilizado?**
O método mais utilizado é **PayPal**.  
Essa conclusão foi obtida através da contagem da quantidade de transações por método de pagamento.

---

### **5. Compras com desconto têm valor maior ou menor que compras sem desconto?**
- Com desconto: **US$ 99.411** (total)
- Sem desconto: **US$ 133.670**

Compras com desconto tendem a ter valores menores — o que indica que os descontos são aplicados em produtos mais baratos ou compras de baixo valor.

---

### **6. Qual tipo de envio (“Shipping Type”) é o mais escolhido?**
O método de envio mais escolhido é **Free Shipping**, sendo o preferido pela maioria dos clientes.

---

### **7. Qual Estado (“Location”) mais gasta?**
O Estado com maior valor total gasto é **Montana**.  
Essa região apresentou o maior faturamento somado no período analisado.

---

### **8. Existe relação entre idade e valor gasto?**
Não foi identificada relação significativa entre idade e valor gasto.

- As médias de gasto por faixa etária são muito próximas.
- O desvio padrão (~23) é muito maior que as diferenças entre faixas.
- Portanto, **idade não influencia o gasto médio**.

---

## Conclusões Gerais

- O faturamento está concentrado principalmente na categoria **Clothing**.  
- O ticket médio é relativamente baixo (**US$ 59.76**).  
- Não-assinantes geram mais receita do que assinantes.  
- **PayPal** é o método preferido de pagamento.  
- Descontos não aumentam o valor gasto — pelo contrário, aparecem em compras menores.  
- **Free Shipping** é o método de envio mais utilizado.  
- **Montana** lidera o ranking de estados com maior gasto.  
- A **idade não é um fator relevante** para definir quanto um cliente gasta.

---

## Sobre o Projeto

Este trabalho foi desenvolvido como estudo de análise de dados, com foco em prática real, documentação e interpretação de resultados.  
Serve como um dos projetos iniciais do portfólio do autor.
