# CSF-TP4 - Parte 2

Um PDF com uma cópia da lista de exercícios passada em sala de aula (Parte 1 desta atividade) também se encontra neste repositório.

Neste exercício iremos calcular a perda no ar (Path Loss), potênica de transmissão e capacidade do canal LoRa.

Os códigos contidos neste git são os mesmos usados na última atividade prática. Eles devem ser modificados para calcular o RSSI e o SNR da comunicação.

As seguintes perguntas devem ser respondidas:

1) Para as potências de transmissão 5, 10, 15 e 20 (dBm), qual a potência efetiva irradiada? Responda em dBm e mW. Considere o ganho das antenas acopladas e desconsidere as perdas das conexões usadas até a antena.

2) Usando o RSSI no receptor. Qual foi a perda no ar de cada transmissão feita na questão anterior? Responda em dBm/metro e mW/metro.

3) Alterando os valores do parâmetro Spread Factor (SF), altera-se o RSSI no receptor? Caso haja uma alteração, explique como o parâmetro SF afeta os cálculos.

4) Usando a SNR no receptor. Calcule a capacidade do canal para as Larguras de Banda 125, 250 e 500 kHz.

5) Alterar os parâmetros potência de transmissão e SF afetam o cálculo da capacidade do canal? Explique.

## Informações Úteis

* Explicação de como é calculado o RSSI, em dBm:

![Explicação RSSI retirada de https://lora.readthedocs.io/en/latest/#rssi](/img/rssi.png)

* SNR é calculado em dB.

* O ganho das antenas que vieram com os ESP32 (Heltec WiFi LoRa 32 v3) é de 5 dBi.
