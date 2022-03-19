https://code.visualstudio.com/docs/nodejs/nodejs-tutorial

https://code.visualstudio.com/docs/nodejs/reactjs-tutorial

npm install -g express-generator
//nainstaluju express, kdyz nemam (-g je globalni)

express myExpressApp --view pug
//express vytvori zaklad apky

cd myExpressApp
npm install
//instalace zavislosti z package.json

//npm start
zkusim spustit

//defaultne bezi na http://localhost:3000/


//k debugovani potrebuji vytvorit launch.json
run -> add configuration


DODELAT CI/CD proces nasazovani primo na Azure
https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/deploy-to-azure-vscode?view=azure-devops
https://code.visualstudio.com/docs/azure/deployment


SWAGGER
https://javascript.plainenglish.io/how-to-implement-and-use-swagger-in-nodejs-d0b95e765245
npm install express cors morgan body-parser dotenv
npm install @babel/core @babel/node @babel/preset-env