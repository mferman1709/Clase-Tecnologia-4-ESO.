# Papelera inteligente
<img width="1254" height="1254" alt="image" src="https://github.com/user-attachments/assets/c2d4a5eb-64f9-4aeb-8365-101382d86eb5" />

## Descripción del proyecto

Mi proyecto de **Teleco Games** consistía en diseñar una papelera inteligente con el objetivo de fomentar que los jóvenes utilicen más las papeleras y sean más conscientes de la importancia de mantener los espacios limpios.

La idea principal del proyecto era crear una papelera que incorporase tecnología para hacer que tirar basura fuese una acción más interactiva. Para ello, se planteó colocar una pantalla en la parte frontal de la papelera que mostrase un porcentaje aproximado de llenado, permitiendo conocer de una forma sencilla cuánto espacio disponible queda en su interior.

De esta manera, la papelera no sería un simple recipiente para depositar residuos, sino un elemento que proporciona información al usuario y genera una mayor interacción.

Además, se planteó conectar la papelera con una aplicación móvil. Cada vez que una persona depositase correctamente un residuo, el sistema podría registrarlo y añadir puntos al usuario. La finalidad de esta puntuación sería hacer el proceso más dinámico y parecido a un juego, utilizando elementos como recompensas o rankings para motivar la participación.

El objetivo principal no sería únicamente recoger basura, sino conseguir que las personas tengan una mayor motivación para utilizar correctamente las papeleras y cuidar los espacios comunes.

---

## Funcionamiento del sistema

El funcionamiento de la papelera se basaría en la utilización de varios sensores conectados a un sistema de control.

Uno de los sensores principales permitiría conocer el nivel de llenado de la papelera. Para ello, se podría utilizar un sensor de distancia que midiese cuánto espacio queda libre en el interior. Con esta información, el sistema calcularía un porcentaje aproximado y lo mostraría en la pantalla frontal.

Cuando un usuario tirase basura, la papelera detectaría la acción mediante sensores y enviaría la información al controlador principal. Este se encargaría de actualizar el porcentaje de llenado y comunicar los datos con la aplicación móvil.

La aplicación tendría la función de almacenar los puntos obtenidos por cada usuario. De esta forma, se podría crear un sistema de participación donde las personas obtengan una recompensa simbólica por realizar acciones positivas relacionadas con la limpieza y el reciclaje.

---

## Componentes necesarios

Para desarrollar este proyecto serían necesarios diferentes componentes electrónicos:

### Sensores

Los sensores serían una parte fundamental del sistema, ya que permiten obtener información del estado de la papelera.

Algunos sensores que podrían utilizarse son:

- **Sensor ultrasónico:** serviría para medir la distancia hasta los residuos acumulados y calcular el porcentaje de llenado.
- **Sensor de proximidad:** permitiría detectar cuándo una persona se acerca a la papelera.
- **Sensor de apertura:** podría utilizarse para detectar cuándo se abre la tapa o cuándo se deposita un residuo.

<img width="447" height="447" alt="image" src="https://github.com/user-attachments/assets/71e7e6ec-3bb4-4449-9c4b-4d8b0adc7e32" />

### Pantalla LED

La pantalla situada en la parte frontal permitiría mostrar información al usuario de una forma sencilla.

Sus principales funciones serían:

- Mostrar el porcentaje de llenado de la papelera.
- Indicar si la papelera está cerca de llenarse.
- Mostrar mensajes después de utilizarla, como agradecimientos o información relacionada con el reciclaje.

<img width="554" height="554" alt="image" src="https://github.com/user-attachments/assets/d08ab28f-9194-4e72-8c09-a928905eefed" />

### Microcontrolador

Sería necesario un componente encargado de controlar todos los elementos del sistema. Este recibiría la información de los sensores, procesaría los datos y enviaría las órdenes necesarias a la pantalla y a la aplicación.

Algunas opciones posibles serían placas como Arduino o ESP32, ya que son dispositivos utilizados habitualmente en proyectos electrónicos por su facilidad de programación y conexión con sensores.

### Conexión con la aplicación móvil

Para enviar información entre la papelera y el teléfono sería necesario algún sistema de comunicación inalámbrica, como Bluetooth o WiFi.

Gracias a esta conexión, la aplicación podría recibir los datos de la papelera y actualizar la puntuación del usuario.

---

## Posibles aplicaciones

Aunque la idea inicial del proyecto está enfocada principalmente a jóvenes, este sistema podría tener otros usos.

Por ejemplo, podría aplicarse en empresas o zonas de trabajo para facilitar la gestión de residuos. Los trabajadores encargados de la limpieza, como los barrenderos o personal de mantenimiento, podrían consultar mediante una aplicación qué papeleras están llenas y cuáles necesitan ser vaciadas.

Esto permitiría mejorar la organización de las tareas de limpieza, evitando revisiones innecesarias y optimizando el tiempo empleado.

También podría instalarse en lugares con gran cantidad de personas, como colegios, universidades, parques o centros comerciales, donde podría ayudar a fomentar mejores hábitos relacionados con el cuidado del entorno.

<img width="1200" height="900" alt="image" src="https://github.com/user-attachments/assets/f3ed1e52-a737-4110-bb22-70717c6a0040" />

---

## Conclusión

La papelera inteligente es un proyecto que combina electrónica y tecnología móvil para intentar mejorar un problema cotidiano: la falta de uso adecuado de las papeleras.

Mediante sensores, una pantalla y una aplicación móvil, se busca crear un sistema más interactivo que motive a los usuarios a tirar la basura correctamente. Además, sus posibles aplicaciones en ámbitos laborales o espacios públicos podrían ayudar a mejorar la gestión de residuos y hacer más eficiente el mantenimiento de estos lugares.
