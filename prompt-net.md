Criando um usuário: 

	net user NOMEDOUSUÁRIO SENHA /add ; Para excluir: /delete

Adicionando a conta ao grupo de Administradores: 

	net localgroup Administradores NOMEDOUSUÁRIO /add

Ativar o Administrador no W10: 

	net user Administrador /active:yes

Trocar a senha do user: 

	net user NOMEDOUSUÁRIO *

Remover user do grupo de Administrador: 

	net localgroup Administradores NOMEDOUSUÁRIO /delete ; Para incluir: /add
