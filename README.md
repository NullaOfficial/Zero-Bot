# Zero-Bot

# Indice
Materiales------------------------1

Descripcion de componentes--------2

Diagrama de cableado--------------3

Modelado 3D/Construccion----------4

Programacion----------------------5

Resumen---------------------------6

Conclusiones----------------------7

Recomendaciones-------------------8

Trabajos futuros------------------9

# Materiales

| Materiales | Cantidad | Precio | Precio Total |
|:-------|:-:|:-:|--:|
| MegaPi | 1 | 0 | 0 |
| DC Motor Driver V1.0 | 1 | 0 | 0 |
| Motores DC de mBlock | 2 | 0 | 0 |
| HC-SR04 | 1 | 0 | 0 |
| Ball Caster | 1 | 0 | 0 |
| Baterias 18650 | 2 | 0 | 0 |
| Jumpers | (suficientes) | 0 | 0 |
| Ruedas  | 2 | 0 | 0 |
| Chasis | 1 | 0 | 0 |

# Descripcion de componentes

-MegaPi: Es una placa basada en Arduino Mega 2560 (utiliza el microcontrolador ATmega2560), lo que le otorga una gran cantidad de puertos de entrada/salida (I/O) y una alta capacidad de procesamiento.

-Motores DC de mBlock: Motores de Corriente Continua (DC) que convierten la energía eléctrica en movimiento rotacional. Si son específicos de mBlock/Makeblock, a menudo vienen con un reductor integrado (engranajes) y pueden tener terminales de conexión diseñados para los puertos de la MegaPi.

-HC-SR04: Un sensor de rango que utiliza ondas ultrasónicas para medir distancias.

-Jumpers: Cables delgados con conectores en los extremos (macho/hembra) que se utilizan para interconectar componentes electrónicos.

# Diagrama del cableado

<img width="800" src="https://github.com/user-attachments/assets/03bad444-3841-421e-a85f-5e27aee990e9">

# Modelado 3D/Construccion

Se empezo creando la base del carro incluyendo los soportes para los componentes electronicos con huecos para el chasis, después se crea el chasis agregandole partes para incrustarse a la base.

# Resumen

El proyecto Zero-Bot documenta el diseño y la implementación de un robot móvil de tracción diferencial. Utilizando la placa MegaPi como controlador principal y un sensor HC-SR04 para la percepción, el bot fue programado para evitar obstáculos automáticamente. El chasis, diseñado en CAD, integra los dos Motores DC de mBlock, la MegaPi y la fuente de alimentación (Baterías 18650), proporcionando una plataforma estable y compacta para la locomoción autónoma.

# Conclusiones

El objetivo de crear un robot evasor de obstáculos fue cumplido. La MegaPi demostró ser una plataforma robusta, especialmente en el manejo de múltiples motores.

# Recomendaciones

Sustituir las 18650 por una fuente de alimentación con mayor tasa de descarga.

# Trabajos futuros

Crear un coche para la categoria de Futuros Ingenieros de la WRO (World Robotics Olympiad) con mi equipo.
