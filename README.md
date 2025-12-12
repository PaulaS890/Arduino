<h1 align="center"><strong>Arduino</strong></h1><br>
<p align="center">
  <br><br><img width="300" height="202" alt="Arduino_Logo_Registered svg" src="https://github.com/user-attachments/assets/8376ca18-e5cd-4814-9817-2957fb73f506"/><br><br>
</p>


<details>
<summary><h2>Introducción</h2></summary>
</details>

<details>
<summary><h2>Objetivos</h2></summary>
</details>

<details>
<summary><h2>Actividad 0</h2></summary>

#### 1. ¿Qué es Arduino?<br>
<br>Arduino es un microprocesador que te permite programarlo para hacer las cosas que quieras. <br>
  
#### <br><br>2. ¿Cuáles son sus características más importantes?<br>
<br>Arduino tiene muchísimas características únicas, pero, en específico, considero que las más importantes son las siguientes:<br>
<ul>
<li>Existe de forma física y de forma digital, es decir, hay programas que te permiten simular lo que hace una placa física en forma digital o bien también existen placas físicas. Esto nos viene bien sobre todo a la hora de querer hacer algo para poder probarlo y hacer una esquematización antes de llevarlo a la realidad.<br>

<li>Ambas versiones deben ser programadas, con la ventaja que si es de forma digital, se puede llegar a programar con bloques de programación en cambio de su lenguaje de programación nativo (C o C + +).<br>

<li>Es muy fácil de utilizar, ya que está pensado para principiantes o estudiantes que quieran saber sobre la electrónica o programación, teniendo en cuenta que no tienen experiencia previa.<br>

<li>Tiene una gran variedad de entradas y salidas, por lo que te permite hacer una gran variedad de proyectos. Gracias a esta gran variedad de entradas y salidas también ha logrado tener una gran compatibilidad con componentes, ya sean sensores, luces, pantallas, motores, botones entre otros.<br>

<li>Su conexión mediante la placa física y el código que genere el usuario se puede hacer por USB, por lo que facilita la conexión.<br>

<li>Su fácil accesibilidad, ya que si no dispones de un gran presupuesto, para aprender puedes usar su versión digital que es completamente gratuita, o bien, si lo quieres hacer de forma física un kit de arduino suele estar bastante barato.<br>
</ul>

#### <br><br>3. ¿Cuál es el origen de Arduino?<br>
<br>En 2005, en el instituto Interaction Design Institute Ivrea de Italia se creó lo que hoy en día conocemos como Arduino. Esto se desarrolló debido a que en las escuelas de diseño se necesitaba una forma fácil y barata de creación de prototipos electrónicos interactivos.<br>

#### <br><br>4. ¿Qué modelos de Arduino hay? Haz una tabla donde especifiques para cada modelo: microcontrolador, voltaje, pines digitales, entradas analógicas, memoria, reloj<br>

Existe una gran variedad de modelos de Arduino, algunos se centran más en unas cosas y otros en otra, de esta forma, tienen una gran variedad de usos. El principal, más conocido y usado es el Arduino Uno. A continuación podemos observar la tabla que hemos hecho con la comparación de todos los modelos Arduino que hemos encontrado:<br>

| **Modelo**              | Arduino UNO | Arduino Mega | Arduino Leonardo | Arduino UNO R3 | Arduino GIGA R1 WiFi                                          | Arduino MKR WAN 1310                                   | Arduino Nano ESP32 con Headers | Arduino Nano RP2040  | Arduino Opta Lite             | Arduino Opta RS485       | Arduino Opta WiFi | Arduino UNO R4 Mínima | Arduino UNO R4 WiFi | Arduino Mega 2560 R3 | Arduino MKR WiFi 1010 | Arduino Portenta H7 | Arduino Due |
|-------------------------|-------------|--------------|------------------|----------------|---------------------------------------------------------------|--------------------------------------------------------|--------------------------------|----------------------|-------------------------------|--------------------------|-------------------|-----------------------|---------------------|----------------------|-----------------------|---------------------|-------------|
| **Microcontrolador**    | AT mega 328 | AT mega 2560 | AT mega 32u4     | AT mega 328    | STM32H747XI MCU dual Cortex-M7®+M4 de 32 bits de bajo consumo | MCU ARM de baja potencia SAMD21 Cortex®-M0+ de 32 bits | u-blox® NORA-W106 (ESP32-S3)   | Raspberry Pi RP 2040 | STM32H747XI Dual ARM® Cortex® | STM32H747XI Cortex® ARM® | STM32H747XI       | Renesas RA4M1         | Renesas RA4M1       | AT mega 2560         | SAMD21 Cortex         | STM32H747           | AT91SAM3X8E |
| **Voltaje**             | 7-12 V      | 7-12 V       | 7-12 V           | 7-12 V         | 6-24 V                                                        | 3,3 V                                                  | 6-12 V                         | 5-21 V               | 12-24 V                       | 12-24 V                  | 12-24 V           | 6-24 V                | 6-24 V              | 7-12 V               | 5 V                   | 3.3-5 V             | 7-12 V      |
| **Pines digitales**     | 14          | 54           | 20               | 14             | 76                                                            | 8                                                      | 14                             | 20                   | 16                            | 8                        | 8                 | 14                    | 14                  | 54                   | 8                     | 80                  | 54          |
| **Entradas analógicas** | 6           | 16           | 20               | 6              | 12                                                            | 7                                                      | 8                              | 8                    | 8                             | Configurable             | Configurable      | 6                     | 6                   | 16                   | 7                     | 16                  | 12          |
| **Memoria**             | 32 k        | 256 k        | 32 k             | 32 k           | 2MB                                                           | 256 k                                                  | 384 k                          | 16 MB                | 1 MB                          | 1 MB                     | 1 MB              | 256 k                 | 256 k               | 256 k                | 256 k                 | 8 MB                | 32 k        |
| **Reloj**               | 16 MHz      | 16 MHz       | 16 MHz           | 16 MHz         | 480 MHz                                                       | 48 MHz                                                 | 240 MHz                        | 133 MHz              | 480 MHz                       | 480 MHz                  | 480 MHz           | 48 MHz                | 48 MHz              | 16 MHz               | 48 MHz                | 240 MHz             | 84 MHz      |

#### <br><br>5. ¿Para qué sirve Arduino?<br>
<br>Principalmente Arduino sirve para poder crear proyectos electrónicos y de automatización de forma sencilla sin tener experiencia previa de forma barata. <br>

#### <br><br>6. ¿Qué lenguaje utiliza?<br>
<br>Arduino utiliza el lenguaje de programación C y C + +.<br>

#### <br><br>7. ¿Qué es Arduino IDE?<br>
<br>Arduino IDE es el programa oficial que se usa para la programación y compilación del código de las placas Arduino. Es decir, en esta aplicación se escribe o sube el código de lo que queremos hacer con nuestra placa en C o C + +. Una vez tenemos el código, conectamos la placa, lo compilamos para corroborar si es correcto y finalmente se ejecuta para que la placa haga lo que hemos programado.<br>

</details>

<details>
<summary><h2>Actividad 1</h2></summary>
<h3>Objetivo de la actividad</h3>
El objetivo de esta práctica es el de aprender cómo funcionan los LED y hacer que uno parpadee.

<h3>Materiales necesarios</h3>
• Placa de arduino
• Resistencia
• LED
• Cables

<h3>Código utilizado</h3>
#define LED1 2 //declaración componente
void setup() { //declaraciones fijas, no le hace falta bucle
pinMode (LED1, OUTPUT); //declaramos que es una salida
} 
void loop() { //el bucle que se repite
digitalWrite(LED1, HIGH);  //encendemos led
delay(1000);  //esperamos 1seg
digitalWrite(LED1, LOW); //apagamos led
delay(1000); //esperamos 1 seg
	}


<h3>Esquema</h3>
<img width="686" height="294" alt="image" src="https://github.com/user-attachments/assets/283c8064-238d-4d61-b529-015e60f2f5f9" />

<h3>Foto y vídeo</h3>
<img width="550" height="734" alt="image" src="https://github.com/user-attachments/assets/28d57b46-d3b4-48bb-8bb4-3dcd32c93cd8" />


https://github.com/user-attachments/assets/37f2a64e-26c6-4785-b794-0118e580dc65



<H3>Preguntas</H3>
• ¿Qué son el void setup() and void loop() ? 
Void setup se encarga de recopilar la configuración del programa, mientras que void loop es el código que se ejecutará en bucle.
• ¿Qué quiere decir la línea: #define LED_BUITIN 2 ? 
Se define que el led está en el pin digital 2 bajo el nombre LED_BUITIN.
• ¿Qué quiere decir la línea delay(1000); ? 
Esa línea son los milisegundos de espera que hay para ejecutar la siguiente orden.
• Buscar información de cada función del script en: https://www.arduino.cc/reference/en/ ? 
pinMode OUTPUT: Establece el pin seleccionado como salida.
Delay: rato de espera para ejecutar la siguiente orden.
DigitalWrite HIGH/LOW: Aumenta o disminuye el voltaje para que el led se encienda o se apague.
• Selecciona el extremo del jumper que está en el pin 2 y conéctalo donde dice 5V. ¿Qué ocurre con el led: parpadea?
El LED sí que parpadea, ya que es lo que le indicamos en el código, aparte, las conexiones están 
bien conectadas, es decir, los polos positivos donde deben ir y los polos negativos donde deben ir.
• Conecta cada cable o jumper al polo (-) o GND y al polo (+) de la pila. ¿Qué ocurre con el led: parpadea?
No, en este caso el LED no parpadeará, se quedará o bien encendido fijo o bien apagado fijo, ya
que dependiendo de cómo se conecte (es decir, si le cambiamos los polos) el LED no hará la
función que le hemos dicho que haga, si no que se quedará o bien encendido o bien apagado.

</details>

<details>
<summary><h3>Actividad 2</h3></summary>

<h3>Objetivo de la actividad</h3>
El objetivo de esta práctica es la de aprender a comprender cómo funciona el LED, saber como conectarlos correctamente y hacerlos funcionar a su respectivo tiempo. En este ejercicio hemos hecho un semáforo, haciendo que cada LED parpadee sin sobreponerse los unos a los otros y hemos hecho que funcione un único LED individual.
Para hacer el semáforo, es tan sencillo como añadir dos LEDs más con sus respectivas resistencias y cables. En cuanto al código, hemos añadido los otros dos LEDs al script y ha funcionado perfectamente.

<h3>Materiales necesarios</h3>
• Placa de arduino
• Resistencias
• LEDs
• Cables

<h3>Código utilizado</h3>
#define LED1 2 //declaración led amarillo
#define LED2 15 //declaración led rojo 
#define LED3 0 //declaración led verde 


void setup() { 
// Definimos los pines como salida.
pinMode (LED1, OUTPUT); 
pinMode (LED2, OUTPUT); 
pinMode (LED3, OUTPUT); 
} 
void loop() { 
digitalWrite(LED1, HIGH);   // Aumentamos la carga para que se encienda el LED
delay(1000); 			          // Espera de 1 segundo
digitalWrite(LED1, LOW);    // Disminuimos la carga para que se apague el LED
delay(1000); 
digitalWrite(LED2, HIGH); 
delay(1000); 
digitalWrite(LED2, LOW); 
delay(1000); 
digitalWrite(LED3, HIGH); 
delay(1000); 
digitalWrite(LED3, LOW); 
delay(1000); 
}

<h3>Esquema</h3>
<img width="670" height="355" alt="image" src="https://github.com/user-attachments/assets/05e934ce-ec36-42ea-8d02-f2e964530e38" />

<h3>Foto y vídeo</h3>
<img width="1307" height="735" alt="20251212_124513" src="https://github.com/user-attachments/assets/5ff46e66-977b-48e9-adc1-78c36b6ba8f7" />

https://github.com/user-attachments/assets/ef3f6fd2-4b6c-4a06-a335-bbe9cdff9fa1


</details>

<details>
<summary><h2>Conclusiones</h2></summary>
.
</details>

<details>
<summary><h2>Bibliografía</h2></summary>
</details>

