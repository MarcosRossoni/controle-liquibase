# Sistema de Controle de liquidbase

O projeto é um complemento Sistema de Controle JSP o qual segue o link do mesmo https://github.com/MarcosRossoni/SistemaControleJSP, 
com este é possivel a tabela que sera utilizada no projeto principal.

# Detalhamento

O projeto foi criado como um projeto springBoot com JDK 17, o banco de dados escolhido foi o Postgres. Para que a tabela
seja construída de forma correta deve se criar um base de dados com o nome <b>sistema_autorizacao</b>, o mesmo pode ser criado
em uma instância do Postgres em um container Docker ou local.

Após abrir o projeto e configurar o ambiente se deve abrir o terminal e rodar o comando <b>mvn install</b> para que a tabela
seja criada.