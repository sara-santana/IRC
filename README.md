# Projecto IRC - Gestor Municipal
Arquitetura Cliente-Servidor usando Python3

Para iniciar o desenvolvimento é necessário abrir uma consola para correr o servidor e até 5 consolas para correr o cliente usando os comandos python3 gestor_municipio_server e python3 gestor_municipio_client respetivamente.
A comunicação Cliente-Servidor é feita fia sockets TCP.

De modo a realizar as possíveis interações entre o cliente e o servidor, o cliente envia pedidos ao servidor.
Possiveis pedidos:

CONSULT_LOCAL - consultar um local;
	input: identificador do local
CONSULT_COMPLAINT - consulta de reclamações relativas a um local;
	input: identificador do local
CREATE_SERVICE - serviço criado disponivél num local;
	inputs: nome do serviço, identificador do local, tipo de serviço e preço
CHARGE - cobrar um serviço a um local;
	inputs: identificador do serviço e preço
END_SERVICE - terminar um servico;
	input: identificador de um serviço
EXIT - termina a coneção com o servidor.

