# README-de-Todo-o-Projeto
o projeto tem dois sistemas de login: um para cliente e outro para administrador (adm).
Cada um tem sua própria página de login que redireciona para uma área específica após o login bem-sucedido.

Login do Cliente
Arquivo: login_cliente.html

Campos: Usuário e Senha

Processo:
O formulário envia os dados via fetch para /login-cliente.
Se o login for válido (response.ok), o usuário será redirecionado para home_cliente.html.
Se inválido, aparece um alerta.

Login do Administrador
Arquivo: login_adm.html

Campos: Usuário e Senha

Processo:
O formulário envia os dados via fetch para /login-adm.
Se o login for válido (response.ok), o usuário será redirecionado para /home-adm.html.
Se inválido, aparece um alerta.


O projeto separa clientes e administradores, cada um com login e área própria, mas depende de um backend e banco de dados para funcionar corretamente.


o projeto em si é um site que contém um sistema de pesquisa onde o ADM cria perguntas para o cliente responder para uma pesquisa.


foram usados ​​para o projeto JS,CSS,Postgres,Node,JSON,Front,Back.
