# Projeto-MQTT-para Arduino Uno

Projeto MQTT-Arduino Uno mais um Sensor Magnético para monitorar se a porta de um Rack de Rede está Aberto ou Fechado,enviar essa informação via internet utilizando protocolo MQTT( Message Queuining Telemetry Transport),para um servidor MQTT hospedado na Amazon Web Service(AWS),e exibir a informação em um cliente MQTT(MQTTDash),instalado em um smartphone conforme imagem abaixo:
![Projeto MQTT](https://i.imgur.com/8AzTkk6.png)


Foram utilizadas as seguintes bibliotecas:
.UIPE (conexão do modulo ethernet ENC28J60 com Arduino)
.PubSubClient(cliente MQTT para Arduino)

Materiais:
.Arduino Uno
.Modulo Ethernet(ENC28j60)
.Sensor Magnético(MC-38)
.Jumpers

![CIRCUITO](https://i.imgur.com/U5lKK2E.png?1)















