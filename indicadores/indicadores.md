# Parámetros de rendimiento  y KPIs

De acuerdo con el [diagrama VSM](https://drive.google.com/file/d/1R6CTQlbLSqZXP_ZOIvwtcjmw3XsWAsQU/view?usp=share_link) diseñado para nuestro proyecto, se cuenta con una línea de producción compuesta por 6 etapas:
1. Corte láser
2. **Taladrado:** Presenta una bifurcación para el procesamiento independiente de piezas planas y piezas que requieren una orientación específica.
3. Lijado
4. Sellado
5. Lacado
6. **Ensamble:** Presenta una ramificación de 3 líneas, para el ensamblaje independiente de los 3 productos que se trabajarán.
<br><br>

### Trabajo en proceso (WIP):
Para cada producto el proceso de manufactura será secuencial y abarcará cada una de las 6 etapas descritas. Esto implica la existencia de 5 almacenes intermedios y 6 estaciones, por producto. Por tanto, la expresión para estimar el WIP está dada por:<br><br>
<p align="center">$$WIP=\sum_{i=1}^5 W_i + \sum_{i=1}^6 WE_i$$</p>
<br><br>

### Takt time:

### Tiempo de ciclo ($T_c$):
