# Acesso SSH no EC2

## Introdução
  Neste repositório, documento a criação de uma instância de máquina virtual EC2 na AWS e o acesso a ela via SSH.
  
## Objetivo
  O objetivo é demonstrar o processo de provisionamento na nuvem da AWS e o acesso por SSH, utilizando a ferramenta PuTTY.
  
## Materiais
  AWS e PuTTY.
  
## Método
  Primeiramente, é preciso criar uma instãncia EC2 na AWS, selecionar o sistema Amazon Linux, configurar uma chave .ppk e executá-la. Com isso, é realizado o download da chave de acesso e a instância é executada.
  
  ![image](https://github.com/IsraelNLC/semana3-ec2/assets/99210055/9489382b-11d7-4ad5-a6d6-3ef04a5da30b)
  Console AWS com a instância em execução

  Após isso, eu utilizei o PuTTY para conectar o SSH. 

  ![image](https://github.com/IsraelNLC/semana3-ec2/assets/99210055/37de4137-52ee-4981-a6e2-cfc69c962968)
  
  Interface do putty
  
  ![image](https://github.com/IsraelNLC/semana3-ec2/assets/99210055/374b9e21-5151-4f9b-aadf-799e5bdfdafc)
  SSH conectado com sucesso!

## Resultados
  Consegui criar a instância e conectar o SSH com sucesso.
  
## Conclusão
  Através dessa atividade, pude me familiarizar mais com a cloud computing na prática e com a conexão SSH.

## Refeências
  https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/putty.html (documentação putty AWS)
  https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html (download PuTTY)
