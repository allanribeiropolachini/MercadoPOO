Adriller Genova Ferreira 8922201
Allan Ribeiro Polachini 8922347
Hikaro Augusto de Oliveira 9066487

COMO EXECUTAR:
1- Primeiro deve ser executado o Servidor (MercadoServidor.jar) passando como argumento a PORTA
2- Com o Servidor sendo executado, j� � possivel executar quantos clientes quiser, para isso basta executar o MercadoCliente.jar, passando como argumento o NUMERO DE IP (host) e a PORTA

FUNCIONAMENTO:
Ap�s a executar o programa, um MENU ir� aparecer para todos os clientes conectados no servidor.
Quando o Cliente seleciona alguma a��o, � enviado um pedido para o servidor, retornando as informa��es necess�rias. Por exemplo, se o usu�rio quer listar todos os produtos, a aplica��o do Cliente envia um pedido, e o servidor retorna todos os nomes dos produtos.
Todos os cadastros de Usuario e de Produtos, sao automaticamente salvos na aplica��o do Servidor (com um arquivo CSV), dessa forma, mesmo que um usu�rio cadastre um novo produto, quando outro usu�rio, que est� utilizando o programa ao mesmo tempo selecionar para listar os produtos, o novo produto ja ficar� vis�vel.
E mesmo se um cliente finalizar um programa, quando ele executar de novo, se outros clientes fizeram inser��es ou compras, tudo ficar� atualizado autom�ticamente, em todos os Clientes, simult�neamente.