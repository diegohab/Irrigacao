# Irrigacao 1.0
Este é um projeto para automatização de um sistema de irrigação, desenvolvido no primeiro semestre de Eng. Elétrica na Unesp de Ilha Solteira, nele serão implementados conceitos de Controle, Automação, IoT, programação em Python e em C++.
Inicialmente, gostaria de deixar claro que este não é o método mais barato e eficaz de se produzir algo do tipo. Entretanto devido a fatores externos, este foi o modo escolhido para o desenvolvimento.
Enfim, a partir dos conceitos explicitados acima, e dos seguintes itens, desenvolveu-se o projeto.

## Itens Usados
###### Raspberry Pi 3 B+                           
###### Módulo frequência de rádio 433MHz
###### Arduino Uno                                  
###### Contator 70 amperes
###### Módulo Relé                                  
###### Relé termico
###### Sensor de umidade do solo
#
A princípio dividi o projeto em duas partes, na primeira ficam o Raspberry, o módulo emissor de frequência de rádio e o sensor de umidade do solo, os dois últimos ficam acoplados ao primeiro da seguinte forma:

![Alt Text](https://raw.githubusercontent.com/T635/Irrigacao/master/Imagens/Circuito%20raspberry.png)

Na segunda parte foram usados o Arduino e nele acoplados o módulo de relé, módulo receptor de frequência de rádio, o relé termico, o contator e o motor da irrigação da seguinte forma:
