Adriller Genova Ferreira 8922201
Allan Ribeiro Polachini 8922347
Hikaro Augusto de Oliveira 9066487

COMO EXECUTAR:
1- Primeiro deve ser executado o Servidor (MercadoServidor.jar) passando como argumento a PORTA
2- Com o Servidor sendo executado, já é possivel executar quantos clientes quiser, para isso basta executar o MercadoCliente.jar, passando como argumento o NUMERO DE IP (host) e a PORTA

FUNCIONAMENTO:
Após a executar o programa, um MENU irá aparecer para todos os clientes conectados no servidor.
Quando o Cliente seleciona alguma ação, é enviado um pedido para o servidor, retornando as informações necessárias. Por exemplo, se o usuário quer listar todos os produtos, a aplicação do Cliente envia um pedido, e o servidor retorna todos os nomes dos produtos.
Todos os cadastros de Usuario e de Produtos, sao automaticamente salvos na aplicação do Servidor (com um arquivo CSV), dessa forma, mesmo que um usuário cadastre um novo produto, quando outro usuário, que está utilizando o programa ao mesmo tempo selecionar para listar os produtos, o novo produto ja ficará visível.
E mesmo se um cliente finalizar um programa, quando ele executar de novo, se outros clientes fizeram inserções ou compras, tudo ficará atualizado automáticamente, em todos os Clientes, simultâneamente.