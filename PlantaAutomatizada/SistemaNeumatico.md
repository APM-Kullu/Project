# Sistema Neumático
Este documento presenta el diseño del sistema neumático de la planta automatizada. Este sistema utiliza tecnología neumática para el control y accionamiento 
de diferentes procesos y mecanismos en la planta. El diseño se basa en la utilización de componentes clave como un compresor de aire, válvulas neumáticas, 
cilindros y otros dispositivos neumáticos. Estos componentes trabajan en conjunto con el PLC para proporcionar energía y control a los distintos mecanismos 
automatizados de la planta.

## Diagrama Sistema Neumático
![Diagrama neumatico_page-0001](https://github.com/APM-Kullu/Project/assets/42346345/26222e50-c0c4-49e7-a6ca-bb3b0fb1604f)

## Compresor
Ya que el compresor solo se usará para el sistema de mordazas neumáticas, se escoge un compresor de 2 etapas 5 HP 500L, el cual cumple con la capacidad de flujo
requerida para accionar los cuatro cilindros neumáticos y con la presión requerida. La referencia del compresor es 
[E230ME0500-500](https://www.evans.com.co/producto/compresor-aire-lubricado-2-etapas-5-hp-motor-electrico-tanque-500-litros-175-psi-e230me0500-500/).

<img src="https://sp-ao.shortpixel.ai/client/to_auto,q_glossy,ret_img,w_450,h_450/https://www.evans.com.co/wp-content/uploads/2017/06/Compresores_EVANS_E230ME0500_500_1L_50.jpg" width="400">

MOTOR:

Potencia del motor: 5.00 HP.
Velocidad del Motor: 1750 RPM.
Tipo de motor: Eléctrico.
Marca del motor: Weg/Siemens.
Fases: Trifásico.
Voltaje: 220/440 V.

CARACTERÍSTICAS:

Tipo de compresor: Reciprocante.
Presión máxima: 175 PSI.
PCM @ 90 PSI: 18.30 pcm.
PCM @ 150 PSI: 16.00 pcm.
Capacidad del tanque: 500.00 L.
Posición del tanque: Horizontal.
Ciclo de trabajo: 70% Trabajo - 30% Descanso.
Tiempo de trabajo: 10000 horas.
Acoplamiento del motor a la cabeza: Banda V.
Tipo de guarda: Metálica.
Presentación: Estacionario.

CENTRO DE COMPRESIÓN:

Número de cabezas: 1.
Número de etapas: 2.
Número de cilindros/pistones: 2.
Modelo del Cabezal: CE230.
Aceite recomendado para la cabeza: RC-AW100 (incluido en la compra del compresor).
Capacidad de aceite para la cabeza: 1.50 L.
Primer y segundo cambio de aceite: 25/50 horas (Usar aceite RC-AW100).
Cambios de aceite posteriores: 1500 horas (Usar aceite RC-X3000 vendido por separado).
Potencia mecánica de la cabeza: 5.00 HP.
Desplazamiento: 23.00 pcm.

El precio del compresor es de **COP 12.066.243**. 

## Unidad de Mantenimiento (FRL)

Para la unidad de mantenimiento se escoge una FRL, la cual combina el filtrado, la regulación de presión y la lubricación en un solo dispositivo, 
garantizando un suministro de aire limpio, regulado y lubricado para los sistemas neumáticos, lo que resulta en un rendimiento óptimo, una mayor durabilidad 
de los componentes y una operación confiable. La referencia de la unidad de mantenimiento es [AC20 Series 8492T115](https://www.mcmaster.com/8492T115/).

<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/849/8492t2-@1x_636987887154604691.png?ver=ImageNotFound">

Serie del fabricante: AC20.
Configuración: En línea.
Tamaño de la tubería: 1/8".
Caudal máximo: 32 scfm a 100 psi.
Presión máxima: 145 psi.
Capacidad de eliminación de partículas: Hasta 5 micrones.
Material del recipiente: Plástico de policarbonato transparente.
Tipo de drenaje: Automático.
Rango de ajuste de presión de salida: 7.25-123 psi.
Capacidad de lubricante: 0.85 oz.
Incluye manómetro.
Altura total: 5 1/2".
Ancho total: 5".
Precisión de regulación: ±3%.

El precio del compresor es de **USD 94.40**.

## Válvulas de Control Direccional

Se han seleccionado válvulas 5/2 con activación por bobina eléctrica y retorno por muelle. Estas válvulas cuentan con dos posiciones de trabajo y cinco conexiones, lo que permite controlar el flujo de aire en el sistema neumático. La activación por bobina eléctrica proporciona un control preciso y rápido de las válvulas, mientras que el retorno por muelle garantiza la seguridad y la fiabilidad de la operación, asegurando que las válvulas vuelvan a su posición original en caso de fallo eléctrico. La referencia de las válvulas es [6425K11](https://www.mcmaster.com/6425K11/).

<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/642/6425k132-@1x_636881540402220587.png?ver=ImageNotFound">
<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/c03/c03a-E5l1-digital-master1551986280-p9@1x_636874820347248581.png?ver=ImageNotFound">

Función: Control direccional.
Tipo de válvula: Tipo carrete (spool).
Tipo de válvula de control direccional de aire: 4 vías.
Patrón de flujo: 5/2.
Para tipo de cilindro de aire: Doble efecto.
Actuación: Eléctrica (solenoides).
Retorno de actuación: Por resorte.
Caudal máximo: 56 scfm a 100 psi.
Rango de presión: 15-150 psi.
Rango de temperatura: -10°F a 115°F.
Tipo de conexión de entrada: Roscada.
Tamaño de entrada: 1/8 NPTF.
Tipo de conexión de salida: Roscada.
Tamaño de salida: 1/8 NPTF.
Tipo de conexión de escape: Roscada.
Tamaño de escape: 1/8 NPTF.
Material del cuerpo: Aluminio.
Dimensiones generales:
Longitud: 5 1/2 pulgadas.
Ancho: 7/8 pulgadas.
Altura: 2 3/4 pulgadas.

El precio de la válvula es de **USD 112.92** y se requieren 4.

## Cilindros Neumáticos 

La referencia de los cilindros neumáticos utilizados se encuentra en [60405K127](https://www.mcmaster.com/60405K127/) y se usa en el 
[Mecanismo Mordaza Neumática](MecanismoMordazaNeumatica.md). 

<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/640/6402t811-1647969487-p9@1x_637835482946000001.png?ver=ImageNotFound">

Tipo de cilindro: Tie Rod (de tipo tirante).
Tamaño del orificio: 32 mm.
Carrera: 275 mm (retraído: 421 mm, extendido: 696 mm).
Fuerza a 50 psi: 63 lbs.
Fuerza a 100 psi: 125 lbs.
Tipo de amortiguación: Amortiguación ajustable.
Tipo de actuación: Doble efecto (aire para extender y aire para retraer).
Material del cuerpo: Aluminio extruido.
Material del émbolo: Acero inoxidable 431.
Diámetro de la varilla: 12 mm.
Tipo de rosca de la varilla: M10.
Tamaño de la entrada de aire: 1/8 (rosca BSPP).

Estas características demuestran que el cilindro neumático seleccionado es adecuado para nuestras necesidades en términos de tamaño, fuerza, capacidad de amortiguación y durabilidad.

El precio del cilindro es **USD 233.28** y se requieren 4.

## Mufflers

Los "mufflers" (también conocidos como silenciadores o atenuadores) son dispositivos utilizados para reducir el ruido generado por el escape de gases en sistemas de aire comprimido. Estos dispositivos se instalan en el sistema de escape o en las salidas de aire y tienen la función de disminuir la intensidad del sonido producido por el flujo de gases. Se utilizan comúnmente en las salidas de aire de las válvulas de control direccional en sistemas neumáticos. Estos dispositivos se instalan en la salida de escape de las válvulas para reducir el ruido generado por el escape de aire comprimido. La referencia escogida es [7352N61](https://www.mcmaster.com/7352N61/).

<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/735/7352N61multipositive_top_positive_right_washer_1614256045_192@1x_637498313096587939.png?ver=ImageNotFound">

Estilo: A.
Tipo de conexión: Tubo.
Tipo de conexión de tubo: Roscado.
Tamaño de tubo: 1/8".
Tipo de rosca: BSPP (British Standard Pipe Parallel).
Género: Macho.
Caudal máximo: 21 scfm @ 100 psi (Pies cúbicos estándar por minuto a 100 psi).
Presión máxima: 175 psi.
Temperatura máxima: 175° F.
Altura: 1 3/4".
Estilo de accionamiento: Hexagonal externo.
Para uso con: Aire, gas inerte.
Material: Latón.
Construcción del cuerpo: Poroso.
Para reducir: Ruido, partículas.
Remueve partículas de tamaño hasta: 40 micrones.
Calificación de reducción de ruido: 10-20 dB.

El precio de los Mufflers es **USD 4.18** y se requieren 8. 

## Válvulas de control de flujo

La válvula de control de flujo de aire con codo ajustable de precisión. Esta válvula se utiliza en sistemas neumáticos para controlar y regular el flujo de aire en una dirección específica. La función principal de esta válvula es controlar la velocidad y el flujo de aire en un circuito neumático. Será utilizada para regular la velocidad de los cilindros neumáticos. La referencia escogida es [4076K37](https://www.mcmaster.com/4076K37/).

<img src="https://www.mcmaster.com/mvD/Contents/gfx/ImageCache/407/4076k28--885391fc6361560182088-p9@1x_636957609029154304.png?ver=ImageNotFound">

Uso: Aire comprimido.
Función de la válvula: Ajuste de flujo.
Tipo de válvula: Aguja.
Forma: Codo de 90°.
Actuación: Presión.
Control de flujo: En una dirección.
Tipo de control de flujo: Salida del cilindro.
ISO Designación: Meter Out.
Mecanismo de ajuste de flujo: Dial.
Número de puertos: 2 (1 de flujo, 1 de entrada, 1 de salida).
Material del cuerpo: Plástico de nylon.
Material del accesorio: Latón.
Coeficiente de flujo (Cv): 0.006.
Tasa de flujo máxima: 0.1 scfm a 100 psi.
Presión máxima: 145 psi.
Rango de temperatura: 35° a 155° F.
Dimensiones: Longitud de 15/16", ancho de 7/16", altura de 1 5/16".
Conexión de entrada: Roscada (tipo NPT) de 1/8".
Conexión de salida: Push to Connect para tubo de 1/8" de diámetro exterior.

El precio de la válvula es de **USD 22.75** y se requieren 8.
