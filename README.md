# Atividade Vagrant  
  
**Curso:**: MBA Full Stack Developer  
**Disciplina:** Infrastructure And Cloud Computing  
**Professor:** João Henrique Victorino da Silva  
**Instituição:** Impacta  
  
## Projeto  
  
Este repositório contém um projeto Vagrant para ser entregue como atividade para avaliação.  
  
O intuito é subir uma máquina virtual com MySQL instalado e que esteja acessível no host da máquina na porta 3306.  
  
Vale ressaltar aqui que utilizei o exemplo disponibilizado pelo professor no diretório github:  
* **https://github.com/joaovictorino/vagrant-spring**    
  
O projeto foi implementado com Vagrant na versão 2.2.14  
  
Como teste, pode-se utilizar os comandos abaixo (ou qualquer variação válida dos mesmos) na máquina host:  
* **mysql -D petclinic -u petclinic -p petclinic -h localhost -P 3306 --password=petclinic**  
  .
* **mysql -D petclinic -u petclinic -P 3306 -p**  
* **Password:** petclinic  

*Obs.: Conforme entendi a atividade, o acesso ao banco de dados na maquina virtual deve se dar pelo "localhost" da máquina host. Sendo assim, não defini nenhum IP ao fazer o binding de portas entre o guest e o host (vide **Vagrantfile**)*
