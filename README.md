# ID5933-ieeelatam
Arquivos e dados adicionais relacionados ao artigo ID5933 - IEEE Latin America Transactions

Este repositório contém os códigos dos módulos de comunicação e dados experimentais coletados e utilizados no artigo "Improved Indoor 3D Localization using LoRa Wireless Communication" (ID5933) do IEEE Latin America Transactions.
/*Adicionar link de acesso ao artigo após publicação*/

Dados experimentais:

Cada uma das abas da planilha (Lab P1, Lab P2, Lab P3, Quadra P1, Quadra P2 e Quadra p3) apresentam os dados coletados em cada um dos experimentos descritos no artigo.
Para cada experimento são apresentados os seguintes dados:
- valor de RSSI (dBm) transmitido por cada nó fixo (RSSI 1 , RSSI 2 e RSSI 3)
- valor da altitude (m) do nó móvel localizável (Altitude)
- valor da altitute da coordenada de referência (Altitude Nível Zero)
- valor unitário do RSSI de cada ponto a um metro de distancia do ponto móvel, correspondete ao paramatro A da Equação do artigo (A1, A2 e A3). Medido - correspondem aos valores originais e Melhorado - correspondem aos valores após o aprimoramento descrito no artigo 
- coordenadas reais de uma posição 3D de teste de localização (Ponto X Y Z)

Códigos dos módulos de comunicação:

A solução é composta por 5 módulos de comunicação sem fio LoRa modelo ESP32 LoRa (V2) do fabricante Heltec Automation (https://heltec.org/project/wifi-lora-32/) conforme mostrado na Figura 1 do artigo. 
Cada um dos código fonte compilados para esses 5 módulos estão disponíveis: 
- Nó Concentrador fixo;
- 3 Nós Localizadores fixos (LocalizadorF1, F2 e F3);
- Nó Localizável móvel;
