# estacao_metereologica
Projeto para Criação de Estação Metereológica para medir Temperatura e Umidade através de sensores em um Arduino Uno R3.
Objetivo Secundário: Enviar as informações coletadas pelo Arduino para uma API na AWS.
Outros Objetivos: Disponibilizar uma interface para consulta da temperatura e suas médias.

Utiliando um sensor DHT-22 para a coleta de temperatura e umidade, os dados são coletados e exibidos na tela

Bibliotecas Utilizadas:
- Arduino - Sensor DHT - Umidade e Temperatura
- Adafruit Unified Sensor Library: https://github.com/adafruit/Adafruit_Sensor
 
# Esquema de ligação da prática  
Conexão do Sensor DHT-22

Sensor >> Arduino
- pino 1 >> 5v
- pino 2 >> GND
- pino 3 >> null
- pino 4 >> pino 2
