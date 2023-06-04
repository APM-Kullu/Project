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

El precio del compresor es de COP 12.066.243. 

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

El precio del compresor es de USD 94.40.

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

El precio de la válvula es de USD 112.92.

## Cilindros Neumáticos 




La materia prima es una lámina de MDF de 15 mm de espesor y de dimensiones 1.8 m x 2.4 m. La referencia de la lámina es [Lámina de MDF](https://colombia.masisa.com/producto/mdf/).

<img src="https://i.ebayimg.com/images/g/pq0AAOSwDWVgEWoS/s-l1600.jpg" width="400">

Las láminas son vendidas por Masisa  Colombia, hace falta una cotización al por mayor (Cuantas).

<!-- -------------------------------------------------------------------------------------------------------------------------------------------------------- -->
## Corte previo de lámina 

Para cortar MDF se requiere de una sierra industrial, en este caso se hará una estación de corte con una sierra circular de mano. Se puede utilizar una sierra circular con una potencia mínima de 1200W y una velocidad de al menos 4500 RPM. Sin embargo, es importante tener en cuenta que la capacidad de corte (15 mm) también dependerá del diámetro de la hoja de sierra, la calidad y el tipo de la hoja de sierra, así como de la velocidad de alimentación del material. En general, se recomienda utilizar una hoja de sierra con un número de dientes adecuado para cortar MDF, que puede variar de 40 a 80 dientes. También es importante asegurarse de que la hoja de sierra esté afilada y en buen estado para garantizar un corte limpio y preciso.

Para esta etapa se escogió la maquina [Sierra Circular 7-1/4-pulg 1500W 6000RPM GKS 150](https://homecenterco.scene7.com/is/image/SodimacCO/358623_1?fmt=jpg&fit=fit,1&wid=420&hei=420).
