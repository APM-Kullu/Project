# Gestión de Proyecto

Para la organización del proyecto se utiliza la herramienta de GitHub Projects, donde se asignan tareas a los integrantes del equipo y se plantea un cronograma mediante un diagrama de Gantt.

El proyecto esta disponible en este [enlace](https://github.com/orgs/APM-Kullu/projects/1).

## Metodología - OBSOLETA

Debido a las características del proyecto en donde los conocimientos requeridos serán adquiridos durante el desarrollo, se plantea una serie de componentes generales, que serán desglosados en tareas especificas a medida que se avance en el proyecto y se comprenda mejor el alcance de cada componente, asignando cada tarea a un item especifico dentro de Github Projects, donde se definirá un responsable y un plazo de desarrollo. Esto estará acompañado con dos reuniones semanales los días Miércoles y Domingos, donde se discutirán los avances del proyecto y se crearan las tareas que se consideren pertinentes al corto plazo e igualmente se asignaran aquellas que previamente se hallan asignado.

De esta manera la metodología planteada no propone un cronograma a largo plazo, mas halla de tener en cuenta las fechas de entrega, sino que se basa en un trabajo incremental, donde se van desarrollando las tareas de acuerdo al estado del proyecto, esto con el fin de que la herramienta de GitHub Projects sea verdaderamente útil para la gestión del proyecto y no se convierta en un obstáculo al no poder cumplir de forma estricta con un cronograma.


## Componentes de Proyecto

El proyecto se divide en las siguientes componentes, donde cada uno se corresponde  con una etiqueta en GitHub Projects:

- Gestión de Proyecto: [Project](https://github.com/APM-Kullu/Project/labels/Project)
- CAD: [CAD](https://github.com/APM-Kullu/Project/labels/CAD)
- Diseño de Planta: [Plant](https://github.com/APM-Kullu/Project/labels/Plant)
- Indicadores de desempeño: [Indicators](https://github.com/APM-Kullu/Project/labels/Indicators)
- Celda robotizada: [Robotics](https://github.com/APM-Kullu/Project/labels/Robotics)
- Digital Factory: [DigiFac](https://github.com/APM-Kullu/Project/labels/DigiFac)
- PLC: [PLC](https://github.com/APM-Kullu/Project/labels/PLC)
- Comunicaciones: [Comms](https://github.com/APM-Kullu/Project/labels/Comms)
- SCADA - Industria 4.0: [SCADA](https://github.com/APM-Kullu/Project/labels/SCADA)


## EDT

### Definiciones
- Diseño global de planta: Se refiere a la selección de procesos y maquinas que contiene la planta de manufactura, incluyendo la interacción entre ellos, sin tener en cuenta los detalles de diseño de cada uno de ellos, como el control, sensores, etc.
- SyA: Sensores y Actuadores.
- Tecnomatix: Software para simulación de diseño global de planta de manufactura.
- Ignition: Software para implementación de sistemas SCADA.
- Diseño de la red de simulación: Se refiere a la planeación de como se comunicaran los diferentes elementos involucrados en la simulación de los procesos que se automatizaran, incluyendo el diseño de la Red, la preparación de dispositivos requeridos, asi como la configuración del software de comunicaciones.

<table>
  <thead>
    <tr>
      <th>Código</th>
      <th>Descripción</th>
      <th>Responsable</th>
      <th>Etiqueta</th>
    </tr>
  </thead>
  <tbody>
    <tr> <td>1    </td><td>Gestión de Proyecto                                               </td><td>        </td><td>          </td></tr>
    <tr> <td>1.1  </td><td>Planeación                                                        </td><td>        </td><td>          </td></tr>
    <tr> <td>1.1.1</td><td>Definición de EDT                                                 </td><td>Camilo  </td><td>Project   </td></tr>
    <tr> <td>1.1.2</td><td>Diagrama de Gantt                                                 </td><td>Camilo  </td><td>Project   </td></tr>
    <tr> <td>1.1.3</td><td>Estimación de costos de proyecto                                  </td><td>Julian  </td><td>Project   </td></tr>
    <tr> <td>1.3  </td><td>Indagación de indicadores de desempeño                            </td><td>Juan    </td><td>Indicators</td></tr>
    <tr> <td>1.4  </td><td>Análisis económico de proyecto                                    </td><td>Juan    </td><td>Indicators</td></tr>
    <tr> <td>1.5  </td><td>Creación de Logotipo                                              </td><td>Juan    </td><td>Project   </td></tr>
    <tr> <td>1.6  </td><td>Web de proyecto                                                   </td><td>Julian  </td><td>Project   </td></tr>
    <tr> <td>2    </td><td>Pre-proyecto                                                      </td><td>        </td><td>          </td></tr>
    <tr> <td>2.1  </td><td>Diseño CAD de los productos                                       </td><td>        </td><td>          </td></tr>
    <tr> <td>2.1.1</td><td>Taburete                                                          </td><td>Camilo  </td><td>CAD       </td></tr>
    <tr> <td>2.1.2</td><td>Soporte de Vinos                                                  </td><td>Julian  </td><td>CAD       </td></tr>
    <tr> <td>2.1.3</td><td>Base de Portátil                                                  </td><td>Juan    </td><td>CAD       </td></tr>
    <tr> <td>2.2  </td><td>Diseño global de planta no automatizada                           </td><td>        </td><td>          </td></tr>
    <tr> <td>2.2.1</td><td>Selección de etapas de planta no automatizada                     </td><td>Todos   </td><td>Plant     </td></tr>
    <tr> <td>2.2.2</td><td>Desglose de etapas de planta no automatizada                      </td><td>Julian  </td><td>Plant     </td></tr>
    <tr> <td>2.2.3</td><td>Selección de maquinaria y materia prima de planta no automatizada </td><td>Santiago</td><td>Plant     </td></tr>
    <tr> <td>2.2.4</td><td>Diseño de planos de manufactura                                   </td><td>Camilo  </td><td>CAD       </td></tr>
    <tr> <td>2.2.5</td><td>Estimación de tiempos de etapas de planta no automatizada         </td><td>Camilo  </td><td>Plant     </td></tr>
    <tr> <td>2.2.6</td><td>Implementación de planta no automatizada en Tecnomatix            </td><td>Juan    </td><td>Plant     </td></tr>
    <tr> <td>2.2.7</td><td>Indicadores de desempeño de planta no automatizada                </td><td>Juan    </td><td>Indicators</td></tr>
    <tr> <td>3    </td><td>Diseño de propuesta de automatización                             </td><td>        </td><td>          </td></tr>
    <tr> <td>3.1  </td><td>Diseño global de planta automatizada                              </td><td>        </td><td>          </td></tr>
    <tr> <td>3.1.1</td><td>Planteamiento de propuestas de automatización                     </td><td>Todos   </td><td>          </td></tr>
    <tr> <td>3.1.2</td><td>Selección y desglose de etapas de planta automatizada             </td><td>Santiago</td><td>Plant     </td></tr>
    <tr> <td>3.1.3</td><td>Análisis de costos de equipos de planta automatizada              </td><td>Santiago</td><td>Plant     </td></tr>
    <tr> <td>3.1.4</td><td>Implementación de planta automatizada en Tecnomatix               </td><td>Juan    </td><td>Plant     </td></tr>
    <tr> <td>3.1.5</td><td>Indicadores de desempeño de planta automatizada                   </td><td>Juan    </td><td>Indicators</td></tr>
    <tr> <td>3.2  </td><td>Diseño de la red de simulación                                    </td><td>Camilo  </td><td>Comms     </td></tr>
    <tr> <td>3.3  </td><td>Celda robotizada                                                  </td><td>        </td><td>          </td></tr>
    <tr> <td>3.3.1</td><td>Diseño de celda robotizada en software incluyendo SyA             </td><td>Julian  </td><td>Robotics  </td></tr>
    <tr> <td>3.3.2</td><td>Calculo e implementación de trayectorias                          </td><td>Julian  </td><td>Robotics  </td></tr>
    <tr> <td>3.3.3</td><td>Configuración OPC para celda robotizada                           </td><td>Juan    </td><td>Comms     </td></tr>
    <tr> <td>3.3.4</td><td>Configuración de Ignition para celda robotizada                   </td><td>Juan    </td><td>SCADA     </td></tr>
    <tr> <td>3.4  </td><td>Digital Factory                                                   </td><td>        </td><td>          </td></tr>
    <tr> <td>3.4.1</td><td>Diseño de gemelos digitales en NX (Modelo + SyA)                  </td><td>Santiago</td><td>DigiFac   </td></tr>
    <tr> <td>3.4.2</td><td>Diseño y calculo de trayectorias de gemelos digitales             </td><td>Santiago</td><td>DigiFac   </td></tr>
    <tr> <td>3.4.3</td><td>Configuración OPC para gemelos digitales                          </td><td>Juan    </td><td>Comms     </td></tr>
    <tr> <td>3.4.4</td><td>Configuración de Ignition para gemelos digitales                  </td><td>Juan    </td><td>SCADA     </td></tr>
    <tr> <td>3.5  </td><td>PLC                                                               </td><td>        </td><td>          </td></tr>
    <tr> <td>3.5.1</td><td>Diagrama GRAFCET del algoritmo de control                         </td><td>Camilo  </td><td>PLC       </td></tr>
    <tr> <td>3.5.2</td><td>Implementación en Ladder de algoritmo de control                  </td><td>Camilo  </td><td>PLC       </td></tr>
    <tr> <td>3.5.3</td><td>Configuración OPC para simulador de PLC                           </td><td>Camilo  </td><td>PLC       </td></tr>
    <tr> <td>4    </td><td>Implementación física de planta automatizada                      </td><td>Juan    </td><td>Project   </td></tr>
  </tbody>
</table>

## Responsables

### Componentes de proyecto
- Camilo: Planeación y Cronograma (EDT + Diagrama de Gantt)
- Julian: Análisis de costos, matriz comunicaciones
- Santiago: Adquisiciones, FOB de maquinas + impuestos + Aduanas + etc
- Juan: Modelo de negocio, empresa, rentabilidad

### Componentes técnicos
- Juan: SCADA + Indicadores
- Julian: RobotStudio + Web
- Camilo: PLC + COM
- Santiago: Planta + NX