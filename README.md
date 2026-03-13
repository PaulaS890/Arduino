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

<H3>Código Utilizado</H3>
<h4>Actividad 3</h4>

```
const byte ledPins[] = {4, 0, 2};   // Pines RGB
const byte chns[] = {0, 1, 2};      // Canales PWM

void setup() {
  for (int i = 0; i < 3; i++) {
    // Asocia pin + canal + frecuencia + resolución
    ledcAttach(ledPins[i], 1000, 8);
  }
}

void loop() {
  for (int i = 0; i < 256; i++) {
    setColor(wheel(i));
    delay(30);
  }
}

void setColor(long rgb) {
  ledcWrite(ledPins[0], 255 - ((rgb >> 16) & 0xFF)); // Rojo
  ledcWrite(ledPins[1], 255 - ((rgb >> 8) & 0xFF));  // Verde
  ledcWrite(ledPins[2], 255 - (rgb & 0xFF));         // Azul
}

long wheel(int pos) {
  pos = pos % 256;

  if (pos < 85) {
    return ((255 - pos * 3) << 16) | ((pos * 3) << 8);
  } 
  else if (pos < 170) {
    pos -= 85;
    return ((255 - pos * 3) << 8) | (pos * 3);
  } 
  else {
    pos -= 170;
    return ((pos * 3) << 16) | (255 - pos * 3);
  }
}
```

<h3>Foto y vídeo</h3>

<H4>Actividad 1</H4>

<img width="599" height="361" alt="image" src="https://github.com/user-attachments/assets/212a6290-5777-45cf-8a8c-c431514502bd" />

https://github.com/user-attachments/assets/76f5c103-d68f-4810-a0b6-65fbe2417a49

<H4>Actividad 2</H4>

<img width="761" height="423" alt="image" src="https://github.com/user-attachments/assets/752e56a0-149c-40f6-bba8-65ea7ee82af0" />


https://github.com/user-attachments/assets/b9b54b54-c6a0-4439-917e-236055050acc

<h4>Actividad 3</h4>

https://github.com/user-attachments/assets/41bdf0b5-4507-4c52-aa48-990a226ebce1

</details>

<details>
<summary><h2>Actividad 6</h2></summary>

### Resumen de la actividad

Para este ejercicio deberemos utilizar una barra LED para simular el efecto del coche fantástico, haciendo que las luces se vayan iluminando de izquierda a derecha y reboten en los bordes, formando un ciclo infinito.

### Preguntas

<b>1. Diseñar el circuito partiendo de la base que a cada pin de la barra LED irá conectado una
resistencia de 220 ohm y del otro extremo a masa, los pines donde conectar a placa los
escogeis vosotros</b>

CÓDIGO:
```
byte ledPins[] = {23, 22, 21, 19, 18, 5, 4, 0, 2, 5};
int cuentaLED;

void setup() {
  cuentaLED = sizeof(ledPins) / sizeof(ledPins[0]);

  for (int i = 0; i < cuentaLED; i++) {
    pinMode(ledPins[i], OUTPUT);
  }
}

void loop() {
  for (int i = 0; i < cuentaLED; i++) {
    digitalWrite(ledPins[i], LOW);
    delay(50);
    if (i > 0) {
      digitalWrite(ledPins[i-1], HIGH);
    }
  }

  digitalWrite(ledPins[cuentaLED-1], HIGH);

  for (int i = cuentaLED - 2; i >= 0; i--) {
    digitalWrite(ledPins[i], HIGH);
    delay(50);
    if (i < cuentaLED - 2) {
      digitalWrite(ledPins[i+1], HIGH);
    } 
  }
  digitalWrite(ledPins[0], HIGH);
}

```

#### Foto y vídeo

<img width="702" height="425" alt="image" src="https://github.com/user-attachments/assets/89035ccb-8c52-4d40-8ae4-1397f7608557" />



https://github.com/user-attachments/assets/5d2516e6-e31e-45de-b8f1-3da31aada5db




<b>Crear el diseño del circuito en cualquier herramienta de las que hemos trabajado en clase.</b>

<img width="726" height="559" alt="image" src="https://github.com/user-attachments/assets/f8de9a4c-e342-4905-96c3-b064c44846aa" />


<b>Si has probado el código verás que algo no funciona, localiza los errores, solvéntalos y
explícanos por qué no funcionaba.</b>

ERROR 1: Los pines no están definidos, por lo que no se encenderá ningún led.

ERROR 2: Por ende, si el array anterior está vacío, ledCounts = sizeof(ledPins); devolverá 0 porque no hay ningún parámetro.

ERROR 3: Los bucles i+ e i- están mal escritos, deben escribirse como i++ e i--

ERROR 4: Dentro de delay() debe de haber algún valor, no puede quedarse vacío, sino, no hace nada.

ERROR 5: Los leds deben de estar escritos como OUTPUT, no INPUT.


<b>Cómo tengo que hacer si quiero que el LED empiece en otra posición, por ejemplo, en el
medio y vaya de izquierda a derecha. (Sube video también de esta parte y el código
modificado)</b>

Podemos hacerlo de forma sencilla añadiendo la línea de código
```
  int center = cuentaLED / 2;
```

Esto divide el número de pines por la mitad (nos da el valor central) y hace que comience por ahí.
También tenemos que modificar algunas variables de los bucles for del final.

#### CÓDIGO MODIFICADO

```
byte ledPins[] = {23, 22, 21, 19, 18, 5, 4, 0, 2, 5};
int cuentaLED;

void setup() {
  cuentaLED = sizeof(ledPins) / sizeof(ledPins[0]);

  for (int i = 0; i < cuentaLED; i++) {
    pinMode(ledPins[i], OUTPUT);
  }
}

void loop() {

  int center = cuentaLED / 2;

  for (int i = 0; i < cuentaLED; i++) {
    digitalWrite(ledPins[i], LOW);
    delay(50);
    if (i > center) {
      digitalWrite(ledPins[i-1], HIGH);
    }
  }

  digitalWrite(ledPins[cuentaLED-1], HIGH);

  for (int i = center - 1; i >= 0; i--) {
    digitalWrite(ledPins[i], HIGH);
    delay(50);
    if (i < center - 1) {
      digitalWrite(ledPins[i+1], HIGH);
    } 
  }
  digitalWrite(ledPins[0], HIGH);
}

```
#### Vídeo



https://github.com/user-attachments/assets/b43d7fbc-3dd6-4020-89ec-89f59072c3dc



<b>Ahora queremos que cuando la luz llegue al final rebote en bucle.
a. Vídeo en funcionamiento.



https://github.com/user-attachments/assets/86e73138-80ab-4135-babe-05679eae7874


b. Código</b>
```
byte ledPins[] = {23, 22, 21, 19, 18, 5, 4, 0, 2, 5};
int cuentaLED;
int posicion = 0;
int direccion = 1; // 1 = derecha, -1 = izquierda
int velocidad = 100;

void setup() {
  cuentaLED = sizeof(ledPins) / sizeof(ledPins[0]);

  for (int i = 0; i < cuentaLED; i++) {
    pinMode(ledPins[i], OUTPUT);
  }
}

void loop() {

// se apagan todos los leds
for (int i = 0; i < cuentaLED; i++) {
  digitalWrite(ledPins[i], HIGH);
}

//encender led en posicion actual
  digitalWrite(ledPins[posicion], LOW);
  delay(velocidad);

  //mover la posición
  posicion += direccion;

  //cambia de dirección cuando llega al final
  if (posicion >= cuentaLED - 1) {
    direccion = -1; //izquierda
  } else if (posicion <= 0) {
    direccion = 1; //derecha
  }
}
```

</details>

<details>
<summary><h2>Actividad 7</h2></summary>
	
### Resumen de la actividad

Para este ejercicio deberemos conectar una placa LED y un higrotermógrafo a la placa Arduino y con ello hacer que se muestren datos de temperatura y humedad del ambiente en la pantalla.

### Preguntas
<b>1. Conecta la pantalla tal y como se muestra en el circuito anterior.</b>

Conectado.

<b>2. En el Arduino IDE incluye la librería que puedes encontrar en Github, busca el paquete de
LiquidCrystal_I2C.zip y añádelo al IDE para que funcione.</b>
<b>3. Pon el “Upload speed” de “Herramientas>Upload speed” a 115200.</b>
<b>4. NO utilices el puerto 12 de la GPIO.</b>
<b>5. Usa el código que encuentres en el capítulo.</b>
#### Foto y vídeo

<img width="1261" height="685" alt="image" src="https://github.com/user-attachments/assets/6ee2c91d-da06-4b59-ab58-13c08c7a9f42" />


https://github.com/user-attachments/assets/f13eaf30-74e4-460b-aea2-2e74cd6a32d1



#### CÓDIGO MODIFICADO
```
#include <Wire.h> 
#include <LiquidCrystal_I2C.h>

//Crear el objeto lcd  dirección  0x3F y 16 columnas x 2 filas
LiquidCrystal_I2C lcd(0x3F,16,2);  //

void setup() {
  // Inicializar el LCD
  lcd.init();
  
  Serial.begin(9600);
  lcd.backlight();

  // Escribimos el Mensaje en el LCD.
  lcd.print("Hola!!! :3");
}

void loop() {
   // Ubicamos el cursor en la primera posición(columna:0) de la segunda línea(fila:1)
  lcd.setCursor(0, 1);
   // Escribimos el número de segundos trascurridos
  lcd.print(millis()/1000);
  lcd.print(" Segundos");
  delay(100);
}

```

### Segunda parte

#### Preguntas

<b>1. Primero prueba que el código funciona por monitor serial. Prueba a soplar sobre el sensor para modificar los valores de humedad.</b>
Cuando se sopla, aumenta la humedad, se puede ver un claro ejemplo en el vídeo adjuntado más abajo.

<b>2. Ahora prueba a mostrar los valores en la pantalla LCD</b>
En el vídeo mostramos el cambio que hay cuando soplamos en el sensor.

<b>3. Busca que hace esta linea “DHTesp dht; “ al principio del código. ¿Que es un objeto en programación y que es lo que hace?</b>
Interactua con un sensor de humedad y temperatura DHT, utilizando la librería "DHT sensor library for ESPx".

<b>4. Prueba a codificar los valores para que muestre en la primera fila la temperatura en grados Kelvin y en la segunda fila en grados Farenheit.</b>

<img width="1350" height="698" alt="image" src="https://github.com/user-attachments/assets/a44dcdd2-f9bd-4e5e-9a14-f62d6c69b7f4" />

```
#include <Wire.h> 
#include <LiquidCrystal_I2C.h>
#include <DHTesp.h>

#define SDA 13
#define SCL 14

DHTesp dht;
LiquidCrystal_I2C lcd(0x27,16,2);
int dhtPin = 18;

float celsiusToKelvin(float celsius) {
  return celsius + 273.15;
}


float celsiusToFahrenheit(float celsius) {
  return (celsius * 9.0/5.0) + 32.0;
}

bool i2CAddrTest(uint8_t addr) {
  Wire.begin();
  Wire.beginTransmission(addr);
  if (Wire.endTransmission() == 0) {
    return true;
  }
  return false;
}

void setup() {
  Wire.begin(SDA, SCL);
  if (!i2CAddrTest(0x27)) {
    lcd = LiquidCrystal_I2C(0x3F, 16, 2);
  }
  lcd.init();
  lcd.backlight();
  dht.setup(dhtPin, DHTesp::DHT11);
}

void loop() {
  flag: TempAndHumidity DHT = dht.getTempAndHumidity();
  if (dht.getStatus() != 0) {
    goto flag;
  }
  

  float tempKelvin = celsiusToKelvin(DHT.temperature);
  float tempFahrenheit = celsiusToFahrenheit(DHT.temperature);
  

  lcd.setCursor(0, 0);
  lcd.print("Temp Kelvin: "); 
  lcd.print(tempKelvin, 2);
  lcd.print(" K  ");
  
  lcd.setCursor(0, 1);
  lcd.print("Humidity F: "); 
  lcd.print(tempFahrenheit, 2); 
  lcd.print(" F  ");
  
  delay(2000);
}
```


#### Código
```
#include <Wire.h> 
#include <LiquidCrystal_I2C.h>
#include <DHTesp.h>

#define SDA 13
#define SCL 14

DHTesp dht;
LiquidCrystal_I2C lcd(0x27,16,2);
int dhtPin = 18;

void setup() {
  Wire.begin(SDA, SCL);
  if (!i2CAddrTest(0x27)) {
    lcd = LiquidCrystal_I2C(0x3F, 16, 2);
  }
  lcd.init();
  lcd.backlight();
  dht.setup(dhtPin, DHTesp::DHT11);
}

void loop() {

flag:TempAndHumidity DHT = dht.getTempAndHumidity();
if (dht.getStatus() != 0) {
goto flag;
}
lcd.setCursor(0, 0);
lcd.print("Temperature:"); 
lcd.print(DHT.temperature);
lcd.setCursor(0, 1);
lcd.print("Humidity :"); 
lcd.print(DHT.humidity);
delay(2000);
}
bool i2CAddrTest(uint8_t addr) {
Wire.begin();
Wire.beginTransmission(addr);
if (Wire.endTransmission() == 0) {
return true;
}
return false;
}
```

#### Foto y vídeo

<img width="1289" height="655" alt="image" src="https://github.com/user-attachments/assets/17aa6b30-2af7-4fd0-9e33-ddfaaa44ce00" />


https://github.com/user-attachments/assets/8283de5e-4091-4e82-bd3f-b2a0f4f381e7



</details>

<details>
<summary><h2>Actividad 8</h2></summary>

### Resumen de la actividad
Para esta actividad usaremos la placa de arduino para conectarnos a la red WiFi de iFP y crearemos un punto de acceso al que nos podremos conectar.

### Preguntas

<b>1. ¿A qué red te has podido conectar? Es 5G, 2.4G? Explica.</b>
Me he conectado a la red IFP, que es 5g.

<b>2. Verifica el uso de las librerías que aparecen en el código. ¿Son necesarias las tres? </b>
wifi.h - gestiona la conexion de wifi.
wificlient.h - se encarga de la comunicacion tcp ip basica.
wificlientsecure.h - comunicacion segura con tls ssl.

<b>3. ¿En qué casos utilizaría las librerías de arduino WiFiClient.h y WiFiClientSecure.h? </b>
Las utilizaría cuando quiera compartir datos de forma segura entre dispositivos.

<b>Prueba la conectividad entre un dispositivo como e PC o el móvil a la IP que te brinda el ESP32.</b>
<img width="291" height="176" alt="image" src="https://github.com/user-attachments/assets/d68a6568-e3e4-4d36-8ce7-5e8488ff325e" />
<img width="610" height="274" alt="image" src="https://github.com/user-attachments/assets/916396bd-7d17-4369-ab15-f15054a9bd04" />



### Código

#### Primera parte

```
#include <WiFi.h>
#include <WiFiClient.h>
#include <WiFiClientSecure.h>
const char* ssid = "IFP";   // escribir aquí el SSID de una WiFi
const char* password = "ifpformacion"; // escribir aquí la contraseña de la WiFi 

void setup(){ 
  Serial.begin(9600); // abre un puerto serie y establece la velocidad de transmisión
  delay(2000); 
  Serial.println("Setup start"); 
  WiFi.begin(ssid, password); 
  Serial.println(String("Connecting to ")+ssid);

while (WiFi.status() != WL_CONNECTED) { 
  delay(500);
  Serial.print(".");
}
Serial.println("\nConnected, IP address: ");
Serial.println(WiFi.localIP());
Serial.println("Setup end");
}
void loop() { 
}

```

#### Segunda Parte
```
#include <WiFi.h>
const char *ssid_AP = "yipihotspot"; 
const char *password_AP = "aleksei"; //Enter the router password
IPAddress local_IP(192,168,1,100);
IPAddress gateway(192,168,1,10); 
IPAddress subnet(255,255,255,0); 
void setup(){
Serial.begin(9600);
delay(2000);
Serial.println("Setting soft-AP configuration ... ");
WiFi.disconnect();
WiFi.mode(WIFI_AP);
Serial.println(WiFi.softAPConfig(local_IP, gateway, subnet) ? "Ready" : "Failed!");
Serial.println("Setting soft-AP ... ");
boolean result = WiFi.softAP(ssid_AP, password_AP);
if(result){
Serial.println("Ready");
Serial.println(String("Soft-AP IP address = ") + WiFi.softAPIP().toString());
Serial.println(String("MAC address = ") + WiFi.softAPmacAddress().c_str());
}else{
Serial.println("Failed!");
}
Serial.println("Setup End");
}
void loop() {
}
```
#### Preguntas

<b>1. ¿Cuál es el uso de softAPConfig? Argumenta</b>
SoftAPConfig te permite configurar la red Wi-Fi en modo Punto de Acceso (o Access Point).

<b>2. ¿Cómo puedo conocer la cantidad de dispositivos conectados a mi AP? Para ello investiga el uso de WiFi.softAPgetStationNum() y añade las líneas necesarias al código.</b>
Se vería usando el comando WiFi.softAPgetStationNum().

<b>3. ¿Qué método me permite visualizar la dirección IP de la interfaz de red del punto de acceso?</b>
El método que te permite visualizar la dirección IP es con el comando WiFi.softAPIP().


<b>4. ¿Qué nos permite la opción c_str() en el código?</b>
Esta opción convierte un objeto String en un array de caracteres estilo C. Es esencial cuando una función requiere un char* o const char* en lugar de un objeto String.


</details>

<details>
<summary><h2>Proyecto</h2></summary>

### Briefing

#### 1. Presentación de la idea
Para nuestro proyecto de arduino, hemos decidido recrear una hucha que recoja automáticamente las monedas que se le coloquen encima. Será una caja cerrada que, al activarse el mecanismo, se abrirá y saldrá un brazo mecánico que recogerá la moneda y la meterá dentro. Además, incorporaremos un altavoz que se activará y emitirá un maullido cuando el botón sea accionado.
Para esta idea, hemos tomado inspiración de unas huchas que ya existen, normalmente tematizadas con personajes de series de televisión o animales.
Dentro de la caja meteremos un muñeco de un gato que será el que "roba" la moneda. En caso de que no consigamos ninguna figura o peluche, pintaremos el interior de la caja de negro y le dibujaremos unos ojos brillantes, simulando que hay un gato escondido dentro de la caja oscura.

<img width="894" height="832" alt="image" src="https://github.com/user-attachments/assets/82de4bab-55ba-4a17-81a6-537da82cc154" />

#### 2. Objetivos del proyecto
Con el desarrollo de este proyecto, aprenderemos a:
<ul>
<li>Crear un programa desde cero que detecte estímulos y ponga en marcha un mecanismo sencillo.</li>
<li>Montar dicho mecanismo con piezas fabricadas por nosotros y/o improvisadas</li>
</ul>	

#### 3. Requisitos técnicos
Para montarlo todo necesitaremos:
<ul>
<li>La placa de arduino con el extensor ESP32</li>
<li>Cables</li>
<li>Altavoz</li>
<li>Resistencias</li>
<li>Caja</li>
<li>Un bracito para recoger la moneda</li>
<li>Piezas para que se mueva el brazo</li>
<li>Un muñeco para decorar el interior</li>
<li>Pintura y pegatinas para decorar el exterior</li>
</ul>

#### Metodología de trabajo
En nuestro Trello tenemos listadas las tareas por hacer, los principales pasos siendo:
<ul>
<li>Acabar de concretar qué materiales utilizaremos para fabricar el brazo mecánico</li>
<li>Trabajar en la electrónica de la hucha</li>
<li>Escribir el código y comprobar que funciona como debería</li>
<li>Montarlo todo dentro de la caja y ensamblar el brazo mecánico</li>
<li>Decorar la caja y comprobar que todo funciona correctamente</li>
</ul>

#### Recursos disponibles
Tenemos diversos tutoriales para fabricar una hucha cuentamonedas, este es uno de nuestros favoritos por, además de mostrar como la han hecho, detallan con precisión todos los materiales que han utilizado.
https://blogs.etsii.urjc.es/dseytr/hucha-inteligente-cuenta-monedas/


#### Desafíos y soluciones previstas
De cara a este proyecto, tenemos diversos desafíos que deberemos afrontar, siendo estos:

<ul>
<li><b>Fabricación del brazo mecánico</b></li>
Construir la estructura adecuada para que al accionarse el mecanismo, el brazo haga el movimiento que nosotros queremos y recoja la moneda correctamente.

<li><b>Altavoz</b></li>
Utilizaremos un altavoz que se activará al presionar el botón, junto al brazo eléctrico, y emitirá un maullido.

<li><b>Programación</b></li>
Hasta ahora solo hemos utilizado código que nos brindaban los tutoriales oficiales de Arduino, por lo que tener que escribir nuestro propio código desde cero supondrá todo un reto. 
</ul>

### Esquema eléctrico

</details>
<details>
<summary><h2>Conclusiones</h2></summary>
.
</details>

<details>
<summary><h2>Bibliografía</h2></summary>
</details>

