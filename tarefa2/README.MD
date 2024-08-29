📊 Relatório de Consolidação de Dados
Este código Hive SQL cria e manipula duas tabelas, campanhas e purchases, para consolidar dados sobre clientes, campanhas e compras. 📈

Primeiro, define-se a estrutura das tabelas e carrega-se dados de arquivos CSV armazenados no Amazon S3. ☁️ Em seguida, cria-se uma visão chamada consolidated_data, que agrega informações sobre cada cliente, incluindo o total gasto, o local de compra mais frequente, a data da primeira e última compra, a campanha mais recebida e a quantidade de campanhas com status "error". 💵📍📅

A visão também adiciona a data atual e uma formatação do ano e mês. 🗓️ As subconsultas são usadas para identificar os locais e campanhas mais frequentes, e o resultado final é exibido com um SELECT simples. 🔍 A abordagem garante uma visão consolidada e útil para análise de comportamento de clientes e eficácia de campanhas.
