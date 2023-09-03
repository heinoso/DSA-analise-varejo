# Curso: `Fundamentos da linguagem Python para Data Science` 
## Plataforma: `Data Science Academy`

## Objetivo: dado um dataset contendo informações de uma empresa da área do varejo, fazer a análise desses dados afim de responder 10 perguntas de negócio. Sendo elas:

1. Qual cidade com maior valor de venda de produtos da categoria 'Office Supplies'?
2. Qual o total de vendas por data do pedido?
3. Qual o total de vendas por estado?
4. Quais são as 10 cidades com maior total de vendas?
5. Qual segmento teve o maior total de vendas?
6. Qual o total de vendas por segmento e por ano?
7. Dado um critério para desconto, quantas vendas receberiam 15% de desconto?
8. Qual seria a média do valor de venda antes e depois do desconto?
9. Qual a média de vendas por segmento, por ano e por mês?
10. Qual o total de vendas por categoria e subcategoria, considerando somente as top 12 subcategorias? 


## O dataset, localizado na pasta 'dados' desde repositório, contém as colunas:

- Colunas presentes no dataset: 
    - ID_Pedido
    - Data_Pedido
    - ID_Cliente
    - Segmento
    - Pais
    - Cidade
    - Estado
    - ID_Produto
    - Categoria
    - SubCategoria
    - Valor_Venda

## Requirements 
- Para desenvolver o projeto foram utilizadas as bibliotecas *numpy*, *pandas*, *pyplot*, *seaborn*, *datetime* e *plotly*.
- Nesse repositório se encontra o arquivo `requirements.txt`, que pode ser usado para instalar as bibliotecas na versão que foi utilizada no projeto.
    - Para instalar no windows, execute o comando em um terminal que tenha acesso ao python:
    ```
    pip install -r requirement.txt
    ```