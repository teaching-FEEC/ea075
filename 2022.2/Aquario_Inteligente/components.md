# `Componentes `

- [Microcontrolador ESP32](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32_datasheet_en.pdf)

O microcontrolador ESP32 foi escolhido pois possui conexão Wi-fi, pinos de GPIO que atendem o propósito utilizado no projeto (sensores e atuadures) e um ótimo custo benefício. Pode ser gravado utilizando o próprio IDLE do Arduino

- [Sensor de Temperatura DS18B20](https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)

O sesnor de temperatura foi escolhido devido seu range de tempetatura (-55°C a 125°C) e sua acurrácia de + ou - 0.5°C. Além disso, é um sensor que pode ser colocado na água.

- [Sensor de nível](https://www.tecnopartes.com.br/pdf/chave-boia-icos-la16m40.pdf)

O sensor de nível foi escolhido baseado em outros projetos em aquário, tais como o da referência, pois apresenta tamanho compacto, pode ser utilizado em água e tem ótimo custo benefício.

- [Sensor de luminosidade GL5528](https://www.filipeflop.com/img/files/download/Datasheet_LDR.pdf)

O sensor de luminosidade foi utilizado devido seu range, dado que um ambiente residencial possui em torno de 75 a 750 lux, sendo sua sensibilidade de 10 a 100 lux, podendo idendificar um ambiente sem luminosidade como o desejado.

- [Sensor de turbidez CUS52D](https://bdih-prod-assetcentralapi-assetcentral-rest-srv.cfapps.eu10.hana.ondemand.com/files/DLA/005056A500261EEAB3B3A041579CD7D4/TI01136CPT_0620.pdf)

O sensor de turbidez foi escolhido devido sua aplicação para medição de turbidez em monitoramento de filtro, assim como os utilizados em aquário.

- [Micro Servo Motor 9g Tower Pro SG9010](https://www.kjell.com/globalassets/mediaassets/701916_87897_datasheet_en.pdf?ref=4287817A7A)

O servo motor foi escolhido devido seu controle de rotação e seu pequeno tamanho. Assim, torna-se possível controlar um recipiente para que abra e feche, dosando a quantidade de ração despejada.

- [Regulador de Tensão AMS1117 5V 1A](http://www.advanced-monolithic.com/pdf/ds1117.pdf)

O regulador de tensão foi utilizado para fazer a conversão de 5V para 3.3V, pois grande parte dos sensores utilizam alimentação de 5V e o Microcontrolador apresenta tensão de alimentação de 3.3V.

- [Mini Fonte 5V HLK-PM01 100-240V](https://www.filipeflop.com/img/files/download/Datasheet-HLK-PM01.pdf)

A mini fonte de 5V foi utilizada para acionar os periféricos que utilizam tensão de alimentação de 127V.
