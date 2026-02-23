# RESPUESTAS — Reflexión y Resumen (Plantilla genérica)

> **Actividad / ID:** 2.a..e  
> **Unidad / Tema:** Unidad 2 - Análisis de Incidentes  
> **Alumno/a:** Iván Paúl Alba  
> **Fecha:** 23/02/2026  

---

## 1) Reflexión crítica (preguntas)
Responde con **lenguaje técnico** y **argumentos** (no solo opiniones). Si procede, usa ejemplos, riesgos y decisiones justificadas.

### 1.1) ¿Qué te han parecido los temas tratados en la unidad?

Los temas de esta unidad me han parecido generalmente interesantes y muy prácticos para el mundo laboral. Al principio me costó un poco entender cómo se relacionaban todos los conceptos entre sí, pero cuando empecé a tocar las herramientas OSINT; mostré más interés por el tema. Trabajar con los sistemas como Snort y ELK también fue interesante aunque el proceso un tanto frustrante.

### 1.2) ¿Qué ha sido más útil para tu futuro puesto de trabajo? ¿Por qué?

Pienso que ha sido el manejo de herramientas OSINT ya que es muy útil tanto para el mundo laboral como para el manejo personal además de la selección y análisis de proveedores SOC y CERT, ya que es importante conocer las opciones que hay en el mercado para poder elegir la mejor solución para cada caso.

### 1.3) ¿Qué partes ya conocías y cuáles han sido nuevas para ti?

Desconocía todos los conceptos tratados en la unidad; por ejemplo, sabía de la existencia de heeramientas OSINT pero no sabía ni como se le llamaba a eso ni que tampoco había un framework para ellas que se centra en recopilar todas las herramientas que se usan para ello según el tipo de dato que uno quiera obtener.

### 1.4) ¿Qué concepto/idea te ha llamado más la atención y por qué?

El uso de herramientas OSINT y la instalación y configuración de ELK y Snort me ha llamado mucho la atención, ya que es algo que no había hecho antes y me ha parecido muy útil para entender cómo se detectan los incidentes de seguridad. Además, me ha sorprendido la cantidad de información que se puede obtener sobre una persona o una organización solo con buscar en fuentes públicas, lo cual me hace ser más consciente de mi propia huella digital.

### 1.5) ¿Qué parte recortarías o simplificarías si hubiera menos tiempo? Justifica.

El tema de la taxonomía de incidentes me ha parecido un poco tedioso y teórico, y aunque entiendo la importancia que tiene para clasificar y gestionar los incidentes, creo que se podría haber reducido un poco.

### 1.6) ¿Qué tema has echado en falta o ampliarías? Justifica.

Me hubiera gustado ver más ejemplos de noticias de incidentes reales y cómo se resolvieron con el profesor. Creo que enseñarnos casos reales nos ayudaría a mostrar más interes sobre el caso en cuestión e incentivarnos al debate y la participación con el alumnado.

### 1.7) ¿Qué aplicarías “mañana” en un entorno real con recursos limitados?

Una monitorización másica de ELK y dar algunas lecciones básicas a los trabajadores sobre OSINT para concienciarlos de los riesgos que pueden tener en la empresa según lo que publiquen incluso en su vida personal.

### 1.8) ¿Qué duda, riesgo o punto crítico te queda abierto tras la unidad?

La mayor duda que me queda es como responder ante ciertos incidentes además de los conceptos tocados CSIRT, CERT y CIRT que no los he llegado a tener claros.


## 2) Resumen esquematizado (obligatorio)

| Aspecto                         | Descripción                                                                 |
|----------------------------------|----------------------------------------------------------------------------|
| Unidad                          | Unidad 2 – Análisis de Incidentes                                          |
| Concepto clave                  | Comprensión de qué es un incidente de seguridad                            |
| Clasificación                   | Identificación y categorización de incidentes según su tipo y gravedad     |
| Herramientas de detección       | Snort (IDS) y ELK (análisis y correlación de logs)                        |
| Técnicas aplicadas              | Uso de OSINT para evaluación de información pública                        |
| Equipos involucrados            | Equipos de respuesta a incidentes (CSIRT / SOC)                           |
| Competencias desarrolladas      | - Detección de amenazas                                                    |

### 2.1) Mapa/índice de la unidad (visión global)

**Bloque 1: Fundamentos del análisis de incidentes**
- Definición de incidente de seguridad
- Taxonomía de incidentes
- Importancia de documentar y clasificar correctamente

**Bloque 2: OSINT**
- OSINT pasivo: recopilación de información y trabajo en grupo
- Herramientas para la investigación en fuentes abiertas
- Evaluación de huella digital y exposición de información

**Bloque 3: Equipos y estructuras de seguridad**
- SOC: Centro de Operaciones de Seguridad
- CSIRT: Equipo de Respuesta a Incidentes de Seguridad Informática
- CERT: Equipo de Respuesta ante Emergencias Informáticas
- CIRT: Equipo de Respuesta a Incidentes Informáticos
- Selección y análisis de proveedores SOC y CERT

**Bloque 4: Herramientas de detección**
- SIEM: Gestión de Información y Eventos de Seguridad
- IDS: Sistema de Detección de Intrusos
- IPS: Sistema de Prevención de Intrusos
- Implementación práctica para detectar incidentes

**Bloque 5: Prácticas con herramientas específicas**
- ELK Stack (Elasticsearch, Logstash, Kibana) para análisis de logs
- Snort como sistema de detección de intrusos de red
- Configuración en contenedores Docker

### 2.2) Conceptos clave (lista breve)

**Incidente de seguridad:** Cualquier evento que compromete o amenaza la confidencialidad, integridad o disponibilidad de la información o los sistemas de una organización.

**Taxonomía de incidentes:** Sistema de clasificación que permite categorizar los incidentes según su tipo, gravedad, impacto y otros criterios para gestiomarlos de forma organizada.

**OSINT pasivo:** Técnica de recolección de información a partir de fuentes públicas sin interactuar directamente con el objetivo, lo que hace que la investigación sea legal.

**SOC:** Centro de operaciones donde un equipo de analistas monitoriza, detecta, analiza y responde a incidentes de ciberseguridad.

**CSIRT/CERT/CIRT:** Equipos especializados en responder ante incidentes de seguridad, coordinando acciones de contención, erradicación y recuperación cuando ocurre un problema.

**SIEM:** Sistema que recopila y analiza información de múltiples fuentes para detectar posibles amenazas en tiempo real.

**IDS:** Sistema que monitoriza el tráfico de red o las actividades del sistema para detectar comportamientos sospechosos o maliciosos y generar alertas.

**IPS:** Similar al IDS pero con capacidad de bloquear o prevenir activamente las amenazas detectadas, no solo alertar sobre ellas.

**ELK Stack:** Conjunto de tres herramientas (Elasticsearch para búsqueda, Logstash para procesamiento y Kibana para visualización) que permiten analizar y monitorizar logs.

**Snort:** Herramienta de código abierto que funciona como IDS o IPS, analizando y detectando el tráfico de red en tiempo real.

**Docker:** Plataforma que permite crear entornos llamados contenedores para ejecutar aplicaciones de forma independiente, no tiene que ver con el sistema principal. 

### 2.3) Procesos / procedimientos (pasos o checklist)

Monitorizo con SIEM o IDS, reviso las alertas que saltan, clasifico si es real o falso positivo, documento y escalo al equipo correspondiente.

Para OSINT busco información en fuentes públicas del framework del mismo; analizo los riesgos y lo documento.

Con Docker instalo las imágenes de ELK y Snort, configuro reglas, dashboards y voy ajustando las pruebas.

### 2.4) Herramientas / técnicas (si aplica)

OSINT: TiniEye, Webmii, PeekYou, Epieos, HaveIbeenPwned, WayBack Machine, SpiderFoot, WHOIS, DNSDumpster y crt.sh.

Para detectar incidentes: ELK, Snort, Docker y el menú de Kibana.

### 2.5) Buenas prácticas y errores típicos

Debo documentar y clasificar bien para evitar falsos positivos.

Evito ignorar alertas sin revisar, olvidar documentar, depender de una sola herramienta y exponer información sensible.

### 2.6) Glosario mínimo (términos y definiciones cortas)

**Alerta:** Aviso cuando el sistema detecta algo sospechoso.
**Falso positivo:** Alerta que parece mala pero no lo es.
**Huella digital:** Información que dejamos en internet.
**Logs:** Registros de actividad de sistemas y aplicaciones.
**Monitorización:** Vigilancia continua de sistemas para detectar problemas.
**Tráfico de red:** Datos que circulan entre dispositivos en una red.

## 3) (Opcional) Evidencias y recursos usados
Enlaza aquí evidencias (capturas, logs, configuraciones, salidas de comandos, etc.) si forman parte de tu trabajo.

### Evidencia 1
- Archivo: `evidencias/01_...`
- Qué demuestra:
- Qué he aprendido:

### Evidencia 2
- Archivo: `evidencias/02_...`
- Qué demuestra:
- Qué he aprendido:


## 4) Conclusión (cierre)

Esta unidad me ha resultado un poco más interesante que el anterior por los temas tocados como he mencionado anteriormente.
Pienso que la parte práctica al fin y al cabo es la que me ha resultado más útil y le he puesto más empeño. Por otra parte, el trabajo de conceptos SOC, CSIRT, CERT y CIRT, SIEM, IDS, IPS entre otros no me ha gustado ni por la manera de aprenderlo, ni por el tiempo en el que se ha dado ese criterio.
