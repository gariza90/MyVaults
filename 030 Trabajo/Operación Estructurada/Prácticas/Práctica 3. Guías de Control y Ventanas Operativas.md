# HSE-G-048 Guía de la Práctica de Guías de Control, Ventanas Operativas de Integridad y Alarmas en las Áreas Operativas de Ecopetrol S.A.
Establece:
- Lineamientos para la estandarización de la definición, implementación y gestión de las guías de control, ventanas operativas de integridad y alarmas, en todas las áreas operativas de Ecopetrol S.A.
- Responsabilidades de los diferentes involucrados en cada una de la las etapas de implementación para garantizar un adecuado seguimiento y control de la operación.

## Alcance
- De aplicación en todas las áreas de operaciones directas y/o contratadas (incluyendo subsuelo) de Ecopetrol S.A.
- De ejecución diaria por parte de los operadores, técnicos, supervisores, recorredores y/o todos aquellos cargos específicos que sean responsables de la confiabilidad e integridad de las plantas, sistemas y equipos.

## Conceptos
### Punto crítico de control - PCC
Ver [[Glosario#Punto crítico de control|Punto crítico de control]]

### Guia de control - GC
Ver [[Glosario#Guía de control|Guúa de control]]

### Ventana operativa de integridad - VOI
Ver [[Glosario#Ventana operativa de integridad|Ventana operativa de integridad]]

### Alarma
Ver [[Glosario#Alarma|Alarma]]

## Condiciones
La implementación de la practica asegura:
- El cumplimiento de los estándares de diseño de los activos.
- Los criterios e indicadores de confiabilidad e integridad.
- El monitoreo y optimización del desempeño del proceso operativo.
- El logro de los objetivos operacionales y las necesidades del negocio.

Los equipos de trabajo de cada unidad o instalación definirán:
- Los límites de las ventanas operativas de integridad de los equipos.
- Los límites de las ventanas operativas adicionales en función de los mecanismos de falla o de degradación presentes en cada sistema o unidad.
- La documentación de las ventanas operativas, en cuanto a:
	- Valores límite.
	- Acciones requeridas por parte del operador.
	- Consecuencias o impactos generados frente a la desviación.
- La divulgación a todo el personal involucrado e interesado.

Lo anterior hace parte del paquete de información de tecnología de procesos y debe estar disponible en un sitio de acceso público para que sea consultada por cualquier persona de la unidad o instalación.

## Lineamientos
- Las ventanas operativas de integridad y/o guías de control se definen los puntos críticos de control, lo cuales pueden estar relacionados con diferentes áreas de desempeño (HSE, Integridad, Eficiencia, Rentabilidad, Confiabilidad, Calidad, etc) y pueden ser:
	- **Variables de proceso** (temperatura, presión, flujo, pH, concentración, etc).
	- **Aspectos de calidad del producto** (calidad de agua de inyección, %BSW, % azufre, sodio, etc).
	- **Condiciones de los equipos** (vibración, velocidad, temperartura de pared, temperatura de lubricante, % de carga, % de apertura, voltaje, corriente, etc).
- Típicamente todos los puntos críticos de control deben tener guía de control alta y/o guía de control baja.
- Algunos puntos críticos de control que no afectan la integridad, tendrán definidos guías de control y no requieren definición de ventanas operativas de integridad.
- Un punto crítico de control al que se le definan ventanas operativas de integridad, pueden tener límite de alta, de baja o ambas, dependiendo de las necesidades y criticidad del proceso. Si el punto crítico de control tiene definidas ventanas operativas de integridad por alta y baja (crítica y estándar), debe tener definidas las guías de control respectivas.
- La definición de los puntos críticos (variables claves) se hacen analizando integralmente cada equipo y sus sistemas auxiliares y todos aquellos equipos aguas arriba o aguas abajo que pueda llegar a afectar su integridad.
- Las ventanas operativas de integridad se definen sobre los puntos críticos o variables de control de mayor impacto o consecuencia. Las guías de control se definen sobre los puntos críticos o variables de control que inciden o afectan los valores de las ventanas operativas de integridad.
- Las ventanas operativas de integridad son definidas para los puntos críticos o variables de control, para las demás variables asociadas que inciden sobre el efecto o la consecuencia de sobrepasar las ventanas, el monitoreo se establece con la definición de las guías de control.

- Existen dos zonas de operación que se delimitan con la definición de las guías de control y ventanas operativas de integridad.
	- **Zona de guías de control**: Es la zona óptima de operación, donde el proceso es operado de forma estable, confiable y rentable, y está delimitado por los valores definidos para las guías de control.
	- **Zona de ventanas operativas de integridad**: Establece los límites para las variables de procesos que pueden afectar la integridad de los equipos, sistemas, plantas, estaciones y facilidades, si la operación del proceso se desvía de los límites establecidos.

- Entre los límites de las guías de control y las ventanas operativas de integridad, se deberá configurar la respectiva alarma, de forma tal, que la misma sirva como una medida de control que permita tomar acciones oportunamente antes de que la variable alcance y sobrepase la ventana operativa de integridad.
- El proceso de definición de las guías de control y las ventanas operativas de integridad se deberá realizar a través de una revisión integral, para asegurar la correcta definición de sus límites y/o alarmas. Cada alarma debe tener una justificación y una respuesta o acción específica del operador.
- Para la definición del tipo de alarma y su configuración de la prioridad, se deberá aplicar la política de alarmas existentes en cada unidad o instalación, asegurándose en cualquier caso, que la definición de las guías de control, las ventanas operativas de integridad y las alarmas estén correctamente alineadas. %% Listado de alarmas configuradas en el DeltaV%%
- Durante el proceso de definición de guías de control y ventanas operativas de integridad es requerido que se realice la definición de las alarmas entre guía de control y ventana estándar, y, entre ventana estándar y ventana crítica. %%Alarmas de bajo, bajo-bajo, alto y alto-alto%%

## Proceso de definición
### Equipo multidisciplinario
Se debe realizar un taller conformado por un equipo multidisciplinario liderado preferiblemente por el ingeniero de proceso del área o el ingeniero de la especialidad más afín con la naturaleza del proceso, y contar con la participación de las demás especialidades que brindan soporte (rotativo, estático, electrónico, eléctrico, sistema de levantamiento artificial ALS, entre otros) y de representantes de la operación con amplia experiencia (técnicos, recorredores o supervisores), que puedan evaluar cada variable de la operación y establecer mediante el análisis de riesgos y consecuencias de los puntos críticos de control de cada área operativa.

Si una instalación tiene unidades o sistemas similares, se deberá realizar un taller conjunto de todas las áreas o unidades similares, que asegure que, la definición de las guías de control y las ventanas operativas de integridad y alarmas, guarden consistencia en cuanto al tipo de análisis realizado y en especial a los criterios utilizados para el desarrollo del taller. Esta sesión asegurará que los negocios estandaricen la filosofía y esquemas operacionales de sus instalaciones. %%Verificar si en las diferentes estaciones existen sistemas similares y evaluar la viabilidad de lo descrito anteriormente.%%

### Entradas requeridas
- Histórico de desempeño de todas la variables de proceso de las unidades o áreas productivas por lo menos de un año completo de operación (si se dispone de un periodo mayor, mejor) y que incluya diferentes escenarios operativos, de manera que se puedan identificar las variaciones típicas bajo diferentes escenarios. Se deberá analizar la trazabilidad y consistencia de la información para los diferentes escenarios de operación, que permita una selección de los rangos óptimos de operación.
- Diagramas grandes de control, PFD, P&ID, piping class, plot plan.
- Manuales de operación y diseño de las plantas.
- Filosofía de operación y control.
- Modelos de simulación.
- Estudios de RCM (mantenimiento centrado en la confiabilidad).
- Estudios de FFS (Fitness For Service - Aptitud Para el Servicio).
- Taller PHA - ARP (Process Hazzard Analysis - Análisis de Riesgo de Proceso).
- Listado de equipos críticos por plantas e instalaciones.
- Herramienta para el análisis de riesgos (Matriz RAM).
- Los modos de falla establecidos en el estudio RBI (Inspección Basada en Riesgo - Lazos de Corrosión), en las áreas que aún no se tengan, se debe contar con:
	- Datos operacionales históricos, registros de mantenimiento e inspección.
	- Datos de calidad y datos de laboratorio.
	- Datos de metalurgia y corrosión.
	- Prácticas recomendadas (propias de Ecopetrol y de la industria en general).
	- Herramientas de modelamiento de proceso y corrosión.
- Documentos de apoyo para la definición de guías de control, ventanas operativas de integridad y alarmas (si existen). Teniendo en cuenta que cada negocio tiene particularidades muy especiales, es adecuado que cada uno elabore los documentos específicos propios de referencia que requiera en el tema.

### Procedimiento
#### Actividades
1. Conformar el equipo de trabajo interdisciplinario responsable de la definición.
2. Asegurar la disponibilidad de la información relacionada como [[Práctica 3. Guías de Control y Ventanas Operativas#Entradas requeridas]].
3. Definir o validar los puntos críticos de control del área operativa, es decir, las variables a las que se les va a definir los límites de las guías de control, ventanas operativas de integridad y alarmas. Si son variables que afectan la integridad, para ello se debe realizar lo siguiente:
	- Definir el diagrama grande de control del proceso (DGC) o documento similar, las secciones del área operativa sobre las que se hará la definición.
	- Identificar en cada sección el orden en que se revisarán los equipos.
	- Identificar cuáles son los equipos críticos y establecer los puntos críticos de control para cada sección de la planta o área y los circuitos asociados. Aplicar los siguientes criterios para determinar los puntos críticos del área.
		- Analizar la criticidad desde el punto de vista ambiental, económico, de seguridad y de proceso.
		- Revisar los equipos del área que pueden generar parada de planta, de un bombeo, una parada de una estación o batería.
		- Revisar la relación de dependencia de equipos críticos entre diferentes secciones del área operativa.
		- Determinar los puntos críticos de control de acuerdo a la prioridad de la operación.
		- Racionalizar el número de puntos críticos de control. Se recomienda que el número sea determinado con juicio de expertos.
4. Determinar la criticidad de cada punto crítico de control, utilizando la herramienta RAM.
5. Definir la frecuencia de control permanente para el caso de los valores monitoreados en DCS o sistemas en línea, por turno, semanal, mensual u otro en especial, de acuerdo con la criticidad de la variable y de la disponibilidad de la información.
6. Establecer los límites de los puntos críticos de control con criterios técnicos, teniendo en cuenta:
	- Guías de control operativas (límites alto y bajo), se define con base en los puntos de mayor eficiencia, utilizando entre otros, los históricos de desempeño de la unidad, estación, pozo, etc.
	- Ventanas operativas de integridad (ventana operativa de integridad estándar y crítica), se define con base en lo establecido por el diseño para asegurar la integridad de los activos.
	- Alarmas (limites altos, bajos o ambos), se define con base en lo establecido por el diseño para asegurar la integridad de los activos.
7. Para establecer el incumplimiento de una guías de control, los criterios recomendados son los siguientes, sin embargo, se pueden tener otros de acuerdo con la variable específica.

|Concepto|Definición|
|----------|----------|
|Tiempo acumulado|Si la suma de los tiempos que la variable ha estado por fuera de la guía de control, es mayor o igual a un tiempo establecido, se generará una no conformidad|
|Tiempo continuo|Si el tiempo continuo que estuvo la variable por fuera de la guías de control, sobrepasa un valor establecido, se generará una no conformidad.|
|Número de veces|Si el número de veces que la variable está por fuera de la guía de control, es mayor o igual a un valor definido, se generará una no conformidad.|

8. Toda violación de una ventana operativa de integridad crítica y/o estándar genera una alerta y un indicador de nivel III de seguridad de procesos según lo describe el API 754; si se materializa una pérdida de contención, inmediatamente es un incidente de seguridad de procesos.
9. Registrar la información de las ventanas operativas de integridad y guías de control en el formato establecido [[HSE-F-134 Formato para el registro de guías de control y ventanas operativas de integridad para áreas operativas de Ecopetrol S.A.]].

## Roles y responsabilidades
### Jefes de área, Coordinadores o Responsable del área operativa
- Responsable directo de que el área cuente con una adecuada definición de las ventanas operativas de integridad y guías de control.
- Garantizar la divulgación de las ventanas operativas de integridad y guías de control en su área.
- Asegurar el cumplimiento de las ventanas operativas de integridad y guías de control en su área.
- Suministrar la formación necesaria a todos los operadores en el proceso de manera que se tenga total entendimiento de los riesgos e impactos asociados a una inadecuada gestión de dichos parámetros.
- Realizar de manera sistemática el seguimiento al cumplimiento de las guías de control, ventanas operativas de integridad y alarmas.
- Responder por el cumplimiento del plan de sostenibilidad de las guías de control, ventanas operativas de integridad y alarmas.

### Supervisores
- Asegurar que durante el turno a su cargo se identifiquen las desviaciones de las guías de control y las ventanas operativas por parte del equipo operativo de la planta que lidera.
- Asegurar que se realicen los análisis de causa raíz que se requieran, la identificación de las acciones de mejora y que se implementen en campo de manera oportuna.
- Identificar necesidades de ajuste en las guías de control y/o ventanas operativas de integridad.
- Gestionar el apoyo de las áreas de soporte para garantizar los resultados del área.
- Acompañar la sesión semanal de seguimiento a los resultados del cumplimiento de ventanas operativas de integridad y guías de control.
- Apoyar la ejecución del plan de sostenibilidad que se define y gestiona en este escenario y la formación del equipo de operaciones en este tema.

### Técnicos, Operadores, Recorredores
- Identificar las desviaciones de las guías de control y de las ventanas operativas de integridad de manera oportuna, a través del análisis operacional.
- Evaluar el desempeño de la unidad, y ejecutar las acciones que se requieran para normalizar o mejorar la condición.
- Asegurar la documentación en su turno, las acciones desarrolladas para cerrar las brechas de las violaciones a guías de control, ventanas operativas y alarmas generadas.
- Proponer mejoras que permitan optimizar la operación a partir del seguimiento de estos parámetros.

### Ingenieros de soporte (procesos)
- Responsable de la aplicación de esta práctica en su área.
- Velar por la veracidad de la información y de los límites establecidos para las ventanas operativas de integridad (crítica y estándar) y las guías de control de su área.
- Liderar los talleres de definición y/o revisión de las ventanas operativas de integridad y las guías de control de su área.
- Realizar ajustes en los valores definidos retando la calidad de los análisis que soporten dichas decisiones, contando con el apoyo de los demás especialidades (eléctrico, electrónico, rotativo, estático y civil).
- Realizar permanentemente el análisis de todas las desviaciones a los límites de integridad que se presenten, identificando las causas raíz.
- Validar las causas raíz identificadas por los operadores a las desviaciones.
- Establecer la estrategia de prevención para evitar desviaciones similares futuras.
- Establecer las medidas de mitigación que sean necesarias para reducir el impacto de las desviaciones que se presenten.
- Ajustar frecuencias de inspección y monitoreo.
- Definir acciones de restitución de una condición afectada.
- Realizar la divulgación de cualquier cambio.
- Realizar el entrenamiento del grupo de operaciones.
- Acompañar el análisis operacional diario y la sesión semanal de seguimiento al cumplimiento de las guías de control, ventanas operativas de integridad y alarmas.
- Contribuir con su análisis en la solución de las desviaciones que el operador no pueda corregir directamente en el turno.

## Seguimiento
Monitoreo permanente de la operación (guías de control, ventanas operativas de integridad y las alarmas de los puntos críticos definidas), por parte de los operadores, supervisores, recorredores, facilitadores e ingenieros de soporte, a través de:
- Las rondas estructuradas.
- En los sistemas de control SCADA.
- En los sistemas de monitoreo en línea.

#### Actividades
La revisión y el seguimiento debe realizarse para todos los escenarios de operación posibles: Arrancadas, paradas, operación normal y emergencias.

- Realizar análisis de eventos en los que se presenten incumplimientos de las guías de control, alarmas y ventanas operativas para establecer las acciones de mitigación de los riesgos y normalizar la condición operacional.
- Registrar los incumplimientos en los sistemas de información establecidos.
- Configurar la herramienta para realizar el seguimiento al cumplimiento de guías de control, ventanas operativas de integridad y alarmas, para ello se debe:
	- Definir la herramienta en donde se almacenará la información (sistemas informáticos, papel, etc).
	- Acordar con el área de informática, la configuración de la herramienta en el sistema definido por cada área, con la información consignada en [[HSE-F-134 Formato para el registro de guías de control y ventanas operativas de integridad para áreas operativas de Ecopetrol S.A.]], de tal manera que permita la identificación de desviaciones con respecto a las guías de control y las ventanas operativas de integridad.
	- Realizar pruebas del sistema y asegurar la generación de los reportes de las violaciones a las guías de control y ventanas operativas.
- Realizar la formación del equipo de operaciones en el manejo de la herramienta con el apoyo del área de informática y el líder de operación estructurada del área.
- Oficializar por parte del jefe de área las ventanas operativas de integridad y guías de control para su divulgación dentro de todo el equipo de operaciones.
- Poner en productivo el sistema de seguimiento para el control de la operación. Es clave tener en cuenta los roles y responsabilidades de cada uno de los representantes del área.

En el formato [[HSE-F-135 Lista de verificación para la definición de ventanas operativas de integridad, guías de control y alarmas en las áreas operativas de Ecopetrol S.A.]], se presenta una lista de verificación detallada de los pasos anteriormente descritos para la definición de las mismas.

## Gestión
En todas las áreas debe tener una sesión semanal dirigida por el líder operativo, en la que se revisarán las violaciones a las guías de control, ventanas operativas de integridad y alarmas generadas, las acciones definidas y la efectividad de las mismas, de manera que se garantice que se actúe oportunamente frente a estas condiciones, se proteja la integridad.

En esta reunión debe participar siempre el ingeniero de proceso y lo acompañarán los ingenieros de las demás especialidades a demanda. Cada área de acuerdo a sus particularidades establecerá el esquema más apropiado para asegurar dicho acompañamiento.

De esta sesión se debe obtener un plan de sostenibilidad de guías de control, alarmas y ventanas operativas, que debe tener el lsitado de las variables cuyos límites no se están cumpliendo, los resultados de los análisis, el plan de mejora y el avance del mismo.

Para realizar el seguimiento de acuerdo al nivel de madurez del proceso se recomiendan los siguientes indicadores que serán detallados en la hoja de vida:
- Porcentaje de cumplimiento de ventanas operativas de integridad.
- Porcentaje de cumplimiento de guías de control.
- Porcentaje de cumplimiento de alarmas.
- Porcentaje de documentación de no conformidades y alertas generados (violación a ventanas operativas de integridad, guías de control y alarmas).

Lo anterior contribuye en los siguientes indicadores de operación estructurada.
- Índice de efectividad de la operación estructurada.

## Actualización
Las ventanas operativas de integridad, alarmas y las guías de control deben ser documentos controlados y deben ser parte del sistema de calidad de las áreas operativas de Ecopetrol S.A. La copia controlada de las ventanas operativas de integridad y guías de control tiene que ser visible y accesible para el personal operativo. Si es posible se deben publicar en un sitio de la intranet local.

Todo cambio a las guías de control, ventanas operativas de integridad y alarmas, requiere la aplicación del procedimiento de control de cambios a la infraestructura. %%Buscar la existencia de este procedimiento en P8.%%

El cambio en los parámetros de las guías de control requiere un manejo del cambio bajo la autorización de la autoridad técnica definida y el líder operativo que permita asegurar la trazabilidad del ajuste realizado, la cuasa y el análisis técnico. %%Quiénes serían la autoridad técnica y el líder operativo?%%

## Nivel de implementación
- Realizar autoevaluaciones por parte de la línea operativa con una frecuencia mensual para las áreas que se encuentren en un proceso de instalación de la práctica.
- Realizar evaluaciones cruzadas por parte de los coordinadores o jefes de departamento de acuerdo a lo establecido en los controles de los riesgos del proceso de operación estructurada.
- Aplicar formato [[HSE-F-077 Instrumento de evaluaciones operación estructurada]].
- Generar planes de acción de cierre de brechas, resultado de las evaluaciones, que deberán ser implementadas por cada uno de los responsables de las áreas operativas.

## Referencias
- API RP 584 (2014) Integrity Operating Windows.
- GRB-CEL-I-001 Instructivo para la implementación de la política de alarmas.
- RFN-P-022 Gestión de alarmas.