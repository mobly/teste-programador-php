# Teste - Criação de uma loja simples

Elaborar um carrinho de compras simples (lista de categorias / lista de produtos / busca / detalhe / carrinho / criação do pedido / lista de pedidos) em PHP / MySQL (pode usar framework).

1. Os produtos devem estar em um banco de dados relacional nos quais devem ser exibidos na lista;
1. Os produtos devem possuir os seguintes atributos : nome, descriçao, imagem, preço, categoria(um produto pode estar em mais de uma categoria) , caracteristicas (devem ser pré-definidas e associadas ao produto);
1. Não é necessário criar um layout elaborado;
1. O carrinho deve ser mantido mesmo se o usuário navegar em outra pagina (nova busca / listagem / ou detalhe do produto );
1. O pedido deve ser salvo no banco de dados contemplando todos os itens do carrinho e os dados do usuário ( Pessoais e de entrega );
1. Não é necessário integração de nenhuma forma de pagamento, apenas gerar o registro do pedido no banco de dados;

## Entrega

O código do projeto deve ser colocado no Github ou Bitbucket do candidato e deve ser enviado apenas o link público do projeto (Código php, Bibliotecas, Estrutura do banco de dados - com dados para teste ).

### Muita atenção

Incluir também no repositório um arquivo **README** com instruções para rodar o projeto. É muito importante que funcione.

## Extras

Outras tecnologias consideradas (Para classificação apenas - a falta do uso não desqualifica o candidato) :

- KeyValueDB (Redis/Memcache);
- Motores de pesquisa (Solr/Sphinx/ElasticSearch/etc); 
- Queue (RabbitMQ / ApacheMQ / Gearman);
- Testes Unitários ;
- Front End : Angular / Bootstrap / React / Vue;
- Docker
