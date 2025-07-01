La **Tuxedo 18650** es una placa de desarrollo con hardware integrado. Su nucleo contiene un microcontrolador WROOM32-ESP32, el cuál corre a 240MHz, tiene WiFi y Bluetooth. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/5fb13976-9757-4182-aaf8-e7b9585a1828" alt="Tuxedo 18650 front" width="512"/>
  <br><br>
  <img src="https://github.com/user-attachments/assets/76dbbbf6-7081-4a05-93e0-28ae0a758c0c" alt="Tuxedo 18650 back" width="512"/>
</p>

Sus características claves son:

- Soporta 2 baterías 18650 en serie, e incluye cargador.
- Puede funcionar a 3.3V y 5V, con un selector deslizable.
- Tiene 8 GPIOs con alimentación VCC y GND cada uno, así que puedes conectar hasta 8 servos de 5V.
- Conectores para I2C, SPI y Voltaje de la batería (entre 6.4V y 8.4V).
- 2 drivers puente H para manejar 2 motores de DC de hasta 1.5A o un motor a pasos bipolar.

<p align="center">
  <img src="https://github.com/user-attachments/assets/02f646e5-ef69-476a-b33a-822569a2e458" alt="Tuxedo 18650 caracteristicas" width="720"/>
</p>

Pero lo verdaderamente interesante de esta placa no es su microcontrolador, si no todo el hardware que trae embebido en la propia tarjeta, de esta manera, el usuario puede llevar a cabo prácticas y proyectos muy interesantes y completos, sin la necesidad de conectar módulos externos; no obstante, la Tuxedo 18650 también lo permite, puesto que tiene los puertos **I2C**, **SPI**, **USB** y entradas y salidas digitales.

Su principal característica y la cual le da el nombre, es que es capaz de funcionar con **2 baterías recargables 18650** en serie, ya que possé tanto un conector JST de 2 pines, como un cargador de baterías LiPo. Es importante señalar que, únicamente se deben conectar 2 pilas 18650 en serie, con la polaridad correcta.

<p align="center">
  <img src="https://github.com/user-attachments/assets/21a002cb-1e6a-434e-a294-c5bdc4cc220f" alt="Tuxedo 18650 baterias" width="512"/>
</p>

En resumen, la placa Tuxedo 18650 contiene lo siguiente:

- Conector de batería JST de 2mm de separación (usado en baterías LiPo), para conectar un paquete de 2 baterías 18650 en serie.
- Circuito de carga de batería con detector de batería faltante, y LEDs de carga y carga completa.  
- Convertidor USB a Serial, con conector USB C.
- Fusible reseteable de hasta 3A. ¡Olvidate de los cortos circuitos!
- Regulador de 3.3V a 500mA.
- Fuente de alimentación de 5V 3A.
- Selector de voltaje entre 3.3V y 5V, ideal para trabajar con circuitos TTL y CMOS.
- 3 Puertos I2C (se conectan en paralelo al puerto I2C del ESP32).
- 1 Puerto SPI.
- Conversor de niveles de entrada o salida para todas las señales digitales, incluidos el I2C y el SPI.
- 2 Drivers DRV8837 puente H de hasta 1.5A para 2 motores de DC o uno a pasos bipolar.
- Buzzer pasivo super compacto.
- 3 botónes de usuario + botón de Reset.
- 2 LEDs de usuario.
- 1 LED Neopixel RGB digital.
- Interruptor de alimentación deslizable.

En este enlace podrás descargar el manual de uso: [Manual de usuario Tuxedo 18650 V1.0](https://github.com/RocketLauncherCDMX/Tuxedo18650/blob/0786c899abc0366a833ea90629ad312b154c0426/Tuxedo%2018650%20user%20manual%20V1.0.pdf)
