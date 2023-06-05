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
- 
### Eje X:
- Motor Eje Z: 5 kg
- Carril Eje X: 8 kg
- Mounting plate: 0.713 kg
- Motor husillo: 4.3 kg
- Broca: 0.01 kg

### Eje Z:
- Motor husillo: 4.3 kg
- Broca: 0.01 kg

## Cálculo de Torque necesario para cada eje
En primer lugar se fija la aceleración deseada para cada eje, esto teniendo en cuenta el límite de los carriles y las velocidades máximas de cada eje. Luego se hace una simplificación de la carga de cada eje como una masa puntual


## Diagrama Sistema Neumático
![Diagrama neumatico_page-0001](https://github.com/APM-Kullu/Project/assets/42346345/26222e50-c0c4-49e7-a6ca-bb3b0fb1604f)

## Compresor
Ya que el compresor solo se usará para el sistema de mordazas neumáticas, se escoge un compresor de 2 etapas 5 HP 500L, el cual cumple con la capacidad de flujo
requerida para accionar los cuatro cilindros neumáticos y con la presión requerida. La referencia del compresor es 
[E230ME0500-500](https://www.evans.com.co/producto/compresor-aire-lubricado-2-etapas-5-hp-motor-electrico-tanque-500-litros-175-psi-e230me0500-500/).

<img src="https://sp-ao.shortpixel.ai/client/to_auto,q_glossy,ret_img,w_450,h_450/https://www.evans.com.co/wp-content/uploads/2017/06/Compresores_EVANS_E230ME0500_500_1L_50.jpg" width="400">

MOTOR:

Potencia del motor: 5.
