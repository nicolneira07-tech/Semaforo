# Semáforo con Arduino Mega

Proyecto de simulación de un semáforo utilizando Arduino Mega 2560 y tres LED.

## Materiales
- Arduino Mega 2560
- Protoboard
- LED rojo, amarillo y verde
- Tres resistencias de 220–330 Ω (recomendadas)
- Cables de conexión

## Conexiones
| LED | Pin | Duración |
|---|---|---|
| Rojo | 10 | 6 segundos |
| Amarillo | 9 | 3 segundos |
| Verde | 8 | 6 segundos |

Conecta cada LED mediante su resistencia y el cátodo a GND.

## Funcionamiento
Verde → amarillo → rojo → amarillo. La secuencia se repite continuamente.

## Código
[semaforo.ino](semaforo/semaforo.ino)

## Uso
Abre el archivo en Arduino IDE, selecciona Arduino Mega 2560 y carga el programa.
