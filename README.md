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
<summary><h2>Actividad 2</h2></summary>

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
<summary><h2>Actividad 3</h2></summary>
<h3>Objetivo de la actividad</h3>
Para este ejercicio debemos montar un circuito que encienda una bombilla mientras mantengamos un botón pulsado. Cuando no lo esté, la bombilla debe permanecer apagada

<h3>Materiales necesarios</h3>

• Placa de arduino

• Resistencias

• LEDs

• Cables

• Botón


<h3>Código utilizado</h3>

```
void setup() {

  pinMode(2, OUTPUT);
  
  pinMode(13, INPUT);
  
}


void loop() {

  if(digitalRead(13) == LOW) {
  
digitalWrite(2, HIGH);
	
  } else {
  
digitalWrite(2, LOW);
	
  }
  
}
```
<h3>Esquema</h3>
<img width="696" height="631" alt="image" src="https://github.com/user-attachments/assets/b26c3592-785b-4634-92b3-5ed23338a09c" />


<h3>Foto y vídeo</h3>
<img width="1270" height="694" alt="image" src="https://github.com/user-attachments/assets/b80c11b1-f10d-4f30-9a56-3a1ddaaf1145" />


https://github.com/user-attachments/assets/7d99913c-f2fd-4895-8cb4-7e18441ce309

<h3>Preguntas</h3>

```
int i = 0;

void setup() {
	for(i=11; i<14; i++)
	pinMode(i, OUTPUT);
}

void loop() {
	for(i=11; i<14; i++){
		digitalWrite(i, HIGH);
		delay(1000);
		digitalWrite(i, LOW);
		delay(1000);
	}
}
```
<h4>¿Para qué sirve el FOR?</h4>
FOR sirve para crear bucles que se repiten hasta que se cumple cierta condición.

<h4>¿Cuáles son los pines de los leds?</h4>
Los pines de los leds son el 11, el 12 y el 13.

<h4>¿Qué hace el código?</h4>
El código repite un bucle de parpadeo hasta que se alcance el pin 13. Al llegar el valor a 14 se detiene y rompe el ciclo.


</details>
<details>
<summary><h2>Actividad 4</h2></summary>

<h3>Objetivo de la actividad</h3>
Para este ejercicio utilizaremos el mismo circuito que en la actividad anterior, pero deberemos cambiar el código para que el led se mantenga encendido al pulsar el botón y se apague únicamente al vovler a presionarlo.

<h3>Materiales necesarios</h3>

• Placa de arduino

• Resistencias

• LEDs

• Cables

• Botón


<h3>Código utilizado</h3>

```
bool ledOn = false;



void setup() {

  pinMode(2, OUTPUT);
  
  pinMode(13, INPUT_PULLUP);
  
}


void loop() {

  if (digitalRead(13) == LOW) {
  
delay(50); // Anti-rebotes
	
edOn = !ledOn; // Invertir estado
	
digitalWrite(2, ledOn ? HIGH : LOW);
	
while(digitalRead(13) == LOW); // Esperar a soltar
	
delay(50);
	
  }
  
}
```

<h3>Esquema</h3>
<img width="696" height="631" alt="image" src="https://github.com/user-attachments/assets/b26c3592-785b-4634-92b3-5ed23338a09c" />


<h3>Foto y vídeo</h3>
<img width="1270" height="694" alt="image" src="https://github.com/user-attachments/assets/b80c11b1-f10d-4f30-9a56-3a1ddaaf1145" />


https://github.com/user-attachments/assets/89cbb973-3c11-4399-8b44-2ebc3a76da11

<h3>Preguntas</h3>

<h4>¿Qué pasa si se quita una resistencia del circuito?</h4>
Si quitamos una resistencia del circuito, este se sobrecalentará y la bombilla se quemará.

</details>


<details>
<summary><h2>Actividad 5</h2></summary>

<h3>Objetivo de la actividad</h3>
En esta práctica deberemos investigar sobre el funcionamiento de los LEDs RGB y comprender su diferencia con un LED normal. En arduino tendremos que controlar los colores que queremos que muestre el LED RGB, luego, haremos que vaya cambiando gradualmente entre colores.

<h3>Preguntas</h3>

<b>Analizar y entender la diferencia entre un LED normal a un LED RGB. Para esto pueden crear una pequeña tabla de dos Columnas, donde la cabecera de cada columna serán los dos tipos de LED analizados en clase y que tendrá dos filas asociadas a los elementos comunes y las diferencias entre ellos.</b>

Un LED normal emite una única luz, mientras que uno RGB puede emitir los tres colores luz primarios (rojo, verde y azul) y mezclarlos para crear luces de más colores.

| LED NORMAL                                                  | LED RGB                                                                                                                    |
|-------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| Emite un único color                                        | Infinidad de colores mezclando las intensidades del rojo, verde y azul                                                     |
| Dos pines ánodo y cátodo                                    | Cuatro pines, uno común (ánodo y cátodo) y los otros tres para los colores                                                 |
| Se enciende o apaga desde un pin digital y una resistencia. | Se controla con pines PWM (pulse width modulation), que simulan voltajes variables ara ajustar la intensidad de cada color |


<b>Que ocurriría en caso de invertir los colores del LED RGB por ejemplo que el pin 4 (Rojo) vaya a la pata del LED G(Verde) y el pin 0 a la pata del LED R(Roja). Porque cree que pase esto argumente su respuesta.</b>

El color final deseado cambiaría ya que se modificaría la intensidad con la que brilla cada color.


<b>Que sucede si comentamos dentro de la función void loop{}, la llamada a la función setColor(red, green, blue). Argumente lo que observa, después de volver a compilar el código.</b>

Si ponemos la función setColor(red, green, blue) el LED se apagará ya que los pines no estarán definidos.



<b>¿Qué función tendría que dejar de utilizar para evitar el cambio aleatorio de los colores dentro del ciclo infinito? Explique que hace dicha función.</b>

Para que no haya un cambio aleatorio de colores dentro del ciclo, habría que eliminar la función random(), la cual genera valores diferentes en cada ejecución del loop.


<b>Utiliza al menos dos combinaciones de colores (RGB) no aleatorias, que más le guste y donde se observen diferencias y argumente porque cree usted que se observa la tendencia hacia un color determinado. </b>

Los LEDs tienen una tendencia hacia el azul, esto es debido a que los diodos de distintos colores suelen tener una eficiencia distinta, y a que el ojo humano es más sensible a este color.


<b>¿Qué sucedería si utilizamos la función aleatoria, pero regulamos los valores de la función random y pasamos los rangos que queremos? ¿Sería una forma de regular la coloración del LED RGB? Explique su respuesta brevemente.</b>

Limitar los valores RGB dentro de la función random() nos serviría para regular qué colores queremos que muestre el LED.


<b>Explique que es el tipo de dato long y su diferencia con el int y porque se utiliza en el ejercicio</b>

La diferencia principal entre INT y LONG es la cantidad de números enteros que pueden almacenar.



| INT                                      | LONG                                          |
|------------------------------------------|-----------------------------------------------|
| 32 bits                                  | Hasta 64 bits                                 |
| Utilizado para números estándar          | Utilizado en cálculos científicos o contables |
| Rango de -2.147.483.648 a -2.147.483.647 | Rango hasta 9 x 10^18                         |


<b>Explique el funcionamiento de la función wheel de manera general.</b>

La función wheel() genera un color basado en la posición 0 - 255. Se utiliza para crear el efecto arcoíris en un led RGB.


<b>Busque en las referencias para que se utiliza la función ledcWrite() además indique cual es la salida de esta función y qué significado tiene en el código.</b>

ledcWrite() permite controlar el brillo de cada color del LED, permitiéndonos mostrar cualquier color que nosotros queramos (dentro de las limitaciones de los colores luz).

Dentro del código, lo utilizamos para generar una señal específica a los pines que se le indican para mostrar los colores que queramos.


<h3>Foto y vídeo</h3>

<H4>Actividad 1</H4>

<img width="599" height="361" alt="image" src="https://github.com/user-attachments/assets/212a6290-5777-45cf-8a8c-c431514502bd" />

https://github.com/user-attachments/assets/76f5c103-d68f-4810-a0b6-65fbe2417a49

<H4>Actividad 2</H4>

<img width="761" height="423" alt="image" src="https://github.com/user-attachments/assets/752e56a0-149c-40f6-bba8-65ea7ee82af0" />



https://github.com/user-attachments/assets/b9b54b54-c6a0-4439-917e-236055050acc



</details>


<details>
<summary><h2>Conclusiones</h2></summary>
.
</details>

<details>
<summary><h2>Bibliografía</h2></summary>
</details>

