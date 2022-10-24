# Youtube-Automation

O objetivo desta automação é efetuar o download das músicas do Youtube em Mp3, já particionadas para o sistema de sinal eletrônico da Etec Itaquera II.
O sinal eletrônico funciona com um timer mecânico que desliga toca o sinal por 1minuto.
O algoritmo em Python faz o download do arquivo mp3, cria uma cópia sem os metadados com a extensão .new e em seguida, calcula o total de segundos da música.
Com o valor total, o algortimo divide a musicas em partes de 52 segundos e as exporta.
