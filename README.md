# PIDSpoon

O PIDSpoon é um projeto de sistemas microprocessados que visa implementar um algoritmo de controle PID e de tratamento de sinais como a media movel para o desenvovimento de uma colher que possa ajudar a alimentação de pacientes com limitações motoras na mão.

O projeto utilizará os seguintes componentes:
* MPU6050
* STM32F103C8T6 
* 2 micro servo motores

O algoritmo PID busca minimizar um erro a partir da ação em uma atuador agindo baseado em dados de um sensor, já a media movel busca reduzir ruidos e oscilações que possam atrapalhar a medição do valor real do sensor.
