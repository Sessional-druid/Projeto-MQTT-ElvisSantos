# Projeto-MQTT-ElvisSantos
 Repositório criado para armazenar informações sobre o projeto.
## Objetivo:
O objetivo do projeto é monitorar a porta de um rack usando um Sensor Magnético que funcionará em conjunto com um Arduino Uno, verificando o estado do rack (Aberto ou Fechado) e, enviar a informação via internet utilizando o protocolo MQTT, para um servidor MQTT hospedado na AWS que exibirá a informação para o app MQTT DASH (cliente MQTT) em um smartphone, como na imagem abaixo:

## Topologia:
![Topologia](https://github.com/Sessional-druid/Projeto-MQTT-ElvisSantos/blob/main/Projeto-MQTT.jpg?raw=true)

foram utilizadas as seguintes bibliotecas:

UIPEthernet (Conexão do ENC28J60 com arduino)
PubSubClient (Cliente MQTT para o arduino)

## Materiais:
- Arduino Uno
- Módulo Ethernet (ENC28J60)
- Sensor Magnético (MC-38)
- Jumpers

## Circuito:
![](https://camo.githubusercontent.com/ad1da211b35b60b23fb095a64e76dc6504d0c3229e853bd82a69a4d5d27bbb88/68747470733a2f2f692e696d6775722e636f6d2f594947477453472e706e67)

## Aviso:
No caso de usar o iphone para realizar o projeto, o app que deve ser utilizado é: MQTTool.

que pode ser encontrado na App store ou no link abaixo:

https://apps.apple.com/us/app/mqttool/id1085976398
