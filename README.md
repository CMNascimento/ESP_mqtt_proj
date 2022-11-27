# ESP_mqtt_proj

Projeto realizado partindo do exemplo do protocolo MQTT do ESP-IDF. Para o desenvolvimento do projeto foram utilizados uma ESP32, um LED vermelho, um fotoresistor, resistores do tipo PTH(220ohms em série com o LED, e 100k ohms e 10k ohms em série com o fotoresistor), e um dashboard desenvolvido no MQTT Dash. 

O programa comportasse da seguinte maneira:

I) O LED pode ser acionado manualmento através do dashboard;

II) O acionamento pode ser realizado de forma automática através de um valor selecionado da tensão obtida no fotoresistor. 

Imagens do dashboard no MQTT Dash:

![WhatsApp Image 2022-11-27 at 18 51 11 (1) C](https://user-images.githubusercontent.com/89278224/204162047-436e944b-ae3f-48a8-ac33-7598645da3f4.jpg)
![WhatsApp Image 2022-11-27 at 18 51 11 C](https://user-images.githubusercontent.com/89278224/204162054-8b11f6b9-4846-4dad-ad5f-e64d4427d79d.jpg)


Versão do ESP-IDF: 4.4.2
