## 1- Mobilidad y diseño

- #### Opciones de diseño:

	| Foto | Descripción | Nombre |
	|---|---|---|
	| a | a | Cyber Cooper |
	| a | a | Cooper |
	| a | a | Halbi |
	| a | a | The Fridge |

 - #### Halbi The Green:

	* Dirección:

		- Ackerman: 

		- Uso:

	* Transmisión:

		- Velocidad:

		- Peso:

		- Torque:

	* 3D Printed Parts:

		- Impresora:

		- PETG vs PLA:

		- Piezas: 
			
			| Component & Preview | Design & Geometry | Engineering Purpose |
			|---|---|---|
			|Battery Case <br><br><img width="400" height="400" alt="BatteryCase" src="https://github.com/user-attachments/assets/a5362844-dd0e-4073-bef8-bb034bae3ad9" /> | Designed as a vertical tower cage structured with four reinforced pillars on each side, integrated directly onto a solid mounting base with corner screw eyelets. The side walls feature large circular cutouts to minimize material weight while allowing maximum passive airflow to prevent thermal stress on the LiPo cells during high discharge rates. The top pillars include slotted retention eyelets for secure strap fastening. | Centralizes the combined mass of the battery cells vertically along the central geometric axis of the chassis. This open-cage design ensures quick access for battery replacement between runs while providing rigid structural containment against lateral inertia forces during high-speed cornering. |
			| Camera Case <br><br><img width="400" height="400" alt="CameraCase" src="https://github.com/user-attachments/assets/7adbc42b-15eb-4677-a0a4-8d9b3c98bab3" /> | A compact, rectangular protective enclosure specifically tailored to encapsulate the IMX219 (Arducam) sensor. The bottom section integrates a robust cylindrical pivot hinge featuring external locking teeth (spur gear profile) designed to mesh perfectly with a matching mounting base for mechanical angle locking. | Shields the delicate camera PCB from external debris or direct track impacts. The interlocking geared hinge allows the camera's pitch to be adjusted and mechanically locked at a precise 15-degree downward tilt angle, preventing any unwanted lens shifting caused by high-frequency chassis vibrations during operation. |
			| MegaPi Case <br><br><img width="400" height="400" alt="MegaPiBase (1)" src="https://github.com/user-attachments/assets/8db95bf2-a29a-468c-ace8-e21bb1fae9f6" /> | A robust low-profile tray equipped with four integrated, heavy-duty vertical standoffs positioned at the corners to secure the main PCB. The base plate features internal layout guides and structural clearance cuts to avoid components on the underside of the board while keeping the profile as close to the chassis as possible. | Functions as a rigid mechanical cradle for the low-level power electronics. By elevating the PCB via the 3mm integrated standoffs, it prevents electrical short-circuits with the chassis while dampening vibrations. The completely open perimeter guarantees immediate access to the motor screw terminals, power rails, and sensor ports for field maintenance. |
			| RaspberryPi Base <br><br><img width="400" height="400" alt="RaspberryPiBase (1)" src="https://github.com/user-attachments/assets/2403b708-2e1d-4360-9504-aae68c0027d1" /> | A flat, mid-level modular platform featuring four integrated corner standoffs to mount the Raspberry Pi 4 safely. The front section of the base integrates a dual-ear hinge mount equipped with internal locking teeth that mate directly with the Camera Case hinge. | Serves as a dual-purpose structural bridge. It provides a stable, elevated mount for the high-level on-board computer, ensuring optimal heat dissipation via natural convection to prevent CPU thermal throttling. Concurrently, its integrated geared mount firmly locks the camera assembly at the front, eliminating the need for extra components and saving valuable chassis space. |
			| Ultrasonic Case <br><br><img width="400" height="400" alt="UltrasonicSensorCase" src="https://github.com/user-attachments/assets/f9696c40-13e6-46b5-9712-2d7849a80005" /> | A compact, dual-barrel protective bracket custom-tailored to snugly encapsulate the transmitter and receiver cylinders of the ultrasonic sensor module. It features integrated rear mounting tabs and lower flanges for seamless mechanical coupling to the forward crossbeams of the chassis frame. | Provides a rigid, vibration-isolated housing that keeps the ultrasonic sensor perfectly perpendicular to the track's horizontal plane. This precise alignment eliminates acoustic signal distortion and wave scattering, ensuring highly accurate real-time distance measurements for obstacle detection and emergency braking maps. |

## 2. Componentes

- #### Precios:

	| Cantidad | Productos | Precio | Total |
	|---|---|---|---|
	| 1 | [Raspberry Pi 4 B](https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X) | $127.95 | $127.95 |
	| 1 | [Yfrobot steering chassis](https://yfrobot.com/products/steering-gear-robot) | $118.50 | $118.50 |
	| 2 | [Zeee 3S Lipo Battery 2200mAh 11.1V 50C](https://www.amazon.nl/Zeee-Vrachtwagen-Vliegtuig-Quadcopter-Helikopter/dp/B0C2CHMCC3) | $18.99 | $37.98 |
	| 1 | [Arducam 8MP IMX219 175°](https://www.amazon.com/Arducam-IMX219-Degree-Raspberry-Compatible/dp/B09VSVB4DT/ref=sr_1_7?crid=10W18P0RVDUOR&s=electronics&sr=1-7) | $26.99 | $26.99 |
	| 4 | [Lever wire connectors](https://www.amazon.com/Conductor-Compact-Connectors-Electrical-Terminals/dp/B0D9Y5XFQC/ref=sr_1_2_sspa?sr=8-2-spons) | $9.99 | $39.96 |
	| 1 | [Buck Converter 3A 15W Type-C](https://www.amazon.com/-/es/Convertidor-Impermeable-Adaptador-corriente-compatible/dp/B0D2MTJQK8) | $8.79 | $8.79 |
	| 1 | [MAKEBLOCK MegaPi (from mbot mega)](https://www.robotshop.com/products/makeblock-mbot-mega-robot-car-bluetooth-dongle?qd=09ee589fedd6f0b70db366bd5f5dcf45) | $136.39 | $136.39 |
	| 1 | a | $2.50 | $2.50 |
	| 1 | [LED Traffic Light Module](https://www.amazon.com/Traffic-Light-Module-Board-Arduino/dp/B07R1KJ4DT) | $5.49 | $5.49 |
	| | | | **$505.55** |

- #### Descripción:

	| Foto| Descripción |
	|---|---|
	| Yfrobot kit <div  align="center"> <div  style="width:290 px"> ![halbi](https://funduinoshop.com/media/image/84/6f/82/YFROBOT-chassis-kit-mit-lenkachse-technische-zeichnung_600x600@2x.png) </div> </div>  | El chasis modular YFROBOT 4WD combina tracción en las cuatro ruedas con un sistema de dirección tipo automóvil para ofrecer mayor estabilidad y un control preciso. Diseñado con soportes específicos para controladores como Arduino o Raspberry Pi, simplifica el ensamblaje mecánico y permite añadir sensores o accesorios fácilmente. Al reducir la complejidad del diseño desde cero, resulta una plataforma ideal en educación y competiciones para que los equipos se concentren directamente en la programación, la navegación autónoma y los sistemas de control. |
	| Raspberry PI 4 B <div align="center"> <img width="293" height="172" alt="images" src="https://github.com/user-attachments/assets/5c007a1e-273e-4ce2-89a7-fa99dd9b069b" /> </div> | La Raspberry Pi 4 Modelo B es un potente ordenador de placa única (SBC) del tamaño de una tarjeta de crédito desarrollado por la Fundación Raspberry Pi. Se utiliza ampliamente en robótica, proyectos de IoT y 	sistemas embebidos debido a su versatilidad, rendimiento y precio asequible. |
	| a | a |
	| a | a |
	| a | a |
	| a | a |

- #### Disposición de Sensores y Justificación:

- #### Batería:

- #### Presupuesto de Energía:

- #### Diagrama de Cableado:

<div align="center">

<img width="2960" height="1625" alt="L-N-M@1 25x" src="https://github.com/user-attachments/assets/13e15df3-6f13-4d22-9dfd-a9a075e6561c" />

</div>

## 3.  Software

- #### Utils:

	- Color Tester:

	- ROI Detector:

- #### MegaPiController:

- #### Arduino Controller:

	* Open Challenge:

		- Estrategia: 
		
		- ROIS:

		- Contador de Loops:

		- Diagrama de Flujo:

	- Obstacle Challenge:

		- Estrategia:
		
		- ROIS:

		- Contador de Loops:

		- Diagrama de Flujo:

## 4. Challenges

- #### Problemas de Hardware: 

	- Chasis demasiado pequeño 
	
	- La batería ocupa demasiado espacio

- #### Problemas de Software:

	- L
