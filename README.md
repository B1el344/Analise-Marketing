# **Ánalise de Marketing**
## Problema de négocio:
Este estudo busca responder como características demográficas, canais de venda e campanhas influenciam o gasto total do cliente, além de prever esse gasto para apoiar decisões estratégicas de marketing.
* Dessa forma, busca-se elucidar o departamento de Marketing acerca das seguintes questões:
    1. Qual o impacto que cada característica do cliente tem sobre os gastos?
        1.1 Totais
        1.2 Por Categoria
    2. Há como estabelecer uma previsão, dadas as características do consumidor, do quanto será o seu gasto total?
    3. Qual o perfil de cliente em cada meio de canais de vendas.
    4. As campanhas de vendas foram efetivas? Qual delas foi a mais e a menos efetiva?
## Bibliotecas utilizadas: pandas, matplotlib, seaborn, sklearn, statsmodels
## Principais Insights:
* Concluímos que a maior parte dos nossos clientes são pessoas com Graduação, da geração X e Baby Boomers, Solteiros e sem filhos ou adolescentes em casa e localizados nos Estados Unidos da América. Tal informação pode orientar as campanhas de marketing futuras, para a criação de personas.
* O público com maior gasto total na loja é composto por pessoas com Curso Superior e com rendas anuais altas, sendo assim um público com ticket mais alto que pode maximizar receita de futuras campanhas de marketing.
* Os maiores segmentos de clientes da nossa loja se encontram, pela ordem de quantidade, em: Platinum, Bronze, Gold e Silver. Com o Segmento Platinum figurando em um gasto médio total muito à frente de outros segmentos.
* A maioria dos nossos clientes prefere comprar por Loja ou Cátalogo. O que implica em mantermos estratégias de jornadas do cliente robustas e eficazes, bem como consultores de vendas competentes, uma vez que os nossos consumidores preferem ter em algum momento contato com os mesmos.
* A Campanha 1 foi efetiva para atrair parte dos consumidores do segmento Bronze. A campanha 2 é para atrair clientes do segmento Gold. Com as campanhas 3 e 4 atraindo um número alto de clientes do segmento Platinum.
* O Segmento Silver foi o que mais realizou compras com desconto
* A média de dias sem compra na base de clientes é de cerca de 44 dias.

Dessa forma, é orientado ao Marketing. O foco no segmento Platinum para captação de receitas maiores, uma vez que tais clientes são a maioria, bem como possuem um ticket médio maior. Além de eles se mostrarem mais propensos às campanhas. Ademais, estabelecer e continuamente aprimorar a jornada do cliente devido à predisposição de nossos clientes por comprar com consultores de vendas. Também devem ser instruídas algumas características da  persona de nosso cliente que compõem pessoas da geração X ou Baby Boomer, solteiros, sem filhos ou adolescentes em casa e com Curso Superior (Graduação) em sua maioria. Ademais, foi constatado que um dos fatores mais importantes para o gasto total do cliente na loja é justamente seu salário anual, com ambos possuindo uma correlação forte e positiva.
## Apresentação Executiva:
Foi criado um relatório em formato HTML, cuja a função é esconder o código e garantir uma visualização fácil e atrativa para gerentes de marketing, cuja não estão interresados no código em si, bem como garante o compartilhamento por email sem necessitar um interpretador Python dos gerentes. O relatório foi criado utilizando a ferramenta Quarto.
## Notas Metodológicas:
* **Testes de Hipotése:** Devido ao tamanho da amostra e a diferença entre as magnitudes visuais das diferenças médias optou-se pela análise direta do tamanho do efeito em detrimento de teste de hipóteses formais (ANOVA), que podem apontar significância estatística mesmo para diferenças irrelevantes para o négocio
* **Modelo Preditivo:** Apesar de o modelo não se mostrar eficiente para a predição exata, o mesmo se demonstrou útil para analisar os *drives* do négocio.
## Segmentação dos Clientes:
<img width="1190" height="690" alt="Clusters Marketing" src="https://github.com/user-attachments/assets/eda731dd-1bc4-478d-9be2-5da5e5cb22be" />
<img width="1362" height="196" alt="Tabela Segmentação" src="https://github.com/user-attachments/assets/66513dc8-c119-4688-a1a3-a6805ad8f853" />
