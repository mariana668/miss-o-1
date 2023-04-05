# Missão Arduino

No referente arquivo, temos o link de um circuito simples do Tinkercad, com um LED programado para acender por períodos de tempo distintos.
Para a construção do projeto, foi necessário conectar a protoboard com duas portas da placa de arduino:
Uma delas, onde está escrito "5V" é responsável pela alimentação do sistema (fornecimento da corrente de elétrons) quando a simulação é iniciada.
A outra, a porta 2, serve como aterramento para garantir a diferença de potencial. 
A ideia do programa é que, quando a porta 2 é desconectada, a corrente deixa de passar e o LED apaga (e vice-versa).
É por isso que o código foi escrito de modo a controlar o tempo de conexão da porta 2.
O código é transmitido à placa de arduino que obedece o algoritmo.
