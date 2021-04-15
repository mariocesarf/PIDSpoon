# PIDSpoon

O PIDSpoon é um projeto de sistemas microprocessados que visa implementar um algoritmo de controle PID e de tratamento de sinais como a media movel para o desenvovimento de uma colher que possa ajudar a alimentação de pacientes com limitações motoras na mão.

## Motivação

Temos como motivação do desenvolvimento do PIDSpoon a reprodução de um modelo comercial de uma colher motorizada para alimentação de pessoas que possuem condições que dificultem a alimentação devido a movimentos irregulares dos braços ou mãos, condição muito comum em pacientes com sindrome de Parkinson.

## Componentes
O projeto utilizará os seguintes componentes:
* MPU6050
* STM32F103C8T6 
* 2 micro servo motores

## Background

O algoritmo PID busca minimizar um erro a partir da ação em uma atuador agindo baseado em dados de um sensor, já a media movel busca reduzir ruidos e oscilações que possam atrapalhar a medição do valor real do sensor.

## Link para apresentação
