# FINDER_OPTA_002
# C++

O projeto consiste em criar um rede Cliente e Servidor com o Finder OPTA. Neste caso, este projeto é composto por 4 OPTAs, sendo um deles o modelo Advanced e os outros três o modelo Lite. O OPTA Advanced atua como um Cliente, pois solicita leituras dos OPTA Lites. Temos então uma comunicação Modbus TCP/IP entre os produtos, com os três OPTA Lites visando ler sinais de 0-10V em suas entradas e o mesmo sinal lido nas entradas será espelhado nas portas dos módulos de expansão analógicos. Então se o OPTA estiver lendo 3V em uma das entradas, as portas do módulo de expansão também terão saída de 3V. O OPTA Advanced recebe esses dados dos três OPTA Lites e essas leituras são disponibilizadas no Arduino IoT Cloud.

A configuração dos módulos de expansão foi feita da maneira mais simples possível para ficar fácil e didático, assim sendo possível a compreensão com maior facilidade. É possível otimizar essa programação por completo, mas pensando em compreensão ao público final, foi deixado de maneira simples.


