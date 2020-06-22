# Desafio 3 - React Native

<li> Durante esse terceiro desafio do Bootcamp, criei uma aplicação básica utilizando React Native, além de
realizar a integração com a API, que foi feita utilizando Node.js </li>

<h2> Conceitos importantes </h2>
<li> O React Native é a versão do React utilizada para desenvolvimento mobile, é uma linguagem multiplataforma
que constrói uma interface nativa, que pode ser utilizada tanto para Android quanto para IOS. 
</li>
<li> A declaração dos componentes é semelhante ao Web, mas não iremos utilizar HTML e sim componentes próprios do 
React Native, além de aplicarmos estilo sem classes ou Id's, nenhum dos componentes possui uma estilização própria.
</li>
<li> O Expo, que é uma SDK com um conjunto de funcionalidades pronto para usar (câmera, vídeo, integrações), onde
não é necessário realizar a configuração de um emulador. Porém, não será utilizado pois o mesmo deixa uma certa
limitação sobre o controle do código nativo, além de várias bibliotecas não possuirem o suporte para o Expo.</li>

<h2> Diferença do React Native para o ReactJS </h2>
<li> No React Native iremos utilizar apenas componentes importados da própria linguagem, além dos elementos </li>
não possuirem valor semântico (significado). Além disso, todos os componentes possuem por padrão o "display: flex".
</li>
<li> View(React Native) = div, footer, header, main, aside, section (HTML)</li>
<li> Text(React Native) = p, span, strong, h1, h2, h3 (HTML)</li>

<h2> Instalação do projeto </h2>
<li> Realizar o clone do projeto via terminal: </li>

``` 
git clone https://github.com/guivicentep/GoStack-3.git
``` 
<li> Logo após, rodar o seguinte comando para instalação das dependências do projeto</li>

```
yarn
``` 
<li> Por fim, rodar o comando abaixo para rodar o app (Necessário um emulador pré configurado)</li>

```
react-native run-android (ou run-ios)
``` 
<li> Para o caso do comando acima não rodar o app, executar o comando abaixo logo em seguida:</li>

```
react-native start
```


