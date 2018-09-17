# MicroMegaDrum
Código adaptado do MicroDrum oficial para ser usado em projetos MegaDrum.

O MegaDrum é um projeto de um módulo controlador de bateria eletrônica baseado no Arduino Mega,
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


