### Desenvolvimento de um APP em React Native para simular o APP do Ifood

**Esse projeto foi apresentado durante o Bootcamp promovido pela [Digital Innovation One] (https://web.dio.me/)** \
**Instrutor [Pablo Henrique] (https://github.com/pablohdev) \

**TECNOLOGIAS UTILIZADAS NO PROJETO**
[React_Native] (https://reactnative.dev/)  \
[Expo] (https://docs.expo.dev/) \
[Styled-Components] (https://styled-components.com/) \
[React_Navigation] (https://reactnavigation.org/)

Para criar o projeto:
Faça um fork ou download desse Repositório:
Crie uma pasta em seu computador e descompacte o arquivo.
Utilizando o terminal de comando do S.O. ou do VS Code navegue até a pasta do arquivo e digite `yarn` \
Aguarde instalar todas as dependências.

Para criar o projeto do início:
 Caso não tenha instalado em seu computador instale o Expo de forma global:
 `npm install --global expo-cli`

 Em seguida navegue no terminal até a pasta onde quer criar o Projeto. \
 Para criar o projeto utilizando o Expo digite o comando:
 
 `expo init [nome-do-projeto]`

 Selecione a opção "blank"

 Esse comando vai criar a estrutura do projeto e o arquivo **package.json**

Em seguida no terminal instale as dependências: \
`yarn add styled-components` \
`yarn add @react-navigation/native`  \
`yarn add @react-navigation/bottom-tabs`  \
`yarn add @react-navigation/stack` \
`yarn add react-native-screens react-native-safe-area-context`
`expo install react-native-gesture-handler` \
`expo install @react-native-masked-view/masked-view` \

## EndPoints

<p>Para consumir dados usamos uma api fake, usando os seguintes endpoints<p>

| NOME         | ENDPOINT                                                                      |
| ------------ | ----------------------------------------------------------------------------- |
| GERAL        | http://my-json-server.typicode.com/pablohdev/app-ifood-clone/db               |
| BANNERS      | http://my-json-server.typicode.com/pablohdev/app-ifood-clone/banner_principal |
| CATEGORIAS   | http://my-json-server.typicode.com/pablohdev/app-ifood-clone/categorias       |
| RESTAURANTES | http://my-json-server.typicode.com/pablohdev/app-ifood-clone/restaurantes     |

Como emulador eu utilizei um celular com sistema Android. \
Para isso é necessário instalar o App do Expo no aparelho.
