# `Projeto integrador do curso de TSI` - IFRN
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

## `Resumo`
Nosso projeto possue o objetivo de criar uma aplicação Mobile que o usuário poderá fazer uma lista pesonalizada de suas compras antes de ir ao supermecado.
Nossa aplicação poderá cadastrar usuários em sua plataforma onde ficará salvo o seu perfil. Com isso ficará disponível ao usuário historico de suas compras.

Essa aplicação também estará em contato com algumas APIs de supermecados onde ao usuário criar sua lista de compras poderá ter uma media parcial de valor que poderá gastar com aquela lista no supermecado X. Isso fazerá o cliente ter em suas mãos informações que fazerá ele saber de antemão aonde economizará mais.

## `Interfaces`
### `Splash screen` 
Tela de abertura

<img align="center" alt="Tela de abertura" height="" width="200" src="https://user-images.githubusercontent.com/98723501/173961242-8586c694-b864-4490-abdc-6c2b411f63c0.png" />  

#

### `Login screen` 
Tela de login - Nela o usuário caso já possua uma conta na plataforma bastará apenas que ele entre com o login e senha mas caso não tenha ainda terá uma certa logo abaixo indicando ao usuário que ele cadastre-se na aplicação.

<img align="center" alt="Tela de login" height="" width="200" src="https://user-images.githubusercontent.com/98723501/174194850-3925f71e-7dad-474a-8f5b-2ae2c445459e.png" />

#

### `New account screen` 
Criar nova conta - O usuário poderá se cadastrar no app a partir desta tela.

<img align="center" alt="Criar nova conta" height="" width="200" src="https://user-images.githubusercontent.com/98723501/174194955-b0d96c70-5e4a-4909-a645-c7658fab46ab.png" />

#

### `New account screen` 
O usuário após inserir o seu nome, e-mail e senha na primenra tela, será direcionado para a segunda tela de cadastro. Onde será solicitado seu endereço.

<img align="center" alt="Criar nova conta" height="" width="200" src="https://user-images.githubusercontent.com/98723501/174195054-cb814439-bc39-4674-87af-fae21d7fb4be.png" />

#

### `Welcome screen` 
Tela de boas-vindas. Essa tela aparecerá a partir do momento que o novo usuário finalizar seu cadastro na plataforma. Como também surgirá sempre que o usuário acessar o aplicativo.

<img align="center" alt="Tela principal" height="" width="200" src="https://user-images.githubusercontent.com/98723501/174196402-06d6c80c-f6d0-4eaf-bc3f-50b204c358b9.png" />


#

### `Profile screen` 
Tela de menu. Aqui o usuário terá acesso a seu perfil podendo alterar seu endereço, senhar, ver historico etc.

<img align="center" alt="Menu" height="" width="200" src="https://user-images.githubusercontent.com/98723501/174195149-77511829-aba2-477b-9c27-eb3ce2e9065e.png" />

#

### `Main screen` 
Aqui  está a tela principal da aplicação. Aqui o usuário poderá escolher a categoria de produtos, quais os produtos ele adicionará a lista ou usar a lista anterior.

<img align="center" alt="Tela principal" height="" width="200" src="https://user-images.githubusercontent.com/98723501/175956525-96901176-e26d-4720-a89a-e1e73ebe2f4d.png" />

#

### `Main screen` 
Tela onde o usuário poderá criar sua lista, escolher a categiria de produtos ou usar uma já existente.

<img align="center" alt="Tela principal" height="" width="200" src="https://user-images.githubusercontent.com/98723501/175957144-ee33fff1-bfb2-45cc-8bf2-d0789687d821.png" />

#

### `Lowest price screen` 
Esta tela o usuário encontrará a melhor opção de compra. Escolherá dentre a lista de supermecados aquele que melhor economizará.

<img align="center" alt="Tela principal" height="" width="200" src="https://user-images.githubusercontent.com/98723501/175958740-180b0a95-13ab-4eaa-a41d-547e6c7f7e13.png" />

#

## `Diagrama de caso de uso`


![Captura de Tela (7)](https://user-images.githubusercontent.com/98723501/179877363-b06e73d3-f5ed-4c45-9d5d-43b95563d1ea.png)

#

## `Diagrama de classe`
Nosso diagrama de classe envolverá a criação do nosso BD em um SGBD relacional.
Logo abaixo teremos uma breve explicação de cada classe que será implementada no sistema.

- `Rigister`: 
Essa classe em nosso sistema será responsável envolver o cadastro dos clientes na aplicação, onde cada cliente ao si registrar será criado um perfil para cada um.

- `Person`:
A classe pessoa é uma classe geral ou primitiva onde será cadastrado os tipos de pessoas em nosso sistema. 
Haverá dois tipos de pessoas: pessoa juridica(supermecados) e pessoa fisíca(usuários ou clientes).

![Captura de Tela (8)](https://user-images.githubusercontent.com/98723501/179877888-b2c688f0-1f2a-4c90-a1bf-54856c05a257.png)

















































