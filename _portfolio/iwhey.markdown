---
layout: post
title:  iWhey
description: “Venha crescer com a gente!”
img:
---

NossoApp tem como foco a criação de lojas virtuais para venda de suplementos e com isso o delivery do produto para casa do cliente. Então, tornamos as vendas mais fáceis e mais rápidas para todos os clientes .
Viemos para modernizar o seu relacionamento com as lojas de suplementos. ComiWhey , você pede rapidamente em qualquer loja que faz entrega na sua região. Empoucos cliques , você pode escolher entre vários produtos, alimentos e ficardespreocupado enquanto espera o seu pedido chegar onde quer que esteja . É rápido,fácil e seguro. E ainda é gratuito !!! Seguir com sua dieta nunca foi tão fácil!!!

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/iwhey/1.png" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/iwhey/2.png" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/iwhey/3.png" alt="" title="example image"/>
</div>
<br/>
Site
- CRUD da Loja: Criar, Visualizar e Atualizar cadastro da loja. Pelo nosso site.- Login Loja: A loja é tem um login e se conecta a aplicação pelo navegador.os valores para os produtos.desconto e a data em que a promoção acaba.compra, os produtos escolhidos com as quantidades, o valor total, o endereço de entrega.alterando o status da venda para “Venda Cancelada Pela Loja”.- Visualizar Rota de Entrega: O  dono da loja visualiza a melhor rota para o entregador fazer a corrida fornecida pela api directions do google.- CRUD de Produtos da Loja: Criar, Listar, Atualizar e Deletar os produtos da loja. As informações dos produtos são adicionadas pelos administradores da aplicação, o dono da loja é responsável por atribuir- CRUD de Promoção do Produto da Loja: Criar(Pelos administradores da aplicação), Listar, Atualizar e Deletar promoção para os produtos da loja. O produto pode ter uma promoção, que é por porcentagem, o dono da loja escolhe o produto e adiciona a promoção adicionando a porcentagem de- Listar Vendas da Loja: Mostra todas as vendas da loja durante o período selecionado(Mês/Ano) e separada também pelo status da venda.- Visualizar Venda da Loja: Mostra todos os detalhes da venda, como o nome do cliente que realizou a- Alterar Status da Venda da Loja: O dono da loja pode alterar o status da venda. No primeiro momentoem que o status é “Aguardando Envio Pela Loja” ele possui duas opções, a primeira seria ele adicionaro tempo de entrega e clicar em “Enviar Produtos” alterando o status para “Aguardando Loja ConfirmarEntrega” e a segunda opção seria o dono da loja “Cancelar Venda”, adicionando o motivo docancelamento e o status seria alterado para “Venda Cancelada Pela Loja”. Se o status da venda for“Aguardando Loja Confirmar Entrega” o dono da loja também possui duas opções, a primeira seria eleclicar no botão “Confirmar Venda” e o status seria alterado para “Venda Concluída” e a segunda opçãoseria adicionar um motivo de cancelamento da venda e em seguida clicar em “Cancelar Venda”,
- Visualizar Rota de Entrega: O  dono da loja visualiza a melhor rota para o entregador fazer a corrida fornecida pela api directions do google.
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/iwhey/4.png" alt="" title="example image"/>
</div>
<br/>
Aplicativo

- CRUD de usuários: Criar, visualizar, Atualizar e apagar usuário.- Login de usuário: Usuário somente pode realizar uma compra logado.- Listagem de produtos em destaque: Na tela inicial que funciona como se fosse uma 
- Listagem de lojas próximas:  De acordo com o posição atual do usuário (ou de algum endereço específico) é listado lojas próximas.
- Filtro por loja: É possível realizar a busca de alguma loja específica através de seu nome.- Filtro por produto: É possível realizar filtro por algum produto específico, ou seja, o usuário pesquisapelo nome do produto e será apresentado as lojas que possuem aquele produto.- Promoções: Após o lojista criar uma promoção no site web, essa promoção é apresentada ao usuário.- Carrinho de compras: O  carrinho de compras permite dividir as compras por lojas, ou seja, é listado os produtos de acordo com cada loja selecionada.
- Realizar compra: A pós o usuário escolher seus produtos então o fluxo desejável é que realize a compra, então será enviado um e­mail para o lojista apresentando informações do pedido, que por sua vez trata de realizar o delivery.
- Listagem de compras: Para um maior controle de suas compras, o usuário dispõe de uma lista de todas suas compras.
- Fale conosco: um canal de comunicação entre o usuário (cliente) e nós do iWhey.
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/iwhey/4.png" alt="" title="example image"/>
</div>