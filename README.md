# Automa-o-WEB-Busca-de-Precos

Projeto de automação WEB para buscar informações de preços de produtos nos sites, realizar a comparação de preços e se algum produto estiver com 20% ou mais de desconto será enviado um email ao responsável peo setor de compras.

TECNOLOGIAS UTILIZADAS:
Para realização do projeto foi utilizado o Python e Selenium.

DESCRIÇÃO DOS PROCESSOS:
Utilizando uma base de dados (arquivo excel) contendo a lista de produtos e links é realizado web scraping acessando os sites dos fornecedores e coletando os preços dos produtos.
Após a coleta de dados, os mesmos são tratados e  inseridos na base de dados.
Apartir das novas informações é realizada uma comparação com o preço original contido na base de dados, e se os preços coletados estiverem com 20% ou mais de desconto é enviado um email ao setor de compras.
No email é enviado a planilha com os dados coletados e informando em qual Loja está mais barato, assim auxiliando o setor a tomar decisões rápidas.

FINALIDADE DE PROJETO:
O objetivo do projeto é utilizar o selenium para buscar informações de sites complexos que constantemente são atualizados, tratar os dados coletados e dar um destino para as informações encontradas.
O projeto foi realizado durante o Curso Python Impressionador ministrado pela HashTag Treinamentos.
