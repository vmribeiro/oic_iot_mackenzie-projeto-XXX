# Objetos Inteligentes Conectados 1 sem. 2018

Turma 5J11

Projeto: "Sensor de umidade de solo com botão de irrigação via Twitter".

Objetivo: Fazer um equipamento com arduíno que utilize um sensor de umidade de solo, de modo que quando o solo não estiver úmido envie uma notificação via e-mail, para que então possamos enviar uma mensagem via twitter que ativará um micro servo que derrubará uma pequena quantidade de água no solo para melhorar a umidade do solo.

## Integrantes do grupo:
•	Jéssica Yumi – TIA: 41531345
•	Gustavo Oliveira – TIA: 41505565
•	Victor Ribeiro – TIA: 41519485

## Problema
Descrição do problema: pessoas que possuem plantas precisam de tempo e dedicação para cuidá-las, seja no aspecto de luz, temperatura e umidade. Caso ela viaje ou saia constantemente, aquelas plantas que necessitam de constantes irrigações acabam ficando secas e morrem por não terem o cuidado suficiente. 
Quem é afetado pelo problema: cultivadores de plantas e/ou hortas caseiras.
Benefícios de uma boa solução: é possível tomar conta das plantas e evitar de deixá-las secas com este equipamento que regará via Twitter caso estejam com pouco umidade no solo, mesmo se estão longe da plantação. Além de otimizar o tempo do cultivador para cuidá-las.

## Interessados
•	Pessoas com plantas e/ou hortas caseiras.

## Usuários
•	Pessoas que possuem plantas e saem constantemente.
•	Cultivadores de plantas.

## Funcionalidades do produto
•	Medidor com sensor de umidade do solo da planta.
•	Envio de email quando o solo está com a umidade abaixo da média.
•	Envio de mensagem via Twitter que irá ativar o microservo que irá derrubar um pequeno copo de água na planta.
 
## Restrições do projeto
•	Deve cobrir uma área pequena.

## Requisitos
•	A terra que será usada deve estar nas condições necessárias para a verificação do sistema (úmida ou seca).
•	O projeto deve ser feito em pequena escala, de preferência em um vaso de planta caseiro.
•	O projeto deve ser feito utilizando Node-RED.
•	O projeto deve usar o protocolo firmata para comunicação com o computador (conexão com o Node-RED).

## Protocolos de comunicação
•	Firmata.

# Descrição de Hardware

## Materiais: 
•	Micro servo.
•	Sensor de umidade do solo.
•	Arduíno Uno R3.
•	Jumpers.
•	Protoboard 830 pontos.
•	Copo pequeno de plástico.
•	Recipiente com terra.

## Plataformas de desenvolvimento:
•	Node-RED.

_______________________________________
# Obervações:

## DescricaodeHardware.pdf: Contém também as imagens dos modelos. 
## Interfaces_e_comunicação: Contém as interfaces e protocolos utilizados.
## docs/1-visao/ : Contém o documento de visão e protótipos.
## docs/2-casos-de-uso/ : Contém o diagrama e especificação de casos de uso.
## src/ : Contém os códigos desenvolvidos.
