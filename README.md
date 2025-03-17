# Comandos Cypress

Criação e inicialização do projeto em node
  npm init -y

Instalação cypress no projeto 
  npm install cypress --save-dev

Comando para testes em modo headless 
  npx cypress run

Comando para instalação do mochawesome 
  npm install --save-dev mochawesome 

Comando para testes em modo mochawesome 
  npm cypress run --reporter mochawesome 



Config.js 

/* const { defineConfig } = require("cypress");

module.exports = defineConfig({
  projectId: "f5nnsk",
  e2e: {
    setupNodeEvents(on, config) {
      // implement node event listeners here
    },
    video: true,
    reporter: 'mochawesome',
    reporterOptions: {
      reportDir: 'cypress/results',
      overwrite: false,
      html: true,
      json: false,
      timestamp: "mmddyyyy_HHMMss" }
    },
});*/
