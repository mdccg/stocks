# stocks

## Níveis de usuário

1. Externo
	1. Cliente
	2. Vendedor (ex.: Samsung, Apple&hellip;)
2. Interno
	1. Funcionário
	2. Vendedor (ex.: Stocks)
3. Técnico em informática

## Modelos de dados

### Usuário

- Nome completo
- Número de CPF
- Telefone celular
- Telefone fixo
- [Loja](#loja)
- [Localização](#localização)

### Cartões

- Número do cartão
- Validade do cartão
- _Card Verification Value_ do cartão
- [Cliente](#usuário)

### Loja

- CNPJ
- Nome
- Site
- Logotipo
- Descrição
- Setor
- Localização

### Localização 
- Rua
- Número residencial
- Bairro
- Município
- Unidade federativa
- Código postal
- Ponto de referência

### Produtos

- Nome
- Descrição
- Preço unitário
- Quantidade em estoque
- Valor de cada prestação
- Número de parcelas
- Mídias
- [Categoria](#categorias)
- [Vendedor](#usuário)

### Categorias

- Nome <!-- infantil, tecnologia, smartphones... -->

### Compras

- Data
- Quantidade adquirida
- Parcelado (booleano)
- Pago (booleano)
- Forma de pagamento
- [Produto](#produtos)
- [Cliente](#usuário)
- [Vendedor](#usuário)

## Formas de pagamento dos vendedores internos

- Banco do Brasil
- MasterCard
- PicPay
- Cartão de crédito
- Cartão de débito
- Pix
- NuBank
- Real

## Perguntas

### 1. É possível que dois vendedores de uma loja (dois vendedores da Samsung, por exemplo) se cadastrem na Stocks para vender produtos diferentes? 
	
Nesse caso, a loja (Samsung) deve ser cadastrada previamente pelo primeiro vendedor que se cadastrou na Stocks para que o segundo vendedor apenas vincule sua conta à loja já criada?

> Sim.

### 2. A loja terá consulta ao Serasa?

> Sim.

### 3. O vendedor de uma loja (Samsung) pode comprar produtos de outra loja (Apple), de modo que se comportem também como clientes no sistema?

> Sim.

### 4. Os vendedores da Stocks têm algum código (como o CPF) para identificá-los no sistema?

A Stocks já tem algum sistema que contém os dados pessoais sobre os seus funcionários? Se tiver, é possível cadastrar um funcionário no app apenas com o código.

> Sim, o número de CPF.

### 5. Os 5% de desconto em caso de atraso da entrega são aplicados no valor total da compra ou no valor unitário de cada produto?

> No valor total da compra.

### 6. As formas de pagamento se aplicam à todas as lojas ou somente à Stock?

> Todas as lojas.

### 7. Haverão entregas muito distantes para, por exemplo, cidades onde não há filiais da Stock? Se sim, o frete será calculado utilizando o método dos correios?

> Sim. O frete será calculado automaticamente pelo site.

## Mídias

### Fontes tipográficas

- Lilita One (display)

### Paleta de cores

- [🇺🇸 American Palette | Flat UI Colors 🎨 280 handpicked colors ready for COPY & PASTE](https://flatuicolors.com/palette/us)

### Ícones

<!-- font awesome -->
- [Magnifying glass - solid | Font Awesome](https://fontawesome.com/icons/magnifying-glass?s=solid&f=classic)
- [Circle user - solid | Font Awesome](https://fontawesome.com/icons/circle-user?s=solid&f=classic)
- [Location dot - solid | Font Awesome](https://fontawesome.com/icons/location-dot?s=solid&f=classic)
- [Caret Down - solid | Font Awesome](https://fontawesome.com/icons/caret-down?s=solid&f=classic)
- [Binoculars - solid | Font Awesome](https://fontawesome.com/icons/binoculars?s=solid&f=classic)
- [Phone - solid | Font Awesome](https://fontawesome.com/icons/phone?s=solid&f=classic)
- [What's App - | Font Awesome](https://fontawesome.com/icons/whatsapp?s=solid&f=brands)
- [Envelope - solid | Font Awesome](https://fontawesome.com/icons/envelope?s=solid&f=classic)
- [Facebook - | Font Awesome](https://fontawesome.com/icons/facebook?s=solid&f=brands)
- [Instagram - | Font Awesome](https://fontawesome.com/icons/instagram?s=solid&f=brands)
- [LinkedIn - | Font Awesome](https://fontawesome.com/icons/linkedin?s=solid&f=brands)
- [Twitter - | Font Awesome](https://fontawesome.com/icons/twitter?s=solid&f=brands)
- [Building with Columns - solid | Font Awesome](https://fontawesome.com/icons/building-columns?s=solid&f=classic)
- [Credit Card - solid | Font Awesome](https://fontawesome.com/icons/credit-card?s=solid&f=classic)
- [Credit Card - solid | Font Awesome](https://fontawesome.com/icons/pix?s=&f=brands)
- [MasterCard Credit Card - | Font Awesome](https://fontawesome.com/icons/cc-mastercard?s=solid&f=brands)
- [Pix - | Font Awesome](https://fontawesome.com/icons/pix?s=solid&f=brands)
- [Wallet - solid | Font Awesome](https://fontawesome.com/icons/wallet?s=solid&f=classic)

### Imagens

<!-- freepik -->
- [Free Photo | Abstract blur and defocused shopping mall](https://www.freepik.com/free-photo/abstract-blur-defocused-shopping-mall_1255076.htm)

<!-- mercado livre -->
- [Smartphone Galaxy A03 Tela 6.5'' 64gb 4gb Ram Azul Samsung | Parcelamento sem juros](https://produto.mercadolivre.com.br/MLB-2146288737-smartphone-galaxy-a03-tela-65-64gb-4gb-ram-azul-samsung-_JM#position=27&search_layout=stack&type=item&tracking_id=481e4b5e-60d6-4fec-b391-c9f94be6dc56)
- [Samsung Galaxy A23 128gb 4gb Ram Branco | Parcelamento sem juros](https://www.mercadolivre.com.br/samsung-galaxy-a23-128gb-4gb-ram-branco/p/MLB19461375?pdp_filters=category:MLB1055#searchVariation=MLB19461375&position=1&search_layout=stack&type=product&tracking_id=481e4b5e-60d6-4fec-b391-c9f94be6dc56)
- [Samsung Galaxy M52 5G Dual SIM 128 GB white 6 GB RAM | Parcelamento sem juros](https://www.mercadolivre.com.br/samsung-galaxy-m52-5g-dual-sim-128-gb-white-6-gb-ram/p/MLB18600627?pdp_filters=category:MLB1055#searchVariation=MLB18600627&position=2&search_layout=stack&type=product&tracking_id=481e4b5e-60d6-4fec-b391-c9f94be6dc56)
- [Samsung Galaxy A51 Dual SIM 128 GB prism crush black 4 GB RAM | Parcelamento sem juros](https://www.mercadolivre.com.br/samsung-galaxy-a51-dual-sim-128-gb-prism-crush-black-4-gb-ram/p/MLB15466968?pdp_filters=item_id:MLB1972625018#searchVariation=MLB15466968&position=4&search_layout=stack&type=pad&tracking_id=481e4b5e-60d6-4fec-b391-c9f94be6dc56)
- [Smartphone Galaxy A03 Core 32gb 2gb Cobre Samsung | Parcelamento sem juros](https://produto.mercadolivre.com.br/MLB-2711174737-smartphone-galaxy-a03-core-32gb-2gb-cobre-samsung-_JM#position=29&search_layout=stack&type=item&tracking_id=481e4b5e-60d6-4fec-b391-c9f94be6dc56)

<!-- ri happy -->
- [Jogo Virtual Clássico - Tamagochi - Bichinho Virtual - Sprinkle- Sortido - Fun](https://www.rihappy.com.br/jogo-virtual-classico-tamagochi-bichinho-virtual-sprinkle-sortido-fun/p)
- [Conjunto Veículos e Bonecos - PJ Masks - Jato 3 em 1 - Hasbro](https://www.rihappy.com.br/conjunto-pj-masks-jato-3-em-1-pj-masks-hasbro/p)
- [Boneca Baby Alive - Princess Ellie Grows Up! - Cabelos Castanhos - F5237 - Hasbro](https://www.rihappy.com.br/boneca-baby-alive-princess-ellie-grows-up--cabelos-castanhos-f5237-hasbro/p)
- [Brinquedo de Atividades - Brincando de Motorista - Retrô - Painel - Vermelho - Estrela](https://www.rihappy.com.br/brinquedo-de-atividades-brincando-de-motorista-retro-painel-vermelho-estrela/p)
- [Mini Figura e Acessórios - Peppa Pig - Sorveteria da Peppa - Hasbro](https://www.rihappy.com.br/mini-figura-e-acessorios-peppa-pig-sorveteria-da-peppa-hasbro/p)
