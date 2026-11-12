
# Control — LARC Open 2027

## Información general

**Proyecto:** LARC Open 2027  
**Organización:** RoBorregos  
**Área:** Software — Control  
**Responsable:** Denis David Cerón Guzmán  
**Colaborador:** Ricardo Flores García  
**Project Manager:** Salette Morales Prieto  
**Periodo:** 2026–2027

---

## 1. Descripción del área

El área de Control es responsable del desarrollo, mantenimiento, integración y validación de los sistemas que permiten controlar el movimiento y funcionamiento del robot de LARC Open.

Su trabajo comprende el control de motores y actuadores, la odometría, el procesamiento de información de sensores, los algoritmos de control y la comunicación entre los programas del robot.

El objetivo es desarrollar un sistema de control preciso, confiable y compatible con los componentes mecánicos, electrónicos y de visión artificial del robot, aprovechando los desarrollos de generaciones anteriores.

Control forma parte del área de Software, integrada por Denis David Cerón Guzmán y Ricardo Flores García.

Aunque Denis será el responsable principal de Control y Ricardo de Visión Artificial, ambos participarán en el desarrollo de las dos especialidades y en su integración.

## 2. Responsabilidades generales

- Analizar el código y los sistemas de control existentes.
- Estudiar el funcionamiento de motores y actuadores.
- Comprender y desarrollar algoritmos de control.
- Revisar los sistemas de odometría y estimación de movimiento.
- Analizar la lectura y calibración de sensores.
- Investigar problemas relacionados con errores y offsets de sensores.
- Revisar la arquitectura y comunicación entre programas.
- Evaluar el funcionamiento y aplicación de FreeRTOS, cuando corresponda.
- Investigar posibles mejoras en precisión, estabilidad y respuesta del robot.
- Coordinar con Visión Artificial la comunicación entre ambos sistemas.
- Colaborar con Electrónica en la integración de sensores, motores y controladores.
- Coordinar con Mecánica las características y limitaciones de movimiento.
- Realizar pruebas y documentar resultados.
- Participar en las actividades de Visión Artificial e Integración.
- Mantener organizada la documentación técnica del sistema.

Las metas específicas, entregables y fechas de cumplimiento se establecerán en los compromisos del área y se administrarán mediante GitHub Issues y GitHub Projects.

## 3. Organización de archivos

| Recurso | Ubicación |
|---|---|
| Código fuente de Control | Repositorio GitHub — Ubicación pendiente de definir |
| Documentación técnica de Control | Este README y documentación del código |
| Documentación de Visión Artificial | `Software/Vision/README.md` |
| Documentación de Integración | `Software/Integracion/README.md` |
| Carta de compromiso | Enlace pendiente de definir |
| Actividades y entregables | GitHub Issues |
| Planeación y cronograma | GitHub Projects |

## 4. Documentación y control de versiones

El código y la documentación de Control deberán mantenerse organizados dentro del repositorio, permitiendo comprender el funcionamiento de los programas e identificar las modificaciones realizadas.

### Consideraciones generales

- Utilizar nombres claros para archivos, funciones y variables.
- Documentar los algoritmos y módulos principales.
- Identificar las librerías y dependencias utilizadas.
- Registrar los parámetros relevantes de control.
- Documentar los motores, actuadores y sensores utilizados.
- Mantener identificadas las versiones del código.
- Registrar los cambios importantes en los programas.
- Documentar procedimientos de calibración.
- Realizar pruebas antes de integrar modificaciones.
- Registrar problemas, soluciones y resultados.
- Evitar archivos duplicados o desactualizados.
- Procurar que ambos integrantes comprendan los cambios relevantes.

Las modificaciones importantes deberán registrarse en los Issues correspondientes y relacionarse con la evidencia técnica disponible.

## 5. Colaboración entre áreas

El desarrollo de Control deberá mantenerse coordinado con Visión Artificial, Electrónica y Mecánica.

### Visión Artificial

La colaboración con Visión Artificial permitirá integrar la información obtenida del entorno con los algoritmos de control y navegación del robot.

Denis y Ricardo deberán coordinar la comunicación entre programas, las entradas y salidas de información y las pruebas de integración.

Ambos participarán en el desarrollo de Control y Visión Artificial, independientemente de su responsabilidad principal.

### Electrónica

La colaboración con Electrónica permitirá asegurar la compatibilidad entre el software de control y los componentes electrónicos, sensores, motores y actuadores.

Los problemas relacionados con conexiones, comunicación, calibración y funcionamiento de sensores deberán investigarse de manera conjunta.

### Mecánica

La colaboración con Mecánica permitirá considerar la configuración física del robot, las características de movimiento, los mecanismos y las limitaciones mecánicas.

Las modificaciones que afecten la cinemática o el comportamiento del robot deberán coordinarse para mantener la compatibilidad entre los sistemas.

Las decisiones que afecten a varias áreas deberán discutirse en conjunto para evitar incompatibilidades durante la integración.

## 6. Seguimiento del área

Las actividades, entregables y evidencias se administrarán mediante GitHub Issues y GitHub Projects.

Las actividades relacionadas con Control podrán identificarse mediante la categoría `software/control`.

Denis será el responsable principal de dar seguimiento a esta especialidad, mientras que Ricardo colaborará en su desarrollo y revisión.

Ambos integrantes deberán participar en las decisiones técnicas y mantener comunicación constante sobre los cambios que afecten al sistema.

Los avances se revisarán durante las juntas generales de los miércoles a las 5:00 p. m.

Este README describe el funcionamiento general del área y solamente deberá actualizarse cuando existan modificaciones importantes en su organización o documentación.

---

## Mensaje de la PM — Para Denis

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

