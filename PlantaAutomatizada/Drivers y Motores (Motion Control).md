# Drivers y Motores - Control de Movimiento

Para determinar los servomotores y drivers adecuados que se utilizarán en el sistema de taladrado, es necesario realizar cálculos para determinar el torque requerido en cada eje del mecanismo. Además, consideraremos el uso de carriles lineales para cada eje, lo cual afectará los cálculos de velocidad y aceleración. Es necesario tener en cuenta los carriles de guía lineal del [Mecanismo de taladrado](MecanismoTaladrado.md) ya que estos ponen límites en las cargas, velocidades y aceleraciones.

## Carriles de guía lineal
Distancia por vuelta: 10 mm/rev

**Capacidad:** 395 lbs (179 kg).

**Aceleración máxima:** 0.3 g (2.94 m/s^2)

**Torque máximo:** 176 in-oz (1.243 N-m)

**Velocidad máxima:**
- Eje X: 650 mm/s (3900 RPM)
- Eje Y: 470 mm/s (2820 RPM)
- Eje Z: 790 mm/s (4740 RPM)

## Cargas de cada eje
### Eje Y:
- Mounting plate x2: 3.4 kg
- Motor Eje X: 5 kg
- Carril Eje X: 9 kg
- Motor Eje Z: 5 kg
- Carril Eje X: 8 kg
- Mounting plate: 0.713 kg
- Motor husillo: 4.3 kg
- Broca: 0.01 kg

**TOTAL: 35 kg**
### Eje X:
- Motor Eje Z: 5 kg
- Carril Eje X: 8 kg
- Mounting plate: 0.713 kg
- Motor husillo: 4.3 kg
- Broca: 0.01 kg

**TOTAL: 18 kg**
### Eje Z:
- Motor husillo: 4.3 kg
- Broca: 0.01 kg

**TOTAL: 4.31 kg**

## Cálculo de Torque necesario para cada eje
En primer lugar se fija la aceleración deseada para cada eje, esto teniendo en cuenta el límite de los carriles y las velocidades máximas de cada eje. Luego se hace una simplificación de la carga de cada eje como una masa puntual par realizar el cálculo del torque necesario usando la formula de torque:
$$T_{in}=\frac{F\cdot P}{2000 \pi \cdot \eta }$$

### Eje Y:
Se supone una velocidad máxima de 450 mm/s para que no exceda la capacidad de este carril y un tiempo de aceleración de 0.2 s:

<img src="https://github.com/APM-Kullu/Project/assets/42346345/a36e4887-97ad-4a17-9b55-99fb3cdc6a08" width="500" alt="Imagen escalada">

$a=\frac{450\frac{mm}{s}}{0.2 s}$      $a=2250\frac{mm}{s^2}$      $a=2.25\frac{m}{s^2}$

Ahora el diagrama de cuerpo libre queda: 

<img src="https://github.com/APM-Kullu/Project/assets/42346345/7bfbc5ed-a156-41e6-8bda-eacba0e5138b" width="500" alt="Imagen escalada">

y por último se puede hallar el torque con la fórmula antes mencionada:

$T_{in}=\frac{78.75 N\cdot 10 mm}{2000 \pi \cdot 0.85 }$

**$T=0.147 N-m$**

**$V_{max}=0.45 \frac{m}{s}(2700 RPM)$**

**$a_{max}=2.25 \frac{m}{s^2}$**


### Eje X:
Se supone una velocidad máxima de 600 mm/s para que no exceda la capacidad de este carril y un tiempo de aceleración de 0.25 s:

<img src="https://github.com/APM-Kullu/Project/assets/42346345/d4874cc2-2f0b-462d-8cd5-44dd71883064" width="500" alt="Imagen escalada">

$a=\frac{600\frac{mm}{s}}{0.25 s}$      $a=2400\frac{mm}{s^2}$      $a=2.4\frac{m}{s^2}$

Ahora el diagrama de cuerpo libre queda: 

<img src="https://github.com/APM-Kullu/Project/assets/42346345/ee0e6f8d-2c65-44fc-a10b-8a01bfc0d27d" width="500" alt="Imagen escalada">

y por último se puede hallar el torque con la fórmula antes mencionada:

$T_{in}=\frac{43.2 N\cdot 10 mm}{2000 \pi \cdot 0.85 }$

**$T=0.081 N-m$**

**$V_{max}=0.6 \frac{m}{s}(3600 RPM)$**

**$a_{max}=2.4 \frac{m}{s^2}$**

### Eje Z:
Se supone una velocidad máxima de 600 mm/s para que no exceda la capacidad de este carril y un tiempo de aceleración de 0.25 s:

<img src="https://github.com/APM-Kullu/Project/assets/42346345/d4874cc2-2f0b-462d-8cd5-44dd71883064" width="500" alt="Imagen escalada">

$a=\frac{600\frac{mm}{s}}{0.25 s}$      $a=2400\frac{mm}{s^2}$      $a=2.4\frac{m}{s^2}$

Ahora el diagrama de cuerpo libre, suponiendo el caso más crítico en donde el motor debe acelerar la carga en contra de la gravedad, queda: 

<img src="https://github.com/APM-Kullu/Project/assets/42346345/f3ad51d8-ccac-49de-8f74-1cb3fbc9d024" width="500" alt="Imagen escalada">

y por último se puede hallar el torque con la fórmula antes mencionada:

$T_{in}=\frac{53.63 N\cdot 10 mm}{2000 \pi \cdot 0.85 }$

**$T=0.099 N-m$**

**$V_{max}=0.6 \frac{m}{s}(3600 RPM)$**

**$a_{max}=2.4 \frac{m}{s^2}$**


## Selección de motor y Driver
Seleccionar el servomotor adecuado implicó considerar el tamaño requerido del marco para los carriles de guía lineal, el cual debía ser de tamaño NEMA 23. Para cumplir con este requisito, se buscó dentro de la familia de servomotores Kinetix TL/TLY que ofrece el tamaño deseado. Entre los modelos disponibles, se encontró que el motor de referencia [TLY-A220P-BJ64AA](https://configurator.rockwellautomation.com/configurator/0E77E6A8D22D45FCA1707BD86DAB74A1/summary) cumple con el torque y la velocidad máxima deseados. Además, este motor es compatible con los drivers [Kinetix 350](https://www.rockwellautomation.com/es-co/products/hardware/allen-bradley/motion-control/servo-drives/single-axis-control/2097-kinetix-350.html).

<img src="https://www.rockwellautomation.com/resources/images/productinfo/IDW_1000x1000/TLY/TLY-A220T-HJ64AA_1000x1000.jpg" width="400">

Frame Size: 2 = 70 mm (2.75 in.) or NEMA 23
Feedback: Absolute Encoder, Battery-Backed, Multi-Turn
Mounting: 70 mm bolt circle metric flange
Connectors: Cables with circular connectors, 1 m (39.4in.)
Brake Option: 24V DC Brake
Magnet Stack Length: Two Stack
Bulletin Number: TL-Series (TLY)
Rated Speed: 5000 rpm
Enclosure/Shaft Key/Shaft Seal: IP65 housing/ Shaft key/No shaft seal
Factory Options: Standard (Metric)
Torque String: 0.757 Nm

El servomotor está equipado con un encoder absoluto de 17 bits, lo que equivale a 131,072 cuentas por vuelta completa del rotor. Teniendo en cuenta que cada vuelta del rotor corresponde a un avance lineal de 10 mm, la resolución de posición para cada eje sería aproximadamente de 0.000076 mm. 


