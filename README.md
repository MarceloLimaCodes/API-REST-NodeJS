# JavaScript-API
API REST que utiliza NodeJS e Express com conexão em MongoDB.

Nessa api você pode criar vários projetos que contém tarefas, dentro de cada projeto você pode registrar várias tarefas. Essas tarefas contém a assinatura do usuário que a criou, sua data de criação, o projeto de onde ele é vinculado e um status que informa se a tarefa foi concluída ou não.

Autenticação:
  - JWT Token
  - Middleware

Os tokens JWT criados tanto na autenticação quanto no registro contém uma validação através de middleware com expiração de 1 dia. É gerado sempre um novo token quando autenticado e registrado.
  
Criptografia:
  - Bycript
  
Serviços:
  - Nodemailer (Recuperação de senha via email) 
