# Atividade Vagrant  
  
**Curso:**: MBA Full Stack Developer  
**Disciplina:** Infrastructure And Cloud Computing  
**Professor:** João Henrique Victorino da Silva  
**Instituição:** Impacta  
  
## Projeto: Atividade Vagrant  
  
Este repositório contém um projeto Vagrant para ser entregue como atividade de avaliação.  
  
O intuito é subir uma máquina virtual com MySQL instalado e que esteja acessível no host da máquina na porta 3306.  
  
Vale ressaltar aqui que utilizei como exemplo, o projeto disponibilizado pelo professor no seguinte diretório github:  
> **https://github.com/joaovictorino/vagrant-spring**    
  
O projeto foi implementado com `Vagrant 2.2.14`  
  
Como teste, pode-se utilizar os comandos abaixo (ou qualquer variação válida dos mesmos) na máquina host:
```
mysql -D petclinic -u petclinic -h localhost -P 3306 --password=petclinic
mysql -D petclinic -u petclinic -h 10.80.4.10 -P 3306 --password=petclinic
```
ou
```
mysql -D petclinic -u petclinic -h 10.80.4.10 -P 3306 -p
mysql -D petclinic -u petclinic -P 3306 -p
Password: petclinic
```