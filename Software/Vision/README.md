
# Visión Artificial — LARC Open 2027

## 1. Información general

**Proyecto:** LARC Open 2027  
**Organización:** RoBorregos  
**Área:** Software — Visión Artificial  
**Responsable principal:** Ricardo Flores García  
**Colaborador:** Denis David Cerón Guzmán  
**Project Manager:** Salette Morales Prieto  

---

## 2. Objetivo general

Comprender, desarrollar, mantener y mejorar el sistema de visión artificial del robot de LARC Open, buscando que sea capaz de interpretar su entorno de manera confiable y proporcionar información útil para la navegación y toma de decisiones.

El desarrollo deberá considerar los requerimientos del reglamento, las características del hardware disponible y la integración con los demás sistemas del robot.

**Visión Artificial forma parte del área de Software**, por lo que deberá mantener una coordinación constante con Control e Integración.

---

## 3. Organización del equipo

| Integrante | Función |
|---|---|
| Ricardo Flores García | Responsable principal de Visión Artificial |
| Denis David Cerón Guzmán | Colaborador en Visión Artificial y responsable principal de Control |

La división entre Visión y Control tiene fines organizacionales y no limita la participación de los integrantes.

Ambos deberán conocer el funcionamiento general del software, colaborar en el desarrollo y participar en las decisiones técnicas.

El responsable principal se encargará de coordinar los avances de su especialidad, mantener organizada la información y comunicar cualquier problema o necesidad al equipo.

---

## 4. Alcance técnico

### 4.1. Procesamiento de imágenes

El sistema de visión deberá contemplar, según las necesidades del robot:

- Captura y procesamiento de imágenes.
- Identificación de elementos relevantes del entorno.
- Detección y reconocimiento de objetos.
- Calibración de cámara.
- Análisis de condiciones de iluminación.
- Evaluación de precisión y rendimiento.
- Optimización del procesamiento de imágenes.

### 4.2. Hardware y software

Se deberán comprender y documentar los componentes y herramientas utilizados para el funcionamiento del sistema.

Esto incluye:

- Cámaras y dispositivos de captura.
- Lenguajes de programación.
- Librerías y dependencias.
- Algoritmos de procesamiento.
- Interfaces y protocolos de comunicación.
- Requerimientos de procesamiento y memoria.

### 4.3. Comunicación con Control

Visión Artificial deberá trabajar de manera coordinada con el sistema de Control para asegurar que la información obtenida pueda utilizarse correctamente.

Se deberá considerar:

- Qué información necesita recibir Control.
- Qué datos proporciona Visión.
- Cómo se realiza la comunicación entre sistemas.
- La frecuencia de actualización de la información.
- El manejo de errores y datos inválidos.
- La compatibilidad entre los programas.

---

## 5. Metodología de trabajo

### 5.1. Comprensión del sistema existente

Antes de implementar modificaciones importantes, se deberá comprender el funcionamiento del código y los componentes existentes.

Esto implica:

- Revisar el código heredado.
- Identificar la estructura general del programa.
- Comprender los algoritmos utilizados.
- Revisar librerías y dependencias.
- Identificar limitaciones y problemas.
- Reconocer las funcionalidades que ya funcionan correctamente.

### 5.2. Investigación y desarrollo

Las propuestas de mejora deberán partir de una necesidad identificada.

Se recomienda:

- Consultar documentación técnica confiable.
- Comparar alternativas de implementación.
- Considerar los recursos disponibles.
- Evaluar ventajas y desventajas.
- Justificar las modificaciones propuestas.
- Consultar con otros integrantes cuando sea necesario.

### 5.3. Pruebas y validación

Las modificaciones deberán evaluarse mediante pruebas que permitan comprobar su funcionamiento.

Se deberán considerar:

- Pruebas individuales de algoritmos.
- Pruebas de captura de imágenes.
- Pruebas de detección y reconocimiento.
- Evaluación de precisión.
- Evaluación de tiempos de procesamiento.
- Pruebas de comunicación con Control.
- Pruebas de integración con el robot físico.

Las pruebas deberán contar con resultados y evidencia que permitan identificar problemas y evaluar mejoras.

---

## 6. Documentación técnica

La documentación de Visión Artificial deberá permitir que cualquier integrante del equipo pueda comprender el funcionamiento del sistema y continuar su desarrollo.

Se deberá mantener información sobre:

### Arquitectura del sistema

- Estructura general del programa.
- Función de los principales módulos.
- Flujo de procesamiento de imágenes.
- Relación con otros sistemas.

### Componentes y herramientas

- Cámara utilizada y sus especificaciones.
- Librerías y dependencias.
- Versiones de software.
- Configuraciones necesarias.
- Requerimientos para ejecutar los programas.

### Algoritmos

- Descripción de los algoritmos utilizados.
- Objetivo de cada algoritmo.
- Entradas y salidas.
- Parámetros relevantes.
- Limitaciones conocidas.

### Problemas y soluciones

- Problemas técnicos identificados.
- Posibles causas.
- Soluciones implementadas.
- Resultados obtenidos.
- Referencias a los Issues correspondientes.

**Nota:** La documentación deberá actualizarse cuando existan cambios técnicos relevantes, evitando duplicar información que ya se encuentre registrada en el código o en GitHub Issues.

---

## 7. Coordinación con otras áreas

### Control

**Responsable principal:** Denis David Cerón Guzmán

- Establecer las necesidades de comunicación entre Visión y Control.
- Definir entradas y salidas del sistema.
- Coordinar modificaciones que afecten a ambos programas.
- Participar en pruebas de integración.
- Identificar problemas de compatibilidad.

### Electrónica

**Responsable:** Bernardo Guerrero Osorio

- Revisar las conexiones y requerimientos de las cámaras.
- Verificar compatibilidad con los componentes electrónicos.
- Analizar problemas relacionados con alimentación y comunicación.
- Coordinar pruebas de hardware.

### Mecánica

**Responsable:** Katia Iveth Uribe Briones

- Definir y revisar la ubicación física de las cámaras.
- Considerar el campo de visión y las posibles obstrucciones.
- Evaluar vibraciones y condiciones que puedan afectar la captura de imágenes.
- Coordinar ajustes mecánicos cuando sean necesarios.

---

## 8. Organización y seguimiento en GitHub

Las actividades de Visión Artificial se administrarán mediante GitHub Issues y GitHub Projects.

**Categoría de seguimiento:** `software/vision`

### GitHub Issues

Los Issues se utilizarán para:

- Asignar actividades.
- Dar seguimiento a investigaciones.
- Registrar errores y problemas.
- Proponer mejoras.
- Documentar solicitudes técnicas.
- Dar seguimiento a pruebas y correcciones.

Cada Issue deberá contar, cuando corresponda, con:

1. Descripción de la actividad.
2. Objetivo.
3. Responsable o responsables.
4. Fecha de entrega.
5. Criterios de aceptación.
6. Evidencia o resultado esperado.
7. Dependencias con otras áreas.

### GitHub Projects

El tablero general de LARC Open 2027 se utilizará para visualizar:

- Actividades pendientes.
- Actividades en desarrollo.
- Actividades en revisión.
- Actividades completadas.
- Responsables y prioridades.
- Fechas y avances.

### Revisión de código

Para mantener la calidad y comprensión del software:

- Documentar los cambios importantes.
- Utilizar nombres descriptivos.
- Evitar modificar código funcional sin comprender sus consecuencias.
- Realizar pruebas antes de integrar cambios.
- Procurar que ambos integrantes revisen y comprendan las modificaciones relevantes.
- Mantener una comunicación constante sobre decisiones técnicas.

---

## 9. Responsabilidades generales

### Responsable principal de Visión — Ricardo

- Coordinar el desarrollo técnico de Visión Artificial.
- Mantener una visión general del funcionamiento del sistema.
- Organizar y dar seguimiento a las actividades de su especialidad.
- Promover la documentación técnica.
- Comunicar problemas, necesidades y avances.
- Coordinar con Denis las actividades compartidas.
- Participar también en el desarrollo de Control e Integración.
- Apoyar en la revisión del código y las pruebas.

### Colaborador — Denis

- Participar en el desarrollo de Visión Artificial.
- Apoyar en la investigación y análisis del sistema.
- Colaborar en la implementación y revisión de algoritmos.
- Participar en pruebas y validación.
- Mantener coordinación entre Visión y Control.
- Compartir conocimientos y participar en las decisiones técnicas.

### Responsabilidades compartidas

- Comprender el funcionamiento general del software.
- Colaborar activamente en ambas especialidades.
- Mantener una comunicación clara.
- Documentar decisiones técnicas relevantes.
- Identificar y comunicar problemas oportunamente.
- Participar en las pruebas de integración.
- Compartir conocimientos y apoyar el aprendizaje mutuo.
- Cumplir los compromisos establecidos en GitHub.

**Importante:** La asignación de responsables busca facilitar la organización y el seguimiento, no establecer una separación rígida de conocimientos o actividades.

---

## 10. Mensaje de la PM — Para Ricardo

Holaaa Ricardo, jajaja.

Primero que nada, que sepas que estas cartas son mi manera de asegurarme de que hayan leído sus README, porque tengo la ligera sospecha de que voy a tener que recordarles que lo hagan jajajaj.

Pero bueno, el chiste es que también quería aprovechar este espacio para motivarlos un poquito y compartirles mi pedacito de sabiduría. Nada de lo que escriba aquí es personal ni significa que piense que vayan a cometer los mismos errores que yo. Simplemente son cosas que he aprendido por lo que me ha tocado vivir y que me hubiera gustado entender antes.

Primero quiero decirte que me pareces una persona muy capaz. Tienes muchísimo conocimiento técnico y creo que eso hace que naturalmente las personas te vean como un líder en ese ámbito. Algo que admiro bastante de ti es que, a pesar de todo lo que sabes, sigues siendo alguien muy humilde, y creo que eso vale muchísimo.

La verdad es que todavía no te conozco tanto personalmente, pero sí quería compartirte algo que aprendí el año pasado.

Uno de mis problemas más grandes fue la falta de comunicación. Muchas veces, cuando algo me molestaba o no estaba funcionando, prefería guardármelo hasta que llegaba un punto en el que simplemente explotaba jajaja. Y algo que aprendí es que muchas veces dejamos crecer problemas que pudieron haberse resuelto con una conversación mucho antes.

No te digo esto porque crea que vayas a cometer el mismo error, sino porque ahora que el equipo te reconoce como alguien con bastante conocimiento técnico, creo que también viene una responsabilidad importante. Ser un líder no solamente es saber mucho o tener las respuestas, también es saber escuchar, tener flexibilidad y entender que no siempre vamos a estar de acuerdo con todos.

Y créeme que escuchar a los demás, incluso cuando tienen menos experiencia que tú, puede enseñarte cosas que no esperabas.

También quiero que sepas que no tienes que cargar con todo ni sentir que tienes que resolver cada problema por tu cuenta. Si en algún momento algo te molesta, no estás de acuerdo con alguna decisión o simplemente necesitas hablar de alguna situación del equipo, puedes acercarte conmigo con toda confianza. Prefiero que podamos hablar las cosas a tiempo, aunque sea una conversación incómoda, a que se conviertan en algo más grande.




**Estoy muy orgullosa de que hayas llegado hasta aquí.** No sé exactamente todo lo que te haya tocado vivir o lo que hayas tenido que hacer para entrar al equipo representativo de robótica, pero el simple hecho de haberlo conseguido ya es un mérito enorme.

Creo que a veces, cuando estamos rodeados de personas que han logrado lo mismo que nosotros, empezamos a normalizarlo. Vemos a todos nuestros compañeros dentro del equipo y se nos olvida que estar aquí no es cualquier cosa. Que detrás de cada persona hubo esfuerzo, tiempo, aprendizajes y probablemente más de un momento complicado.

Y no quiero que se te olvide eso. Que hoy estés aquí significa algo, y es un logro que merece ser reconocido, incluso cuando parece que todos a tu alrededor ya lo consiguieron.

Espero que durante este proyecto no solamente puedas demostrar todo lo que sabes, sino también aprender muchísimo, equivocarte, mejorar y disfrutar la experiencia. No tienes que saberlo todo desde el principio, ni demostrar constantemente por qué mereces estar aquí. Ya te ganaste tu lugar, y ahora toca aprovecharlo.

Me da mucho gusto tenerte en el equipo y espero que podamos construir algo de lo que todos nos sintamos orgullosos.

Y ahora sí, ya acabé jajajaj. Mucho éxito, Ricardo, y gracias por formar parte de LARC Open 2027.

**Salette Morales Prieto**  
Project Manager — LARC Open 2027
