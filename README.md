# WordPress-docker-mysql
Guia instalação do wordpress no docker

utilizando uma maquina linux ubuntu-16.04 lts na aws(Amazom)

1*
sudo apt-get update

2*
sudo apt-get install docker-compose

3*
sudo apt-get install git

4*
git clone http://github.com/concrete-cristian-trucco/wordpress-mysql-compose.git

5*
navegar ate o local do download, normalmente um "cd /wordpress-mysql-compose" resolve.

6*
Após entrar no diretorio, editar a porta desejada no arquivo "docker-compose.yml", após a configuração rodar o comando "docker-compose up" para subir a instancia/imagem "wordpress" que vai poder ser acessada pelo "http://localhost" 

ps: dependendo da porta que estiver configurado o wordpress sera necessario adcionar a porta ao final exemplo com a porta 8080
"https://localhost:8080/wp-admin/"

7*
Partir pro abraço e seja feliz
