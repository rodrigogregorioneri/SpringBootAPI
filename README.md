# SpringBootAPI

# Projeto desenvolvido no domingo, devido falta de tempo não tive como terminar 

Foi desenvolvido dois serviços

Clientes:
-------------
get
path: localhost:8092/api/rest/Clientes
--------------
-------------
post
path: localhost:8092/api/rest/Clientes
--------------
-------------
getId
path: localhost:8092/api/rest/Clientes/{id}
--------------
-------------
deleteId
path: localhost:8092/api/rest/Clientes/{id}
--------------
metodos: getId/getAll/post/delete
json:  

[{"id":"abss","codigo_cliente":null,"datada_cadastro":null,"nome":null,"numero_controle":6,"quantidade":null,"valor":null,"links":[]},{"id":"abddd","codigo_cliente":null,"datada_cadastro":null,"nome":null,"numero_controle":8,"quantidade":null,"valor":null,"links":[]}]





Pedidos:
-------------
get
path: localhost:8092/api/rest/Pedidos
--------------
-------------
post
path: localhost:8092/api/rest/Pedidos
--------------
-------------
getId
path: localhost:8092/api/rest/Pedidos/{id}
--------------
-------------
deleteId
path: localhost:8092/api/rest/Pedidos/{id}
--------------
metodos: getId/getAll/post/delete
json:  

Formatted JSON Data
{"content":[{"codigo_cliente":38,"datada_cadastro":null,"nome":"erer","numero_controle":78,"quantidade":15,"valor":100,"links":[]},{"codigo_cliente":59,"datada_cadastro":null,"nome":"erer","numero_controle":79,"quantidade":10,"valor":100,"links":[]}],"nome":"Rodrigo","sobrenome":"Gregorio Neri"}



Caso seja necessario alterar alguma propriedade do banco basta ir no arquivo application.properties lá tem toda a configuração:
https://github.com/rodrigogregorioneri/SpringBootAPI/blob/master/src/main/resources/application.properties

Não tive tempo habil para fazer os testes automatizados com o JUnit(Nunca usei Mockito por isso não pensei em usar primeiramente pois demoraria um tempo pra entender o framework e o tempo é pouco).

