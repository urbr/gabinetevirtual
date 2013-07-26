Drupal 7 + Composer + Banco de Dados
===============

Descrição: Instalação básica do Drupal 7.22

Instalação:
===============
	1 - Restaurar o DUMP do banco de dados que encontra-se na raiz com o nome 'database.tar.gz'. 
		Comando: psql dbname < db.sql

	2 - Rodar o composer para instalar o módulo do gabinete virtual e o seu tema.
		Comando: php composer.phar install

	3 - Abilite os módulos: "Formulário Oficina de Criação" e "Gabinete Virtual" na aba "Módulos" do Drupal.

	4 - Configure os parâmetros do Gabinete Virtual na aba "Configurações" do Drupal.

Mais Informações
===============
Software mantido por Urucum Brasil
http://www.urucumbrasil.com.br
