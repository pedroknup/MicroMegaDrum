# MicroMegaDrum

English below.

Código adaptado do MicroDrum oficial para ser usado em projetos MegaDrum.

O MicroMegaDrum é um projeto de um módulo controlador de bateria eletrônica baseado no Arduino Mega,
que possui 16 entradas analógicas.

O projeto Microdrum é baseado no Arduino UNO, que possui 6 entradas analógicas e utiliza 
circuitos multiplexadores para aumentar para até 48 entradas analógicas.

O objetivo aqui é portar o projeto MicroDrum para funcionar no projeto MegaDrum. Para
tanto, foi necessário modificar o código para a utilização do Arduino Mega com 16 entradas
sem o circuito multiplexador adicional.

Adicionado a leitura de pinos digitais para choke dos pratos e sons adicionais.

*MegaDrum* agora é TeensyDrum!
Confira o repositório oficial: 
https://github.com/massimobernava/md-firmware/tree/teensy-firmware/sketch_microdrum

----

Code adapted from the official MicroDrum for use in MegaDrum projects.

MicroMegaDrum is a design of an Arduino Mega based electronic drum controller module that has 16 analog inputs.

The Microdrum project is based on Arduino UNO, which has 6 analog inputs and uses multiplexer circuits to increase up to 48 analog inputs.

The goal here is to port the MicroDrum project to work on the MegaDrum project. Therefore, it was necessary to modify the code to use the Arduino Mega with 16 inputs without the additional multiplexer circuit.

Added digital pin readout for cymbal choke and additional sounds.

MegaDrum is now TeensyDrum! Check out the official repository: https://github.com/massimobernava/md-firmware/tree/teensy-firmware/sketch_microdrum


