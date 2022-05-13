# API-REST-NodeJS
Uma API REST usando NodeJS e Express fazendo conexão com MongoDB.

Autenticação:
Contém registro utilizando criptografia Bcrypt, autenticação com Token JWT e rotas de recuperação de senha através de um token enviado por email com tempo de validade de 1 dia (Nodemailer). Os tokens JWT criados tanto na autenticação quanto no registro, contém uma validação através de middleware com expiração de 1 dia, e é gerado sempre um novo token quando autenticado e registrado.

CRUD:
Nessa api você pode criar vários projetos que contém tarefas, dentro de cada projeto você pode registrar várias tarefas. Essas tarefas contém a assinatura do usuário que a criou, sua data de criação, o projeto de onde ele é vinculado e um status que informa se a tarefa foi concluída ou não.
