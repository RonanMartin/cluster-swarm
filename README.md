# cluster-swarm
Definição de um Cluster Swarm Local com o Vagrant

Projeto incrementado com shell script para baixar o apache e dados de site específico.
Também incluso trabalho de consistência de dados através do nfs-server.

Vagrantfile com 2 máquinas virtuais, uma master e outra node01; 
Cada máquina virtual com um IP fixo;
Ambas as MV possuem o Docker pré-instalado; 
A máquina com o nome de master é nó manager do cluster. 
A node01 entrou no cluster Swarm como Workers.
