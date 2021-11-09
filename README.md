# sample-node
App Node simples para testes

## Iniciando uma aplicação node
npm init > irá criar o package.json

node index.js > Irá rodar a aplicação

nodemon index.js > Irá rodar a aplicação e reiniciar automaticamente quando o arquivo mudar (após instalar o pacote)

## Reiniciando uma Aplicação Node Quando o Arquivo Mudar
Por padrão, o comando node *index.js* vai iniciar a sua aplicação, mas não vai reiniciar quando você fizer alguma atualização no arquivo. Isso pode ser chato quando você está desenvolvendo e precisa parar e reiniciar a aplicação toda vez que precisa aplicar uma alteração.

Felizmente temos um pacote npm que vai monitorar e reiniciar quando mudanças forem identificadas. Esse pacote é o nodemon e para intalar basta seguir o comando a seguir.

O -g significa que o pacote vai ser instalado globalmente no seu sistema.

*$ npm install -g nodemon*