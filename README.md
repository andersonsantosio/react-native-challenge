<h1 align="center">Quero Bolsa</h1>
<h2 align="center">Desafio React Native</h2>

## Introdução

Neste desafio você foi contratado para desenvolver um aplicativo de escalação de time de futebol, onde os jogadores podem ser qualquer usuário disponível no GitHub.

Todos os detalhes sobre a API do GitHub:
[https://developer.github.com/v3/](https://developer.github.com/v3/)

## Descrição

Nesta aplicativo, além de um campo de busca, você precisa exibir um campo de futebol, onde os jogadores serão adicionados e posicionados em seus respectivos pontos, ao clicar em qualquer jogador em campo, você exibirá o perfil dele com algumas informações e um botão para poder removê-lo do campo (má conduta talvez? :P).

## Funcionalidades

HomeScreen:
- Ao clicar em "Adicionar ao SQUAD", ir para a tela de busca.
- Ao pressionar um jogador em campo, poder posicioná-lo em qualquer ponto do mesmo.
- Ao clicar no jogador em campo, ir para a tela de perfil do jogador.

SearchScreen:
- Ao pesquisar, exibir a lista de usuários do GitHub que satisfazem o termo.
- Ao clicar no botão de + (adicionar), adicionar o usuário ao campo e voltar para a tela inicial.

PlayerProfileScreen:
- Ao abrir a tela, exibir do usuário a foto de perfil, bio, número de repositórios, seguidores e número de usuários que ele segue.
- Ao clicar no botão de "Remover", remover o usuário do campo e voltar para a tela inicial.

OBS: É impreterível que os dados persistam (sejam salvos) no dispositivo, a fim de que quando o aplicativo seja fechado e aberto novamente, os dados permaneçam inalterados e disponíveis.

## Design:
| HomeScreen | SearchScreen | PlayerProfileScreen |
| ---------- | ------------ | ------------------- |
| ![HomeScreen](/assets/HomeScreen.png) | ![SearchScreen](/assets/SearchScreen.png) | ![PlayerProfileScreen](/assets/PlayerProfileScreen.png)

## Requisitos

- Atender aos critérios de design.
- Atender aos critérios da regra de negócio.
- Persistir os dados localmente.
- Escrever testes unitários, coverage aceitável é de 60%.

## Recursos:

Fonte: [Roboto](https://fonts.google.com/?selection.family=Roboto)

Icones: [FontAwesome](https://fontawesome.com/icons?d=gallery)

React Native Icons:
[https://github.com/oblador/react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)

Design: https://www.figma.com/file/l5W3BnS7KM2VgxSqxUJpM1/REACT-NATIVE-CHALLENGE?node-id=0%3A1

Campo de Futebol:
[https://pixabay.com/pt/illustrations/grass-rush-futebol-campo-de-jogo-114651/](https://pixabay.com/pt/illustrations/grass-rush-futebol-campo-de-jogo-114651/)

## Links Úteis:

https://blog.reactnativecoach.com/creating-draggable-component-with-react-native-132d30c27cb0

https://jestjs.io/docs/pt-BR/tutorial-react-native
