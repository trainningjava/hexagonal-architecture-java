# hexagonal-architecture-java
https://www.happycoders.eu/software-craftsmanship/hexagonal-architecture-java/

Iniciando um banco de dados MySQL local
Para iniciar o aplicativo no modo MySQL, você precisa primeiro iniciar um banco de dados MySQL local. A maneira mais fácil de fazer isso é via Docker, por exemplo, usando o seguinte comando:

Se outra instalação do MySQL já ocupar sua porta local 3306, basta usar outra porta livre, por exemplo, a porta 3307, substituindo- -p3306:3306a por -p3307:3306. Você deve então ajustar a porta no initMySqlAdapters()método da RestEasyUndertowShowApplicationclasse de acordo.

docker run --name hexagon-mysql -d -p3306:3306 \
-e MYSQL_DATABASE=shop -e MYSQL_ROOT_PASSWORD=test mysql:8.1

Na caixa de diálogo que aparece, clique em "Modify options" e depois em "Add VM options" – ou pressione Alt+V. Isso torna o campo de entrada "VM options" visível. Digite "-Dersistence=mysql"

