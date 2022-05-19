 1. npm init -y = inicializa o projeto com o package.json

2. npm i react = instala a lib react.

3. npm i react-dom = 
    Instala a dependencia react-dom que ajuda a nos trabalhar com react na web, comunicacao com arvore de   elementos do html
  
4. npm i @babel/core @babel/cli @babel/preset-env -D 
    BABEL = Babel é responsavel para converter nosso codigo de uma maneira que todos os browsers e todo ambiente de nossa aplicacao consiga entender todo o codigo, pois o JS se atualiza muito rapido. 

5. npm i webpack webpack-cli webpack-dev-server -D
    WEBPACK = Estipula uma serie de configs (LOADERS), de como ela deve tratar diversos tipos de arquivos, ex: converter SASS para CSS pois o CSS é entendivel pelo browser

6. npm i babel-loader -D = 
    Integracao entre o babel e webpack

7. npm i webpack-dev-server -D = 
    Observador e auto-reload, cria automaticamente um novo bundle para nao precisar ficar rodando toda vez que tiver alteracao o comando npx webpack

8. npm i cross-env -D = 
    Serve para criar variaveis de ambiente. (OBS: PACKAGE.JSON = producao e desenvolvimento ambientes)

9. npm i style-loader css-loader -D = 
    Serve para transpilar com babel o css (CONFIGURAR COM WEBPACK)

10. npm i @babel/preset-typescript -D = 
    Serve para o babel entender o typescript

##### Toda vez que tiver alteracao no codigo rodar o ===> npx webpack, para fazer a nova compilacao das alteracoes!  
