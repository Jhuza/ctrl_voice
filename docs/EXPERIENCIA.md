# Control por voz

Transcribe una orden hablada y la publica como mensaje MQTT.

- Entrada: Voz capturada por el navegador.
- Resultado: Transcripción y publicación JSON en el tópico controlVoz.
- Tecnología: Web Speech API · Paho MQTT

## Uso

Prepara el receptor, pulsa Escuchar y permite el micrófono. La transcripción se envía al broker configurado.

## Límites

Requiere navegador compatible, micrófono y broker. El receptor determina qué acción corresponde al texto.

## Evidencia de ejecución

La ficha describe el funcionamiento del código. Una ejecución del modelo o una conexión a un dispositivo debe documentarse con su entrada, resultado observado y captura real; no se presentan resultados simulados como evidencia académica.

[Demo](https://ctrlvoice-8xolwmsfbocxfhpr9znjmh.streamlit.app/) · [Código](https://github.com/Jhuza/ctrl_voice)
