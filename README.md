# `Projeto integrador do curso de TSI` - IFRN

## `Resumo`
Nosso projeto possue o objetivo de criar uma aplicação Mobile que o usuário poderá fazer uma lista pesonalizada de suas compras antes de ir ao supermecado.
Nossa aplicação poderá cadastrar usuários em sua plataforma onde ficará salvo o seu perfil. Com isso ficará disponível ao usuário historico de suas compras.

Essa aplicação também estará em contato com algumas APIs de supermecados onde ao usuário criar sua lista de compras poderá ter uma media parcial de valor que poderá gastar com aquela lista no supermecado X. Isso fazerá o cliente ter em suas mãos informações que fazerá ele saber de antemão aonde economizará mais.

## `Interfaces`
### Splash  
Tela de abertura

![Captura de tela de 2022-09-08 08-50-21](https://user-images.githubusercontent.com/98723501/189120044-86ff4237-0e59-4560-9526-c0eab9f0285d.png)

#

### Login  
Tela de login - Nela o usuário caso já possua uma conta na plataforma bastará apenas que ele entre com o login e senha mas caso não tenha ainda terá uma certa logo abaixo indicando ao usuário que ele cadastre-se na aplicação.

![2](https://user-images.githubusercontent.com/98723501/189120700-54f7786d-61d1-49f0-9cbd-7ff6932c2423.png)

#

### Home 
Tela principal da aplicação. Aqui o usuário poderá escolher em clicar em criar lista ou clicar em uma das categoria de produtos que estará renderizada na tela e iniciar a criação da lista.

![3](https://user-images.githubusercontent.com/98723501/189121198-4c8a8269-124f-4ba6-838d-030a2bcdba13.png)

#

### Supermercado 
Nesta tela o usuário poderá selecionar um dos supermercados renderizados na tela. Pós os produtos que ele escolher para sua listinha será referente ao supermercado escolhido por ele aqui.

![4](https://user-images.githubusercontent.com/98723501/189122879-684009fb-95a9-4a17-a55f-e162033edd17.png)

#

### Categoria
Depois da escolha do supermercado o usuário deverá escolher uma categoria de produtos ou a geral para começar a escolher seus produtos.

![Captura de tela de 2022-09-08 09-45-25](https://user-images.githubusercontent.com/98723501/189125136-1d113c6a-3855-4de4-bbd2-fb7b307f14c7.png)

#

### Produtos 
Escolhida a categoria dos produtos então será renderizado na tela todos os produtos referentes ao supermercado escolhido. Com o seu preço, marca entre outras informações.

![5](https://user-images.githubusercontent.com/98723501/189126783-a69723f4-184b-4657-a38f-55917d70c1cd.png)

#

### Lista 
Aqui é a tela na qual o usuário poderá visualizar as listas em processo. Nela ele poderá realizar uma comparação de preços dentre as listas que ele criou e escolher a melhor opção para ele.

![6](https://user-images.githubusercontent.com/98723501/189127723-e463e37b-95d4-4061-93e3-d382191a9a58.png)

#

### Histórico
Aqui nesta tela o usuário poderá ter um histórico de suas listas realizadas em meses anteriores onde poderá ter informações que julgue necessárias.

![7](https://user-images.githubusercontent.com/98723501/189128750-8b4e93f6-4fe3-4a0e-b365-610868b43860.png)

#

## `Diagrama de caso de uso`


![Captura de Tela (7)](https://user-images.githubusercontent.com/98723501/179877363-b06e73d3-f5ed-4c45-9d5d-43b95563d1ea.png)

#

## `Diagrama de Entidade Relacionamento`
Nosso diagrama envolve a criação do nosso BD no SGBD relacional.
Logo abaixo teremos uma breve explicação de cada classe que foi implementada no sistema.

- `Rigister`: 
Essa classe em nosso sistema será responsável envolver o cadastro dos clientes na aplicação, onde cada cliente ao si registrar será criado um perfil para cada um.

- `Person`:
A classe pessoa é uma classe geral ou primitiva onde será cadastrado os tipos de pessoas em nosso sistema. 
Haverá dois tipos de pessoas: pessoa juridica(supermecados) e pessoa fisíca(usuários ou clientes).

![Captura de Tela (83)](https://user-images.githubusercontent.com/98723501/185929215-cf9bdccc-ce0f-4290-9bd9-a4e86bcb2bc2.png)

















































