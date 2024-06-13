Exercício EC2 com adição de Volume

Passos:

1- Criação da Instância EC2 utilizando a imagem Amazon Linux 2 AMI<br/>
2- Conexão via ssh: ssh -i /path/da/chave {nome-da-maquina}@{ip-da-maquina}<br/>
3- Criação de um novo volume EBS e associação à instância;<br/>
4- Para listar o volume: $ lsblk<br/>
5- Para formatar: $ sudo mkfs -t ext4 /dev/xvdf<br/>
6- Para montar o volume: $ sudo mount /dev/xvdf /meu_diretorio<br/>

![alt text](image.png)<br/>

Com relação ao nome do volume, surge esse aviso quando você cria ele:<br/>

![alt text](image2.png)
