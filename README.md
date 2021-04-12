# Temperature_Controller_DC_Fan
Projeto final da disciplina de Microprocessados 2020.2

OBJETIVOS:

O objetivo principal desse projeto é desenvolver um sistema que automaticamente liguei ou mantenha desligada uma Fan DC dependendo da temperatura presente no ambiente. Alcançada uma certa temperatura, a Fan DC é ligada, caso contrário, ela permanece desligada.
Como objetivo secundário, é mostrada a temperatura atual no sistema, com o intuito de ser um informativo para aqueles que venham a necessitar.  

FERRAMENTAS UTILIZADAS:

- STM32CubeIDE 1.6.0 : Para criação dos códigos
- Proteus 8 : Para simulação do sistema

**Apresentar esquemático**

O projeto tem por princípio a conversão de um sinal analógico para digital para, então, seguir para seus respectivos destinos.

O sistema conta com um sensor de temperatura LM35 para fornecer o sinal analógico e de um ADC interno ao microcontrolador para fornecer o sinal digital.

COMPONENTES:

- Microcontrolador STM32F103C6
- 16 X 2 LCD Display
- LM35
- 2 x 10KΩ resistores
- BC547
- Relay 12V
- Diodo 1N4007 
- Potenciômetro 10KΩ
- Voltímetro DC
- Fan DC

FUNCIONAMENTO:

O LM35 gera uma tensão referente a temperatura atual fornecida. Essa tensão chega ao microcontrolador através de uma porta e, então, por meio de um ADC interno há a conversão para um sinal digital. 

Para o problema testado no sistema, a temperatura limite foi tomada com 50°C e ao passar dessa temperatura a Fan DC seria ligada, senão continuaria desligada, e para toda fonte de alimentação foi tomado o valor de 3,3V. 

Em paralelo a isso, ao crescer e decrescer da temperatura no LM35, é mostrado no LCD a temperatura atual.

RESULTADOS:

Quanto 
- 

Link do vídeo explicativo sobre o projeto: https://www.youtube.com/watch?v=4EThGuIC_vk&ab_channel=PedroHenrique.

