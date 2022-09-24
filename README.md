# projeto2_pythonimpressionador

## 1. Introdução
Projeto de Automação Web em Python desenvolvido ao longo do Curso Python Impressionador, ministrado pela Hashtag Treinamentos. A ideia principal da automação é, com base em uma planilha contendo informações de alguns produtos (iPhone e Placa de Vídeo), procurar de forma automática no Google Shopping e no Buscapé cada um deles, com base nas especificações que foram colocadas nas planilhas (respeitando a faixa de preços pré-estabelecida, e os elementos que não podem estar contidos no nome), e enviar as ofertas de cada um deles por e-mail.


## 2. Situação-desafio
"Imagina que você trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos.

Nessa hora, você vai constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

Seu objetivo: Se o valor dos produtos for abaixo de um preço limite definido por você, você vai descobrir os produtos mais baratos e atualizar isso em uma planilha.

Em seguida, vai enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra.

A procura deve ser de produtos comuns em sites como Google Shopping e Buscapé, mas a ideia é similar para outros sites.
 
Planilha de Produtos, com os nomes dos produtos, o preço máximo, o preço mínimo (para evitar produtos "errados" ou "baratos de mais para ser verdade" e os termos que vamos querer evitar nas nossas buscas.

Procurar cada produto no Google Shopping e pegar todos os resultados que tenham preço dentro da faixa e sejam os produtos corretos. O mesmo deve ser feito para o Buscapé também

Por fim, deve ser enviado um e-mail (no caso da empresa seria para a área de compras por exemplo) com a notificação e a tabela com os itens e preços encontrados, junto com o link de compra.
