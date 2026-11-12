
# Control — LARC Open 2027

## 1. Información general

**Proyecto:** LARC Open 2027  
**Organización:** RoBorregos  
**Área:** Software — Control  
**Responsable principal:** Denis David Cerón Guzmán  
**Colaborador:** Ricardo Flores García  
**Project Manager:** Salette Morales Prieto  

---

## 2. Descripción del área

El área de Control es responsable del desarrollo, mantenimiento y mejora de los sistemas que permiten controlar el movimiento y funcionamiento del robot de LARC Open 2027.

Su propósito es garantizar que el robot pueda ejecutar movimientos de manera precisa y confiable, utilizando correctamente la información proporcionada por los sensores, los algoritmos de control y el sistema de Visión Artificial.

Entre sus principales campos de trabajo se encuentran:

- Control de motores y actuadores.
- Regulación de velocidad, posición y orientación.
- Odometría y estimación del movimiento.
- Lectura y calibración de sensores.
- Implementación y evaluación de algoritmos de control.
- Comunicación entre programas y componentes.
- Integración con Visión Artificial.
- Diagnóstico de problemas de funcionamiento.
- Pruebas y validación del sistema.

### Organización de Software

El equipo de Software se divide en dos especialidades principales:

| Especialidad | Responsable principal | Colaborador |
|---|---|---|
| Visión Artificial | Ricardo Flores García | Denis David Cerón Guzmán |
| Control | Denis David Cerón Guzmán | Ricardo Flores García |
| Integración | Ricardo y Denis | Responsabilidad compartida |

Esta división tiene fines organizacionales y no representa una separación rígida del trabajo.

**Ambos integrantes deberán participar en Visión Artificial y Control**, comprender el funcionamiento general del software y colaborar en las decisiones técnicas.

---

## 3. Responsabilidades generales

### 3.1. Análisis del sistema heredado

El desarrollo de Control deberá partir de la comprensión del sistema utilizado por LARC Open 2026.

Esto implica:

- Revisar el código heredado del equipo anterior.
- Comprender la arquitectura general del software.
- Identificar los algoritmos de control utilizados.
- Analizar el funcionamiento de motores y actuadores.
- Estudiar el sistema de odometría.
- Identificar los sensores y su funcionamiento.
- Revisar la comunicación entre los programas.
- Identificar problemas, limitaciones y funcionalidades existentes.
- Reconocer las soluciones que pueden conservarse o reutilizarse.

Antes de realizar modificaciones importantes, se deberá comprender su funcionamiento y evaluar la necesidad de implementar cambios.

### 3.2. Control de movimiento

El área deberá estudiar y desarrollar las herramientas necesarias para controlar el movimiento del robot.

Sus responsabilidades incluyen:

- Analizar el control de motores.
- Comprender la cinemática del robot.
- Evaluar el control de velocidad y dirección.
- Revisar el control de posición y orientación.
- Implementar o mejorar algoritmos de control cuando sea necesario.
- Evaluar la precisión y estabilidad de los movimientos.
- Identificar errores y proponer soluciones.
- Coordinar con Mecánica las limitaciones físicas del robot.

### 3.3. Sensores y odometría

El sistema deberá utilizar correctamente la información proporcionada por los sensores para estimar su estado y movimiento.

Se deberá trabajar en:

- Identificación de sensores utilizados.
- Lectura y procesamiento de datos.
- Calibración de sensores.
- Identificación de errores y offsets.
- Comprensión del funcionamiento de la odometría.
- Estimación de posición y orientación.
- Evaluación de precisión de las mediciones.
- Investigación de problemas relacionados con el BNO.
- Coordinación con Electrónica para diagnosticar fallas.

### 3.4. Arquitectura y comunicación

El equipo deberá comprender cómo se organizan y comunican los programas del robot.

Esto incluye:

- Estructura general del código.
- Lenguajes de programación.
- Librerías y dependencias.
- Comunicación entre programas.
- Gestión de tareas y procesos.
- Manejo de errores.
- Investigación de FreeRTOS y su aplicación, cuando corresponda.
- Intercambio de información entre Visión y Control.

### 3.5. Investigación y desarrollo

Las propuestas de mejora deberán responder a necesidades identificadas durante el análisis del sistema y las pruebas.

Se deberá:

- Investigar posibles soluciones técnicas.
- Consultar documentación confiable.
- Comparar alternativas.
- Considerar las capacidades del hardware.
- Evaluar ventajas y limitaciones.
- Justificar las modificaciones propuestas.
- Coordinar decisiones que afecten a otras áreas.

### 3.6. Pruebas y validación

El funcionamiento de los sistemas desarrollados deberá comprobarse mediante pruebas.

Se deberán considerar:

- Pruebas de motores y actuadores.
- Pruebas de lectura de sensores.
- Pruebas de calibración.
- Evaluación de odometría.
- Pruebas de precisión y estabilidad.
- Pruebas de comunicación con Visión Artificial.
- Pruebas de integración con Electrónica.
- Pruebas con el robot físico.
- Registro y análisis de resultados.

Las modificaciones deberán validarse antes de integrarse definitivamente al sistema.

---

## 4. Organización de archivos

El área de Software se organizará dentro del repositorio de LARC Open 2027 mediante tres carpetas principales.

```text
Software/
├── Vision/
│   └── README.md
├── Control/
│   └── README.md
└── Integracion/
    └── README.md
```

### Control

Esta carpeta corresponde a la especialidad de Control.

Su README contiene:

- Descripción del área.
- Responsabilidades técnicas.
- Metodología general de trabajo.
- Lineamientos de documentación.
- Coordinación con otras áreas.
- Reglas de seguimiento.
- Responsables del área.

### Visión Artificial

Contiene la información correspondiente al sistema de visión del robot.

**Responsable principal:** Ricardo Flores García.

### Integración

Contiene los lineamientos generales relacionados con la comunicación y funcionamiento conjunto de Visión y Control.

**Responsables:** Ricardo Flores García y Denis David Cerón Guzmán.

### Código fuente

El código del robot deberá mantenerse versionado dentro del repositorio, respetando una estructura acordada por el equipo.

Los README funcionan como documentos de referencia y no sustituyen el código fuente ni el seguimiento mediante Issues.

---

## 5. Documentación y control de versiones

La documentación deberá permitir que los integrantes actuales y futuros comprendan el funcionamiento del sistema y puedan continuar su desarrollo.

### 5.1. Documentación técnica

Se deberá mantener información sobre:

**Arquitectura del sistema**
- Estructura del programa.
- Función de los módulos.
- Flujo de información.
- Relación con otros sistemas.

**Motores, actuadores y sensores**
- Componentes utilizados.
- Especificaciones relevantes.
- Interfaces y protocolos.
- Configuraciones.
- Procedimientos de calibración.

**Algoritmos de control**
- Objetivo de los algoritmos.
- Funcionamiento general.
- Entradas y salidas.
- Parámetros relevantes.
- Limitaciones conocidas.

**Odometría**
- Método de estimación utilizado.
- Sensores involucrados.
- Parámetros y cálculos.
- Errores identificados.
- Métodos de validación.

**Problemas y soluciones**
- Descripción de problemas.
- Posibles causas.
- Soluciones implementadas.
- Resultados de las pruebas.
- Referencias a Issues.

### 5.2. Control de versiones

Para mantener un desarrollo organizado:

- Registrar los cambios mediante Git.
- Utilizar nombres descriptivos en los commits.
- Trabajar en ramas cuando corresponda.
- Evitar modificar código funcional sin comprender sus consecuencias.
- Realizar pruebas antes de integrar cambios.
- Revisar los cambios importantes entre ambos integrantes.
- Mantener actualizado el código del repositorio.
- Documentar modificaciones relevantes.

### 5.3. Evidencia de trabajo

Las actividades técnicas deberán contar con evidencia según corresponda.

Puede incluir:

- Código desarrollado.
- Resultados de pruebas.
- Capturas de pantalla.
- Registros de funcionamiento.
- Diagramas.
- Mediciones.
- Análisis técnico.
- Pull Requests.

La evidencia deberá relacionarse con los Issues correspondientes para facilitar el seguimiento.

---

## 6. Colaboración entre áreas

El desarrollo de Control requiere coordinación constante con las demás áreas del proyecto.

### 6.1. Visión Artificial

**Responsable principal:** Ricardo Flores García.

- Coordinar el intercambio de información entre ambos sistemas.
- Definir las entradas y salidas necesarias.
- Revisar la compatibilidad entre programas.
- Participar en decisiones técnicas compartidas.
- Realizar pruebas de comunicación.
- Identificar y corregir problemas de integración.

Ricardo y Denis deberán comprender ambos sistemas y colaborar en su desarrollo, independientemente de su especialidad principal.

### 6.2. Electrónica

**Responsable:** Bernardo Guerrero Osorio.

- Revisar conexiones de motores y sensores.
- Comprender las características del hardware.
- Verificar protocolos de comunicación.
- Coordinar procedimientos de calibración.
- Investigar problemas relacionados con el BNO.
- Diagnosticar fallas de hardware y software.
- Participar en pruebas de integración.

### 6.3. Mecánica

**Responsable:** Katia Iveth Uribe Briones.

- Comprender la configuración física del robot.
- Identificar limitaciones mecánicas.
- Revisar las características de movimiento.
- Considerar los efectos de las modificaciones mecánicas sobre Control.
- Coordinar pruebas de movimiento.
- Evaluar el comportamiento del robot físico.

### 6.4. Project Manager

**Responsable:** Salette Morales Prieto.

- Coordinar la organización general del proyecto.
- Dar seguimiento a las actividades.
- Facilitar la comunicación entre áreas.
- Identificar dependencias y necesidades.
- Revisar el cumplimiento de compromisos.
- Apoyar en la resolución de problemas organizacionales.
- Mantener el seguimiento general en GitHub Projects.

---

## 7. Seguimiento del área

Las actividades de Control se administrarán mediante GitHub Issues y GitHub Projects.

### 7.1. GitHub Issues

**Categoría:** `software/control`

Los Issues se utilizarán para:

- Asignar actividades técnicas.
- Dar seguimiento a investigaciones.
- Registrar errores.
- Proponer mejoras.
- Documentar problemas.
- Registrar pruebas.
- Solicitar apoyo de otras áreas.

Cada Issue deberá incluir, cuando corresponda:

1. Descripción de la actividad.
2. Objetivo.
3. Responsable o responsables.
4. Fecha de entrega.
5. Criterios de aceptación.
6. Evidencia esperada.
7. Dependencias.

### 7.2. GitHub Projects

El tablero general de LARC Open 2027 permitirá visualizar:

- Actividades pendientes.
- Actividades en desarrollo.
- Actividades en revisión.
- Actividades completadas.
- Responsables.
- Prioridades.
- Fechas de entrega.

### 7.3. Responsabilidades de los integrantes

**Denis — Responsable principal de Control**

- Coordinar el desarrollo técnico de Control.
- Dar seguimiento a las actividades de su especialidad.
- Mantener organizada la información técnica.
- Comunicar avances y problemas.
- Participar en las decisiones técnicas.
- Colaborar en Visión Artificial e Integración.
- Revisar código y participar en pruebas.

**Ricardo — Colaborador en Control**

- Participar en el análisis y desarrollo.
- Apoyar en la revisión de algoritmos.
- Colaborar en pruebas.
- Compartir conocimientos técnicos.
- Coordinar la integración con Visión Artificial.
- Participar en decisiones y revisiones importantes.

### 7.4. Compromisos compartidos

Ambos integrantes deberán:

- Conocer el funcionamiento general del software.
- Participar en Visión y Control.
- Compartir conocimientos.
- Comunicar problemas oportunamente.
- Mantener la documentación organizada.
- Registrar y actualizar sus Issues.
- Colaborar en pruebas de integración.
- Participar en las revisiones técnicas.
- Cumplir los compromisos acordados.

**Importante:** Tener un responsable principal por especialidad permite organizar el seguimiento, pero no significa que las actividades o los conocimientos pertenezcan exclusivamente a una persona.

---

## 8. Un mensaje de tu PM

Holaaaa Denis, jajajaj.

Hermano, desde que te conocí hace como una semana JAJAJAJA, me has parecido una persona muy chill, muy pacífica, o por lo menos quiero pensar que eres así la mayor parte del tiempo jajajaj.

La verdad es que todavía no te conozco tanto, pero algo que sí he podido notar es que eres alguien que escucha muchísimo y que tiene bastante disposición para adaptarse y trabajar con los demás. Y créeme que eso es algo que valoro bastante, porque no siempre es fácil encontrar personas que realmente estén dispuestas a escuchar.

Pero bueno, antes de seguir, que sepas que estas cartas son mi manera de asegurarme de que hayan leído sus README, porque tengo la sospecha de que voy a tener que recordarles que lo hagan JAJAJAJA.

También quería aprovechar este espacio para compartirles un poquito de mi experiencia y darles mi pedacito de sabiduría. Nada de lo que escriba aquí es personal ni significa que piense que vayas a cometer los mismos errores que yo. Simplemente son cosas que he aprendido de lo que me ha tocado vivir y que me hubiera gustado saber antes.

Hay algo que he aprendido trabajando en equipos y que creo que vale muchísimo la pena compartirte.

Muchas veces pensamos que para llevarnos bien con todos tenemos que escuchar, adaptarnos y evitar los desacuerdos. Y aunque esas cosas son importantes, también he aprendido que trabajar en equipo no significa estar siempre de acuerdo ni quedarnos callados cuando pensamos diferente.

A veces, por no querer incomodar a los demás o por mantener un ambiente tranquilo, dejamos pasar ideas, preguntas o comentarios que en realidad podrían aportar muchísimo.

Y créeme que expresar lo que piensas no significa que estés rompiendo la paz del equipo jajajaja. Muchas veces es justamente lo contrario, porque una conversación a tiempo puede evitar problemas mucho más grandes después.

Te comparto esto porque yo misma he tenido que aprender que no siempre es fácil decir lo que pensamos, especialmente cuando estamos rodeados de personas que tienen más experiencia en ciertos temas.

Pero algo que me gustaría que tengas presente es que tus ideas también tienen valor.

No necesitas estar completamente seguro de algo para hacer una pregunta, ni tener la solución perfecta para proponer una idea. A veces las mejores decisiones comienzan precisamente porque alguien se atrevió a cuestionar algo que todos los demás estaban dando por hecho.

Y ahora que vas a estar trabajando tan de cerca con Ricardo, espero que aproveches muchísimo esa oportunidad.

Como él mismo te dijo cuando estábamos hablando, cualquier duda que tengas, pregúntale con toda confianza. Y no solamente a él, también a cualquier otra persona del equipo.

Ricardo tiene muchísimo conocimiento del que puedes aprender, pero eso no significa que tú no tengas cosas que aportarle a él. Al contrario, creo que una de las ventajas más grandes de trabajar juntos es que pueden complementarse, cuestionarse y aprender el uno del otro.

No quiero que sientas que tu papel es solamente escuchar o seguir lo que alguien más propone. También quiero que tengas la confianza de expresar tus ideas, de dar tu opinión y de participar activamente en las decisiones.

Porque trabajar en equipo también significa permitir que los demás te escuchen a ti.

Y algo que espero que nunca se te olvide es que, aunque ahora tienes compañeros que van a depender de ti, tú también puedes depender de ellos.

No tienes que saberlo todo, resolverlo todo ni quedarte con una duda por miedo a preguntar. Están aquí para construir algo juntos, y eso implica aprender a apoyarse mutuamente.

Espero que este equipo sea un espacio donde puedas expresarte con confianza, donde puedas equivocarte, preguntar y proponer sin sentir que tienes que medir cada palabra.

Y si por alguna razón no llega a sentirse así, que espero que no JAJAJAJA, quiero que sepas que siempre puedes acercarte conmigo. Como tu PM me importa que podamos tener esa comunicación y que todos se sientan escuchados.

No te prometo que siempre vayamos a estar de acuerdo, pero sí que voy a estar dispuesta a escucharte y buscar una solución contigo.

Y bueno, ya casi termino mi discurso jajajaj.

Aunque apenas nos estamos conociendo, me da muchísimo gusto que formes parte de LARC Open 2027.

No conozco todo lo que tuviste que hacer para llegar hasta aquí, pero sí sé que entrar al equipo representativo de robótica no es cualquier cosa.

Creo que a veces, cuando empezamos a convivir con personas que consiguieron lo mismo que nosotros, se nos olvida reconocer lo que logramos. De pronto estamos rodeados de gente igual de capaz y empezamos a verlo como algo normal.

Pero que todos tus compañeros hayan conseguido entrar no hace que tu propio logro tenga menos mérito.

Espero que tengas muy presente que ya te ganaste un lugar aquí y que no necesitas demostrar constantemente que mereces estar en el equipo.

Ahora toca aprender, experimentar, conocer a tus compañeros y disfrutar todo lo que viene.

También espero que durante este proyecto puedas encontrar la confianza para intentar cosas nuevas, incluso si al principio no estás completamente seguro de cómo hacerlas. Que te permitas equivocarte, cambiar de opinión y aprender de personas que ven las cosas de manera diferente.

Y sobre todo, que disfrutes la experiencia. Porque al final, más allá de los resultados de la competencia, también están las personas que conoces, los momentos que compartes y todo lo que aprendes durante el camino.

Me da mucho gusto tenerte en el equipo, Denis, y espero que podamos construir algo de lo que todos nos sintamos orgullosos.

Y ahora sí, ya terminé JAJAJAJA.

Sigue siendo esa persona tranquila y abierta a escuchar, pero nunca olvides que tu voz también merece ser escuchada.

Muchísimo éxito, hermano. Espero que este proyecto te deje grandes aprendizajes y muy buenas experiencias.

**Salette Morales Prieto**  
*Project Manager — LARC Open 2027*
