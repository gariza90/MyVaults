# Historias de Usuario
---

Una Historia de Usuario está totalmente centrada en el [[Stakeholders|usuario]], y no en el producto o la organización. Éstas están totalmente alineadas con la expectativa del [[Stakeholders|usuario]], sin tener en cuenta capacidades o restricciones del producto.

Es la representación de un requerimiento del producto, lo que en los métodos tradicionales seria la realización de casos de uso.

Son pequeños incrementos de funcionalidad que permite aportar valor agregado al [[Stakeholders|cliente]].

Son elementos expresados en el sentido del valor que dan al [[Stakeholders|usuario final]], son independientes entre sí y fomentan una conversación sobre el valor para los usuarios.

Es la unidad más granular de requerimientos expresados por el [[Product Owner|Product Owner]].
- Recopila información básica acerca de los requerimientos.
- Registra los requerimientos a un alto nivel.
- Ayuda a desarrollar [[Estimación de Historias de Usuario|estimaciones]] de alto nivel para el trabajo necesario.
- Define las [[Criterios de Aceptación|pruebas de aceptación]] para validar el cumplimiento exitoso.

Actúa como un acuerdo entre [[Stakeholders|clientes]] y el [[Scrum Team|equipo]] para discutir requerimientos detallados durante un [[Sprint]].

### Composición
Se compone de (3C's):
- **Tarjeta (Card)**: Una descripción escrita de la Historia de Usuario de una manera entendible para el [[Scrum Team|equipo]], usada como recordatorio y para planificar. (Debe ser breve). No debe ser detallada. Refleja los elementos más importantes de la Historia de Usuario. Expresa el valor que se quiere conseguir desde el punto de vista del [[Stakeholders|usuario]]. Expresar un Historia de Usuario desde el punto de vista del [[Development Team|desarrollador]] o desde la organización es una mala práctica que refleja la incapacidad de pensar en el valor para el [[Stakeholders|usuario final]].
- **Conversación**: Conversaciones acerca de la Historia de Usuario que sirven para aclarar los detalles. Hay que saber responder a cuestiones sobre el valor y sobre el resultado esperado de la implementación. Esta conversación puede suceder en cualquier momento; es habitual que se produzca durante el [[Product Backlog Refinement|Refinamiento del Backlog]] o el [[Sprint Planning|Sprint Planning]].
- **Confirmación**: La confirmación es un acuerdo que refleja que todas las personas implicadas, [[Product Owner|Product Owner]] y el [[Development Team|equipo de desarrollo]], [[Entendimiento Común|entienden]] cuales son los elementos, valor y el resultado esperado de la Historia de Usuario. Es un [[Criterios de Aceptación|criterio de aceptación]] (idealmente automatizado) que permita determinar cuándo la historia ha sido completada.

Generalmente el [[Product Owner|Product Owner]] le asigna una [[Priorización de Requerimientos|prioridad]] y el [[Development Team|equipo de desarrollo]] le asigna un [[Estimación de Historias de Usuario|tamaño estimado]].

Una vez [[Estimación de Historias de Usuario|estimadas]] y [[Priorización de Requerimientos|priorizadas]] pasan a formar parte del [[Product Backlog|Product Backlog]].

### Contenido
Información contenida en una Historia de Usuario:
- Identificador de Historia: Generalmente un número y un nombre.
- Descripción breve de la función o característica.
- Tipo de Historia: Requisito del [[Stakeholders|Cliente]] o Requisito técnico del [[Development Team|Equipo de Desarrollo]].
- Esfuerzo estimado: Valor [[Estimación de Historias de Usuario|estimado]] en [[05. Planning Poker|puntos]] dado por el [[Development Team|Equipo de Desarrollo]].
- Valor estimado por el Cliente.
- Requerimientos inciertos, llamado el factor de exploración.
- Dependencias de la Historia de otras Historias de Usuario.
- Pruebas de aceptación: Indica como la Historia de Usuario debería ser [[Criterios de Aceptación|probada y aceptada]].

Múltiples Historias de Usuario podrían requerirse para completar una función.

### Características
Las caracteristicas de una buena Historia de Usuario deben de cubrir el acronimo en ingles **INVEST**
- **I**ndependientes: Las Historias de Usuario deben ser independientes unas de otras, y entregables como una unidad, si existen dos historias dependientes, se recomienda unirlas pero considerar dividirlas de tal manera que pudieran generarse más Historias de Usuario que no dependan unas de otras.
- **N**egociables: Debe haber lugar para la negociación en cuanto a la naturaleza de la implementación. Se debe discutir con el [[Stakeholders|cliente]] el alcance de cada Historias de Usuario, y deberá quedar especificado en la validación de cada una.    
- **V**aloradas por los [[Stakeholders|clientes]] (valorables): El [[Stakeholders|cliente]] debera determinar el valor que cada una de ellas representa. El valor que el [[Stakeholders|cliente]] puede determinar para una Historia de Usuario no es el mismo que le podría dar un [[Development Team|desarrollador]], por lo cual, debera existir una charla para llegar a un acuerdo y terminar el sistema a tiempo. Pero sin olvidar que lo mas importante es la opinion del [[Stakeholders|cliente]].
- **E**stimables: Cada Historia de Usuario debera ser [[Estimación de Historias de Usuario|estimada]] según la complejidad y la experiencia de los [[Development Team|desarrolladores]], al finalizar, la suma de la [[Estimación de Historias de Usuario|estimación]] de cada una determinara el total de tiempo de desarrollo del sistema.
- Pequeña**S**: Debera evitarse tener Historias de Usuario largas o grandes ya que esto dificulta determinar la [[Estimación de Historias de Usuario|estimación]] y su ejecución durante un [[Sprint]].    
- Verificables/comprobables/evaluables (**T**est): Ya que las Historias de Usuario son requerimientos funcionales, deben ser posibles examinarlas, probarlas y evaluarlas para comprobar la exactitud basadose en los [[Criterios de Aceptación]] previamente suministrados.

### Redacción
A continuación se describirá y mostrará como redactar una Historia de Usuario.

**Yo como** *usuario/rol*, **quiero/necesito/me gustaría** *función/requerimiento* **para/de esa manera** *descripción del porque/la razón del requerimiento*

**Dado que** *contexto* **y/o** *más contexto*, **cuando** *evento*, **entonces** *resultado* **y/o** *más resultados*.

**Ejemplos:**

**Yo como** *socio tecnológico* **quiero** *conectarme a la plataforma* **para** *dar de alta los cursos a través de una API*.

**Dado que** *que el saldo de la cuenta es negativo* **y** *no hay depósitos directos programados*, (**cuando**) *el día en que el titular de la cuenta intenta retirar dinero*, **entonces** *el banco negará la petición* **y** *enviará alerta al titular*.

Al escribir Historias de Usuario imagina todos los posibles escenarios.

### Separando las Historías de Usuario
- Una Historia de Usuario debería ser corta (no más de 40 horas de trabajo).
- Mantener cortas las Historias de Usuario permite al [[Development Team|equipo]] construir de forma creciente, obteniendo verificación a lo largo del camino.
- Requiere un esfuerzo considerable de parte del [[Product Owner|Product Owner]] el escribir requerimientos a ese nivel de granularidad.

Separar las Historias de Usuario es basándose en el marco general, por ejemplo:
- **Investigación vs acción (Research vs action)**: Si la Historia de Usuario es compleja invierte tiempo del [[Timeboxing|periodo del bloque de tiempo]] en investigación antes de pasar a la siguiente Historia de Usuario.
- **Espiga vs implementación (Spike vs implementation)**: Incluso si el enfoque es claro, a veces la factibilidad necesita ser establecida y el equipo necesita familiarizarse para ser capaz de estimar con precisión y llevar a cabo el trabajo. Experimenta un poco para obtener un mejor entendimiento antes de implementar.
- **Corrientes principales vs corrientes alternas (Main flow vs underneath flow)**: Tiene sentido que construyas la corriente lógica principal primero, así que, haz que sea una Historia de Usuario separada y luego toma los caminos alternos.
- **Comprar vs construir (Buy vs build)**: Invierte tiempo para saber si lo que necesitas ya existe y puede comprarse.

Separar las Historias de Usuario basándose en la experiencia del usuario, por ejemplo:
- **Lote vs en línea (Batch vs Online)**: Manten lejos las interacciones del usuario por algún tiempo, implementa un sistema de lotes primero, luego colócalo en línea.
- **Usuario único vs multiusuario (Single User vs Multi User)**: Trabaja primero en un sistema de usuario único y luego ocúpate de las complicaciones de manejar usuarios múltiples.
- **API vs Interfaz de Usuario (API Only vs User Interfase)**: Construye la interfaz de usuario elegante después, primero ocúpate de la interfaz programática.
- **Interfaz genérica vs interfaz personalizada (Generic UI vs custom UI)**: Primero usa los componentes disponibles para construir algo de manera rápida, luego trabaja en la personalización de la interfaz.

### Épicas o Epopeyas
Macro Historias de Usuario.

Es una forma de agrupar Historias de Usuario basado en objetivos de alto nivel o simplemente en agregar o agrupar un gran número de sub Historias y combinarlas en una gran Historia de Usuario.

---

## Referencias
[Historias de Usuario - jmbeas.es](https://blog.jmbeas.es/2011/05/23/historias-de-usuario-2/)
[Historias de Usuario - gitbooks.io](https://mayra13.gitbooks.io/scrum-master/content/historiasdeusuario.html)
[Scrum no necesita planning poker ni historias de usuario - jeronimopalacios.com](https://jeronimopalacios.com/agile/scrum-no-necesita-planing-poquer-historias-usuario/)
[Los elementos de una buena historia de usuario - jeronimopalacios.com](https://jeronimopalacios.com/product-delivery/los-elementos-una-buena-historia-de-usuario/)