# 1- Mobilidad y diseño

- ### Opciones de diseño:

	| Foto | Descripción | Nombre |
	|---|---|---|
	| a | a | Cyber Cooper |
	| a | a | Cooper |
	| a | a | Halbi |
	| a | a | The Fridge |

 - ### Halbi The Green:

    * ### Foto:

	<div align="center">

	<img width="560" height="580" alt="604003001-cc130bf0-8547-48cc-847e-28dbd9029fba" src="https://github.com/user-attachments/assets/f1dc12a1-dbfc-46f3-9a21-a679aa1aa3db" />

	</div>

	* ### Dirección:

		- Ackerman: La dirección Ackermann es una configuración geométrica utilizada en el sistema de dirección de vehículos (desde automóviles convencionales hasta robots con ruedas) para resolver el problema de que las ruedas giren en ángulos 					diferentes cuando el vehículo toma una curva. En un sistema de dirección simple (donde ambas ruedas giran exactamente el mismo ángulo), la rueda interna arrastra y patina. La geometría Ackermann evita esto, logrando que el vehículo gire de 			forma suave, sin derrapes y reduciendo drásticamente el desgaste de los neumáticos.

			Aunque el sistema lleva el nombre de Rudolph Ackermann, él no fue el inventor, sino el promotor.

			El origen (1816): El diseño original fue inventado en Munich por el constructor de carruajes alemán Georg Lankensperger. Su objetivo era evitar que los carruajes de caballos volcaran o arrastraran las ruedas al girar en esquinas cerradas.

			La patente (1818): Rudolph Ackermann, un editor y empresario inglés que vio el potencial del invento, compró los derechos para el mercado británico y patentó el diseño en Inglaterra en 1818. Debido a esto, la configuración se popularizó en 			todo el mundo anglosajón bajo su nombre.

			Era moderna: Con la llegada de los automóviles a finales del siglo XIX, el principio de Ackermann pasó de los carruajes a los coches autopropulsados y, hoy en día, sigue siendo la base geométrica de casi cualquier vehículo de cuatro ruedas, 			incluidos los chasis de robótica móvil.

			Cuando un vehículo toma una curva, la rueda que queda en el interior de la curva recorre un círculo más pequeño (un radio más corto) que la rueda que queda en el exterior. Para que ambas ruedas giren limpiamente sin oponerse entre sí, todas 			las ruedas del vehículo deben girar alrededor de un mismo punto central común (llamado Centro Instantáneo de Rotación o ICR). Para lograr esto:

 			#### 1. La rueda interna debe girar un ángulo más cerrado.

			#### 2. La rueda externa debe girar un ángulo más abierto

		- Uso: En el contexto del proyecto, implementamos este sistema mecánico para controlar el guiado del robot mediante un único servomotor central acoplado a un varillaje asimétrico. A diferencia de los sistemas de tracción diferencial (donde el 			giro se logra variando la velocidad de las ruedas laterales), la geometría Ackermann nos permite replicar la conducción de un automóvil real, garantizando trayectorias fluidas, mayor estabilidad a altas velocidades y un control preciso en curvas 		cerradas. Esto resulta fundamental para optimizar los algoritmos de navegación autónoma y seguimiento de líneas en entornos competitivos.

		<div align="center">
		<img width="1800" height="1100" alt="Angulo-Ackermann-dibujo" src="https://github.com/user-attachments/assets/58cf9434-8c1e-4c22-8b9f-8c61ecde4aa3" />
		</div>

	* ### Transmisión:

		- Velocidad:

		- Peso:

		- Torque:

	* ### 3D Printed Parts:

		- Impresora:

		- PETG vs PLA:

| PETG | PLA |
|---|---|
| El Polietileno Tereftalato Glicol (PETG) es un termoplástico derivado del petróleo, modificado con glicol para evitar la cristalización y fragilidad del PET común. Combina la facilidad de impresión del PLA con la resistencia mecánica del ABS. Se caracteriza por su excelente tenacidad, resistencia al desgaste químico y capacidad de absorber impactos mediante una ligera flexión elástica, lo que lo hace ideal para componentes funcionales. | El Ácido Poliláctico (PLA) es un termoplástico 		biodegradable de origen natural (derivado del almidón de maíz o caña de azúcar) ampliamente utilizado en impresión 3D por su facilidad de uso. Destaca por su alta rigidez estructural y mínima contracción térmica al enfriarse, lo que permite fabricar 	piezas con tolerancias geométricas muy precisas y sin deformaciones. Sin embargo, su naturaleza molecular lo hace frágil frente a impactos directos. |
| Presenta una alta resistencia al impacto y una notable resistencia a la fatiga mecánica. Cuenta con un módulo elástico que le otorga cierta flexibilidad estructural, permitiéndole soportar torsiones, vibraciones mecánicas y cargas dinámicas sin sufrir fracturas catastróficas. Es el material idóneo para piezas del robot expuestas a colisiones, fuerzas de tracción o movimientos mecánicos constantes. | Ofrece una excelente resistencia a la tracción y una rigidez mecánica superior, lo que significa que no se deforma ni se dobla fácilmente bajo cargas estáticas. Su principal desventaja es la fragilidad extrema; ante esfuerzos mecánicos bruscos o vibraciones continuas, tiende a fisurarse o quebrarse de forma repentina en lugar de flexionarse, limitando su uso en zonas de alta tensión dinámica. |
| Destaca por una estabilidad térmica superior, soportando temperaturas de trabajo de hasta 75°C u 80°C sin perder su rigidez ni sufrir deformaciones estructurales. Esto permite colocarlo directamente junto a disipadores, motores DC o reguladores de voltaje. Además, posee propiedades hidrofóbicas y una alta resistencia química frente a alcoholes, aceites, grasas y a la degradación por exposición a la intemperie. | Posee una baja resistencia térmica, con un punto de ablandamiento (temperatura de transición vítrea) situado entre los 50°C y 55°C. Esto lo vuelve vulnerable a la deformación geométrica si se expone al calor disipado por motores de alta potencia o si el robot opera en entornos cálidos. Asimismo, su resistencia a la degradación por rayos UV y agentes químicos es limitada a largo plazo. |
| Exige condiciones de impresión más estrictas, con temperaturas de boquilla de 230°C a 250°C y cama caliente obligatoria entre 70°C y 90°C. Es propenso a generar hilos finos (stringing) y requiere un control riguroso de la humedad, ya que es altamente higroscópico y absorbe el agua del ambiente rápidamente, lo que degrada la calidad de la pieza si el filamento no se almacena en seco. | Es el material más sencillo de procesar en el taller de robótica, requiriendo temperaturas de boquilla bajas (190°C - 220°C) y una temperatura de cama moderada (50°C - 60°C) o incluso nula. No genera gases nocivos, no sufre de warping (despegue de bordes) y tolera altas velocidades de impresión con ventilación de capa al 100%, facilitando el prototipado rápido de piezas complejas. |
| Se utiliza de forma prioritaria en los componentes críticos sometidos a estrés físico y térmico. Es la elección correcta para parachoques frontales (bumpers) expuestos a colisiones, soportes para motores DC que generan calor por fricción, estructuras internas que sujetan baterías pesadas (soportando inercias bruscas al frenar o girar) y piezas móviles del varillaje del sistema de dirección. | Se aplica en la fabricación de componentes fijos que exigen máxima precisión dimensional y rigidez absoluta, donde las tolerancias geométricas de los encajes deban ser milimétricas. Es ideal para soportes de sensores ópticos o de líneas (que no deben oscilar), carcasas de cámaras de visión artificial, brackets de sujeción estáticos y maquetas de prueba donde el peso y el ajuste de tornillos sean críticos. |
		- Piezas: 
			
| Component & Preview | Design & Geometry | Engineering Purpose |
|---|---|---|
|Battery Case <br><br><img width="400" height="400" alt="BatteryCase" src="https://github.com/user-attachments/assets/a5362844-dd0e-4073-bef8-bb034bae3ad9" /> | Designed as a vertical tower cage structured with four reinforced pillars on each side, integrated directly onto a solid mounting base with corner screw eyelets. The side walls feature large circular cutouts to minimize material weight while allowing maximum passive airflow to prevent thermal stress on the LiPo cells during high discharge rates. The top pillars include slotted retention eyelets for secure strap fastening. | Centralizes the combined mass of the battery cells vertically along the central geometric axis of the chassis. This open-cage design ensures quick access for battery replacement between runs while providing rigid structural containment against lateral inertia forces during high-speed cornering. |
| Camera Case <br><br><img width="400" height="400" alt="CameraCase" src="https://github.com/user-attachments/assets/7adbc42b-15eb-4677-a0a4-8d9b3c98bab3" /> | A compact, rectangular protective enclosure specifically tailored to encapsulate the IMX219 (Arducam) sensor. The bottom section integrates a robust cylindrical pivot hinge featuring external locking teeth (spur gear profile) designed to mesh perfectly with a matching mounting base for mechanical angle locking. | Shields the delicate camera PCB from external debris or direct track impacts. The interlocking geared hinge allows the camera's pitch to be adjusted and mechanically locked at a precise 15-degree downward tilt angle, preventing any unwanted lens shifting caused by high-frequency chassis vibrations during operation. |
| MegaPi Case <br><br><img width="400" height="400" alt="MegaPiBase (1)" src="https://github.com/user-attachments/assets/8db95bf2-a29a-468c-ace8-e21bb1fae9f6" /> | A robust low-profile tray equipped with four integrated, heavy-duty vertical standoffs positioned at the corners to secure the main PCB. The base plate features internal layout guides and structural clearance cuts to avoid components on the underside of the board while keeping the profile as close to the chassis as possible. | Functions as a rigid mechanical cradle for the low-level power electronics. By elevating the PCB via the 3mm integrated standoffs, it prevents electrical short-circuits with the chassis while dampening vibrations. The completely open perimeter guarantees immediate access to the motor screw terminals, power rails, and sensor ports for field maintenance. |
| RaspberryPi Base <br><br><img width="400" height="400" alt="RaspberryPiBase (1)" src="https://github.com/user-attachments/assets/2403b708-2e1d-4360-9504-aae68c0027d1" /> | A flat, mid-level modular platform featuring four integrated corner standoffs to mount the Raspberry Pi 4 safely. The front section of the base integrates a dual-ear hinge mount equipped with internal locking teeth that mate directly with the Camera Case hinge. | Serves as a dual-purpose structural bridge. It provides a stable, elevated mount for the high-level on-board computer, ensuring optimal heat dissipation via natural convection to prevent CPU thermal throttling. Concurrently, its integrated geared mount firmly locks the camera assembly at the front, eliminating the need for extra components and saving valuable chassis space. |
| Ultrasonic Case <br><br><img width="400" height="400" alt="UltrasonicSensorCase" src="https://github.com/user-attachments/assets/f9696c40-13e6-46b5-9712-2d7849a80005" /> | A compact, dual-barrel protective bracket custom-tailored to snugly encapsulate the transmitter and receiver cylinders of the ultrasonic sensor module. It features integrated rear mounting tabs and lower flanges for seamless mechanical coupling to the forward crossbeams of the chassis frame. | Provides a rigid, vibration-isolated housing that keeps the ultrasonic sensor perfectly perpendicular to the track's horizontal plane. This precise alignment eliminates acoustic signal distortion and wave scattering, ensuring highly accurate real-time distance measurements for obstacle detection and emergency braking maps. |

# 2. Componentes

- ### Precios:

	| Cantidad | Productos | Precio | Total |
	|---|---|---|---|
	| 1 | [Raspberry Pi 4 B](https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X) | $127.95 | $127.95 |
	| 1 | [Yfrobot steering chassis](https://yfrobot.com/products/steering-gear-robot) | $118.50 | $118.50 |
	| 2 | [Zeee 3S Lipo Battery 2200mAh 11.1V 50C](https://www.amazon.nl/Zeee-Vrachtwagen-Vliegtuig-Quadcopter-Helikopter/dp/B0C2CHMCC3) | $18.99 | $37.98 |
	| 1 | [Arducam 8MP IMX219 175°](https://www.amazon.com/Arducam-IMX219-Degree-Raspberry-Compatible/dp/B09VSVB4DT/ref=sr_1_7?crid=10W18P0RVDUOR&s=electronics&sr=1-7) | $26.99 | $26.99 |
	| 4 | [Lever wire connectors](https://www.amazon.com/Conductor-Compact-Connectors-Electrical-Terminals/dp/B0D9Y5XFQC/ref=sr_1_2_sspa?sr=8-2-spons) | $9.99 | $39.96 |
	| 1 | [Buck Converter 3A 15W Type-C](https://www.amazon.com/-/es/Convertidor-Impermeable-Adaptador-corriente-compatible/dp/B0D2MTJQK8) | $8.79 | $8.79 |
	| 1 | [MAKEBLOCK MegaPi (from mbot mega)](https://www.robotshop.com/products/makeblock-mbot-mega-robot-car-bluetooth-dongle?qd=09ee589fedd6f0b70db366bd5f5dcf45) | $136.39 | $136.39 |
	| 1 | Click Button | $2.50 | $2.50 |
	| 1 | [LED Traffic Light Module](https://www.amazon.com/Traffic-Light-Module-Board-Arduino/dp/B07R1KJ4DT) | $5.49 | $5.49 |
	| | | | **$505.55** |

- ### Descripción:

	| Foto| Descripción |
	|---|---|
	| Yfrobot kit <div  align="center"> <div  style="width:290 px"> ![halbi](https://funduinoshop.com/media/image/84/6f/82/YFROBOT-chassis-kit-mit-lenkachse-technische-zeichnung_600x600@2x.png) </div> </div>  | El chasis modular YFROBOT 4WD combina tracción en las cuatro ruedas con un sistema de dirección tipo automóvil para ofrecer mayor estabilidad y un control preciso. Diseñado con soportes específicos para controladores como Arduino o Raspberry Pi, simplifica el ensamblaje mecánico y permite añadir sensores o accesorios fácilmente. Al reducir la complejidad del diseño desde cero, resulta una plataforma ideal en educación y competiciones para que los equipos se concentren directamente en la programación, la navegación autónoma y los sistemas de control. |
	| Raspberry PI 4 B <div align="center"> <img width="293" height="172" alt="images" src="https://github.com/user-attachments/assets/5c007a1e-273e-4ce2-89a7-fa99dd9b069b" /> </div> | La Raspberry Pi 4 Modelo B es un potente ordenador de placa única (SBC) del tamaño de una tarjeta de crédito desarrollado por la Fundación Raspberry Pi. Se utiliza ampliamente en robótica, proyectos de IoT y 	sistemas embebidos debido a su versatilidad, rendimiento y precio asequible. |
	| Makeblock MegaPi <div  align="center"> ![nano](https://ardubotics.eu/10754/makeblock-mega-pi-born-to-control.jpg) </div> | Se seleccionó la placa **Makeblock MegaPi** (**ATmega2560**) como microcontrolador central por su capacidad para gestionar múltiples motores y sensores simultáneamente, superando a opciones como Arduino Uno o Nano gracias a sus interfaces plug-and-play. Aunque está diseñada para acoplarse directamente sobre una Raspberry Pi, se optó por conectarla únicamente vía **USB** para la transferencia de datos. Esta alternativa optimiza el espacio del chasis, aprovecha que la MegaPi cuenta con alimentación propia y evita exponer la placa principal a riesgos durante el proceso de soldadura. |
	| Zeee 3S Lipo Battery 2200mAh 11.1V 50C <div  align="center"> <div  style="width:290 px"> ![LX2-BUSB](https://m.media-amazon.com/images/I/71-SIfPk3XL._AC_UF1000,1000_QL80_.jpg) </div> | El robot utiliza una batería LiPo Zeee 3S (2200mAh, 11.1V, 50C) como fuente de energía única, elegida por su alta tasa de descarga y un diseño compacto que optimiza el espacio en el chasis frente a opciones más voluminosas. Esta configuración simplifica el sistema al alimentar tanto la lógica como los motores, aunque exige el uso de reguladores de voltaje externos (como convertidores CC-CC) para proteger componentes sensibles como la Raspberry Pi. A pesar de requerir un manejo cuidadoso con cargadores específicos para evitar riesgos y prolongar su vida útil, ofrece un balance excelente entre potencia, tamaño y rendimiento para aplicaciones robóticas. |
	| Steering servo mg996r <div  align="center"> ![L298N](https://cdn-global-hk.hobbyking.com/media/catalog/product/cache/10/image/9df78eab33525d08d6e5fb8d27136e95/6/2/6221_1_high_7_.jpg) </div> | Incluido en el kit de YFROBOT para controlar el eje de dirección, el MG996R es un servomotor digital de alto torque que opera mediante señales PWM en un rango de 0° a 180°. Su piñonería metálica le otorga una mayor durabilidad y fuerza frente a los servos de plástico, permitiéndole soportar cargas mecánicas exigentes. Con un rango de operación de 4.8V a 6V, ofrece un torque de entre 9.4 y 11 kg·cm y velocidades de hasta 0.15 segundos por cada 60°, utilizando una interfaz estándar de tres pines totalmente compatible con microcontroladores como Arduino y Raspberry Pi. |
	| RS380 motor <div  align="center"> ![motor](https://novatronicec.com/wp-content/uploads/2020/10/Motor-con-caja-reductora-25GA370_2.jpg) </div> | El conjunto de motor RS-380 con caja reductora es un sistema de corriente continua compacto y versátil, ideal para robótica pequeña y automatización ligera. Por sí solo, el RS-380 es un motor con escobillas de tamaño reducido que gira a altas revoluciones (entre 10 000 y más de 20 000 RPM según el voltaje) pero genera muy poco torque. La incorporación de la caja reductora soluciona esta limitación al disminuir la velocidad de giro mediante una serie de engranajes, lo que incrementa significativamente el torque de salida y permite al sistema mover cargas mecánicas más pesadas de manera práctica. |
	| ArduCam IMX219 8MP <div  align="center"> ![Encorder](https://cdn.arducam.com/wp-content/uploads/2022/04/Arducam_IMX219_MIPI_Pi_B0392-8.jpg) </div> | La ArduCam IMX219 de 8MP es un módulo de cámara compacto basado en el sensor Sony IMX219, el mismo estándar de la Raspberry Pi Camera v2, que equilibra resolución y rendimiento para proyectos de visión artificial y robótica. Se conecta mediante la interfaz CSI (Camera Serial Interface), lo que garantiza una transferencia de datos a alta velocidad y con baja latencia hacia computadoras como Raspberry Pi o Jetson Nano. Este diseño la convierte en una solución eficiente y de fácil integración para sistemas embebidos que requieren procesamiento de imagen en tiempo real. |
	| Buck Converter 3A 15W Type-C <div  align="center"> ![camera](https://m.media-amazon.com/images/I/61pOfxNxUnL._AC_UF1000,1000_QL80_.jpg) </div> | El módulo **convertidor buck tipo C de 3A y 15W** es un regulador reductor de CC-CC que transforma voltajes de entrada elevados en una salida baja y estable con una eficiencia del 85 al 95%. En este proyecto, se utilizó para conectar la batería **LiPo Zeee 3S** (de hasta 12.6V) a la **Raspberry Pi 4B**, la cual exige un suministro constante de **5V y hasta 3A**. Debido a que el voltaje directo de la batería dañaría la placa, el convertidor reduce y regula la tensión de manera segura, protegiendo los componentes contra sobrevoltajes, minimizando las pérdidas de energía por calor y garantizando un rendimiento estable del sistema a medida que la batería se descarga. |

- ### Disposición de Sensores y Justificación:

- ### Batería:

- ### Presupuesto de Energía:

- ### Diagrama de Cableado:

<div align="center">

<img width="2960" height="1625" alt="L-N-M@1 25x" src="https://github.com/user-attachments/assets/13e15df3-6f13-4d22-9dfd-a9a075e6561c" />

</div>

# 3.  Software

- ### Utils:

	- Color Tester:

	- ROI Detector:

- ### MegaPiController:

- ### Arduino Controller:

	- Open Challenge:

		- Estrategia: 
		
		- ROIS:

		- Contador de Loops:

		- Diagrama de Flujo:

	- Obstacle Challenge:

		- Estrategia:
		
		- ROIS:

		- Contador de Loops:

		- Diagrama de Flujo:

# 4. Challenges

- ### Problemas de Hardware: 

	- Chasis demasiado pequeño 
	
	- La batería ocupa demasiado espacio

- ### Problemas de Software:

	- a
