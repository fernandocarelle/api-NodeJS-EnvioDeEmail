<h1 align="center"> <strong> API NodeJS para envio de emails </strong></h1>

* Envio utilizando o SMTP do SendinBlue
 * NodeJS
   * API
   * Pacote NodeMailer
   * Pacote Cors
   * Pacote Multer para upload de arquivos
   * Pacote body-parser - Formatar e transformar os dados da requisição em objeto JSON

 ### Instalação
 * git clone https://github.com/fernandocarelle/api-NodeJS-EnvioDeEmail.git
 * cd api-NodeJS-EnvioDeEmail
 * npm install

 ### Configuração
 * Crie uma conta no SendinBlue aqui -> [Link](https://pt.sendinblue.com/).
 * Gere um senha SMTP no Menu Transacional / Configurações.
 * Inclua essa senha dentro do arquivo **.env**
 * No arquivo **nodemail.js**, altere o email para o seu.
 * Conecte a api com o seu formulário.
 * **npm start** para rodar a api.