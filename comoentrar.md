Para acessar o projeto SENAI Connect, abra o terminal do VS Code na pasta do projeto e execute o comando. Ele iniciará automaticamente o frontend e o backend, permitindo acessar o sistema pelo navegador. Certifique-se de que o MySQL esteja ativo para garantir a conexão com o banco de dados. 
 Para tudo funcionar certo, é preciso ter o banco d dados aberto.
 No terminal digite:
 
npm install -D concurrently

Depois: 

npm install express mysql2 cors dotenv --prefix server

E por fim:

npm run start:all
