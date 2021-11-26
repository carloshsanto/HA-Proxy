# SCRIPT de criação de ambiente WEB em container

* Requisito:
	* Instalaçao do Docker
	* Criar os diretórios abaixo. Caso não 
		* /home/suporte/resources <- LOCAL ou NFS-Storage
		* /home/suporte/resources/portainer
		* /home/suporte/resources/haproxy/certs
		* /home/suporte/resources/letsencrypt/log
		* /home/suporte/resources/nginx/conf
		* /home/suporte/resources/nginx/log
		* /home/suporte/resources/nginx/www/default
		* /home/suporte/resources/nginx/www/site....

* Os arquivos deploy_*.sh devem possuir permissão 755.

* Executar o arquivo deploy_portainer.sh.

* Executar o arquivo deploy_nginx.sh.

* Executar o arquivo deploy_haproxy.sh.

* Executar o arquivo deploy_certbot.sh.	<- Não é requisito inicial de funcionamento


OBs.: Foi disponibilizado arquivos de configuração com ajustes iniciais, altere conforme seus requisitos.
