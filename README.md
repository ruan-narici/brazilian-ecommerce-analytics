# Análise Exploratória do E-commerce Brasileiro 📊💻

Este projeto realiza uma análise exploratória detalhada do e-commerce brasileiro, com foco em dados de vendas, frete, prazos de entrega e avaliações de produtos. Utilizando bibliotecas como **Pandas** e **Matplotlib**, o objetivo é extrair **insights valiosos** sobre o comportamento de compra, desafios logísticos e performance das categorias de produtos.

## Objetivo 🎯
- Quais estados lideram as vendas e as compras.
- Como o frete afeta a avaliação dos produtos.
- Como os prazos de entrega impactam as avaliações.
- Identificação das categorias de produtos mais populares e suas respectivas avaliações.

## Tecnologias Utilizadas ⚙️
- **Python 3**
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib**: Visualização de dados.
- **Google Colab**: Ambiente para execução do código.

## Estrutura do Projeto 📂
1. **Carregamento dos Dados**: Importação e limpeza dos dados do e-commerce.
2. **Análise Exploratória**: Padrões de vendas, frete, entrega e avaliações.
3. **Visualizações**: Gráficos para ilustrar as descobertas.
4. **Conclusões**: Insights sobre o impacto do frete, entrega e categorias de produtos.

## Conclusões 🔍
- **SP** é o estado com maior volume de vendas (**80.728 produtos** vendidos / **R$ 12.771.107,02** faturados).
- **SP** também lidera as compras, seguido do **RJ** (**14.566 produtos** e **R$ 2.633.042,81** gastos).
- Estados como **RR, PB, RO, AC e TO** têm frete acima de **R$ 40,00**, impactando negativamente nas avaliações (**média 3,8 estrelas**).
- **RR, AP e AM** possuem prazos de entrega superiores a **40 dias**, afetando a experiência do cliente.
- Entregas acontecem em média **8 a 10 dias antes** do prazo previsto.
- Categorias que mais venderam: **bed_bath_table**, **health_beauty** e **sports_leisure** (**R$ 335.864.564** faturados, **8,5 dias** de entrega média e **4 estrelas**).
- Categorias mais bem avaliadas: **fashion_childrens_clothes**, **cds_dvds_musicals** e **books_imported** (**4,7 estrelas**, **7 dias** de entrega).
- Categorias com piores avaliações: **security_and_services**, **diapers_and_hygiene** e **office_furniture** (**3,1 estrelas**).

---

Esse projeto foi uma excelente oportunidade para aplicar e expandir meus conhecimentos em análise de dados com Python e Pandas.  
**Avante!** 🚀

🔗 Dataset utilizado: [Brazilian E-commerce Public Dataset - Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
🗺️ Schema de Dados

Abaixo está o diagrama representando a relação entre as principais tabelas utilizadas na análise:

![Schema do Projeto](./src/schema/schema.png)


---
