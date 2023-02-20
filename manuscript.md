---
title: Diagnóstico SOA Actual FNA
keywords:
- SOA
- madurez
- gobierno
lang: en-US
date-meta: '2023-02-20'
author-meta:
- Harry Wong, ing.
- Eddie Hernandez, ing.
- Federico Suárez, ing.
- Darío Correal, ing.
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Diagnóstico SOA Actual FNA" />
  <meta name="citation_title" content="Diagnóstico SOA Actual FNA" />
  <meta property="og:title" content="Diagnóstico SOA Actual FNA" />
  <meta property="twitter:title" content="Diagnóstico SOA Actual FNA" />
  <meta name="dc.date" content="2023-02-20" />
  <meta name="citation_publication_date" content="2023-02-20" />
  <meta property="article:published_time" content="2023-02-20" />
  <meta name="dc.modified" content="2023-02-20T04:40:48+00:00" />
  <meta property="article:modified_time" content="2023-02-20T04:40:48+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Harry Wong, ing." />
  <meta name="citation_author_institution" content="Arquitecto SOA, Stefanini" />
  <meta name="citation_author" content="Eddie Hernandez, ing." />
  <meta name="citation_author_institution" content="Datos, Stefanini" />
  <meta name="citation_author" content="Federico Suárez, ing." />
  <meta name="citation_author_institution" content="Infraestructura, Stefanini" />
  <meta name="citation_author" content="Darío Correal, ing." />
  <meta name="citation_author_institution" content="Arquitecto TI, Stefanini" />
  <link rel="canonical" href="https://hwong23.github.io/fna-devdoc-f3/" />
  <meta property="og:url" content="https://hwong23.github.io/fna-devdoc-f3/" />
  <meta property="twitter:url" content="https://hwong23.github.io/fna-devdoc-f3/" />
  <meta name="citation_fulltext_html_url" content="https://hwong23.github.io/fna-devdoc-f3/" />
  <meta name="citation_pdf_url" content="https://hwong23.github.io/fna-devdoc-f3/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://hwong23.github.io/fna-devdoc-f3/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-devdoc-f3/v/b9d9472885bf91249712c3fd76551d2883d5d73f/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-devdoc-f3/v/b9d9472885bf91249712c3fd76551d2883d5d73f/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-devdoc-f3/v/b9d9472885bf91249712c3fd76551d2883d5d73f/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...





Documentación del proyecto 181-2020, E-Service, 
([permalink](https://hwong23.github.io/fna-devdoc-f3/v/b9d9472885bf91249712c3fd76551d2883d5d73f/))
versión indicada a continuación, se encuentra en 
****
[b9d9472](https://github.com/hwong23/fna-devdoc-f3/tree/b9d9472885bf91249712c3fd76551d2883d5d73f)
de February 20, 2023.



## Grupo E-Service



+ **Harry Wong, ing.**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [e_hwong](https://github.com/e_hwong)
    <br>
  <small>
     Arquitecto SOA, Stefanini
  </small>

+ **Eddie Hernandez, ing.**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [e_ehernandez](https://github.com/e_ehernandez)
    <br>
  <small>
     Datos, Stefanini
  </small>

+ **Federico Suárez, ing.**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [e_fsuarez](https://github.com/e_fsuarez)
    <br>
  <small>
     Infraestructura, Stefanini
  </small>

+ **Darío Correal, ing.**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [e_dcorreal](https://github.com/e_dcorreal)
    <br>
  <small>
     Arquitecto TI, Stefanini
  </small>



***


#### PR9. Portafolio de iniciativas y brechas

# Fase 3: SOA Objetivo
# Contenido de los Productos Contractuales, 181-2020

# Producto 9: PR9. Portafolio de Inciativas y Brechas SOA Objetivo
La técnica del portafolio de brechas es utilizada en el desarrollo de este ejercicio de diagnóstico SOA del FNA para delinear los proyectos generadores de cambios aplicables a la situación actual SOA (Fase 1 del proyecto). El portafolio parte desde la arquittectura candidata desarrollada en la fase anterior e identifica los paquetes de trabajo (iniciativas, proyectos, reformas) que conducen al FNA a la arquitectura SOA candidata. La idea principal del análisis de brecha es resaltar los proyectos o ítems omitidos, o por definir, entre la situación actual SOA del FNA (fase 1 del diagnóstico) y la situación objetivo (fase 2). Incluso cuando esta última está todavía en evolución es posible avistar dichos cambios y proyectos. Lo anterior da origen al portafolio de iniciativas priorizadas, las mismas que al ser programas en el tiempo se convierte en la _hoja de ruta SOA del FNA_ (producto 10 de esta fase), y cuya ejecución cerrará las brechas entre el estado inicial SOA y el objetivo.

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto SOA: dependencia de proveedor (OBJ1), fortaleza SOA de las aplicaciones (OBJ2), y tiempo de mercado (OBJ3).

<br>

## Justificación
Asegurar que la arquitectura SOA del Fondo apegada a la [Vista de Segmento FNA](vistadesegmento.md) soporte al procesamiento de información, a los sistemas de información, a las capacidades de negocio, y tecnologías requeridas para cumplir los objetivos de este ejercicio de diagnóstico SOA y que están diagramados en la arquitectura SOA candidata del FNA. Provee los paquetes de trabajo que garanticen (continuidad, orden e impacto) la realización de los cambios entre evoluciones de la arquitectura SOA del Fondo. Por último, el portafolio proporciona datos de entrada para los procesos de contratación y adjudicación futuros que el FNA considere para la implementación de los cambios.


## Contenidos
1. Matriz de brechas de arquitectura SOA candidata del segmento FNA
1. Lista de iniciativas y proyectos (paquetes de trabajo) del segmento FNA: ítems por retener, rediseñar, actualizar, retirar
1. Análisis de impacto y dependencia entre los cambios en el segmento FNA
1. Ficha descriptiva de proyectos para el segmento FNA (justificación)

<br>

## Criterios de Aceptación

* Lista de cambios para el segmento FNA: ítems incluídos, por mejorar, nuevos y eliminados
* Hoja de ruta preliminar hacia un objetivo de mejora

*** 


|Tema            |Portafolio de iniciativas y brechas: **Método de análisis de brecha FNA**|
|----------------|---------------------------------------------------|
|Palabras clave  |SOA, Análisis de brecha, GAP, Comparativa          |
|Autor           |                                                   |
|Fuente          |                                                   |
|Version|b9d9472 del 20 Feb 2023                              |
|Vínculos|[N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)|

<br>

## Método de Análisis de Brecha FNA
El método de análisis de brecha para el FNA está adaptado en cuanto a hacer foco en los resultados esperados de las brechas y en usar los resultados de las fases anteriores del presente ejercicio SOA (ver [04b.Resumen Fase 1](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)). Este análisis de brecha busca dos onjetivos concretos.

<br>

### Objetivos del Análisis de Brecha FNA
Este análisis busca dos objtivos concretos: encontrar brechas que reutilicen los activos de software y TI del FNA. El segundo objetivo es encontrar los brechas que mejor conecten con las problemáticas encontradas en las fases de este diagnóstico SOA. 

1. Reutilizar los activos de software y TI del FNA. Todos los activos de software y TI disponibles en el FNA deben ser equiparados, funcional y tecnológicamente, con los ajustes requeridos por la acrquitectura candidata versión 2.0 entregada por la fase 2 de este diagnóstico. Este objeitvo entrará a delinear las estrategias de implementación de las brechas (soluciones futuras) que se encuentren.

1. Brechas que conecten con las problemáticas y conocimiento previo. Este método parte de la selección de los ítems y conocimiento considerados relevantes, como problemáticas, riesgos y oportunidades, que fueron desarrolladas en las fases anteriores de este proyecto de diagnóstico SOA del FNA. Cada uno de estos contribuye a la identificación de brechas importantes para el Fondo. Por ejemplo, si partimos de uno de los objetivos de esta consultoría, el de flexibilidad, vamos a encontrar brechas que aporten a cumplirlo.

<br>

### Entradas y Salidas del Método Análisis de Brecha FNA
En la siguiente imagen presentamos las entradas necesarias para garantizar tanto las salidas como los objetivos que este método se propone (descritos arriba).

![](images/brecha1.png)

[Imagen 1.]() Entradas y salidas del método de análisis de brechas FNA. Relación de las fases anteriores con las expectativas y productos contractuales de esta última fase.

_Fuente: elaboración propia._

<br>

Las entradas más importantes para la realización de este método son las arquitecturas de referencias, la versión 1.0, elaborada en la fase 1 de este diagnóstico, y la versión sigiuente, la 2.0, elaborada en la fase 2.

De las salidas de este método, la que más conecta con las expectativas es el de la matriz de brechas, que a la vez, se convierte en el portafolio de iniciativas y brechas, producto 9 (PR9), que es el principal de esta última fase del presente proyecto. Esta salida se complementa con otra: la de las estrategias preliminares de implementación de las brechas. Estas dos salidas las consideramos entre las más importantes que se desarrollanrán con la aplicación de este métrodo.


|Tema            |Portafolio de iniciativas y brechas (Deliverable): **Matriz de brechas de arquitectura SOA candidata del segmento FNA**|
|----------------|---------------------------------------------------|
|Palabras clave  |SOA, Análisis de brecha, GAP, Comparativa          |
|Autor           |                                                       |
|Fuente          |                                                       |
|Version|b9d9472 del 20 Feb 2023                                  |
|Vínculos|[N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)|

<br>

## Matriz de brechas de arquitectura SOA candidata del segmento FNA


|Tema            |Portafolio de iniciativas y brechas (Deliverable): **Lista de iniciativas y proyectos SOA**|
|----------------|---------------------------------------------------|
|Palabras clave  |SOA, Análisis de brecha, GAP, Comparativa          |
|Autor           |                                                       |
|Fuente          |                                                       |
|Version|b9d9472 del 20 Feb 2023                                  |
|Vínculos|[N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)|

<br>

## Lista de iniciativas y Proyectos de Cierre de Brecha


# Fase 3: SOA Objetivo
# Contenido de los Productos Contractuales, 181-2020

# Producto 10: PR10. Hoja de Ruta SOA
La hoja de ruta SOA (o el plan de migración) es la programación en el tiempo de un rumbo viable de cambios (migración) en la arquitectura SOA actual del FNA con la intención de moverla de un estado a otro. Plantea el despliegue en el tiempo de la ejecución de las capacidades y proyectos de migración (rollout) de la arquitectura SOA actual del FNA que resulten en la arquitectura SOA candidata con arreglo al portafolio de iniciativas y proyectos (producto 9) del presente diagnóstico. La hoja de ruta plantea además un programa de los estadios intermedios requeridos, y sus controles, para llegar a la arquitectura SOA objetivo coordinado con la oficina de proyectos del FNA para asegurar 

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto SOA: dependencia de proveedor (OBJ1), fortaleza SOA de las aplicaciones (OBJ2), y tiempo de mercado (OBJ3).

<br>

## Justificación
Procura la articulación y gestión de dependencias de las iniciativas SOA del portafolio de la arquitectura SOA (producto 9 de este diagnóstico) con otros proyectos del FNA, a fin de economizar recursos o evitar colisiones. Asegura a la gerencia de tecnología del FNA los criterios para la vigilancia y los puntos de control y revisión de las migraciones transitorias y estables con el propósito de que los equipos implementen los proyectos conforme a los diseños. En términos generales, _este producto es el responsable de organizar la transformación de la arquitetura en implementación_. 

## Contenidos
1. Hoja de ruta de los proyectos de cambio
1. Estimaciones y análisis de impacto y dependencia entre los cambios en el segmento de la empresa
1. Consideraciones para la ejecución de los primeros cambios
1. Puntos de control en la ejecución de la hoja de ruta SOA

<br>

## Criterios de Aceptación

* Lista de cambios para el segmento FNA: ítems incluídos, por mejorar, nuevos y eliminados
* Hoja de ruta preliminar hacia un objetivo de mejora

*** 


## Resumen de Problemáticas del Diagneostivo de Madurez SOA del FNA

1. FNA realiza soluciones de herramientas de software y servicios SOA a la medida para responder a las necesidades y requerimientos de información de las áreas funcionales, en particular la vicepresidencia de Crédito y la de Operaciones (segmento de la empresa objeto de este diagnóstico). El peligro con esto es que hace a la operación (creación, uso y mantenimiento) y a la gestión (mejora, explotación y distribución) de los datos proclive a la proliferación de silos de datos.

1. El análisis del repositorio SOA del FNA evidencia que existen modelos de datos independientes para las diferentes aplicaciones. Por lo tanto, _no existe un modelo de datos común o canónico para la organización_. Así mismo, existen inconvenientes en la gestión del ciclo de vida del dato debido a que existen algunas dependencias de algunos los proveedores para incluir reglas de negocio o nuevas entidades de datos.

1. Desde la perspectiva de madurez SOA, la primera iteración del proceso de evaluación de madurez SOA del FNA determina que el _FNA es una empresa reactiva_, resultado además que es consistente en todas las dimensiones de OSIMM diagnosticadas (negocio, aplicaciones, gobierno, etc.).

1. Mejorar los indicadores de eficacia y madurez SOA, como el de soporte y flexibilidad de negocio, el de diseño de soluciones, servicios y aplicaciones, gestionar los cambios desde arquitectura, mejorar los problemas de uso y gestión de la información e infraestructura. Niveles bajos causados principalmente por (1.) El bajo grado de independencia de proveedor: (ver imagen abajo) _38 puntos / 100 puntos_ (2.) Baja flexibilidad y tiempos de entrega (time-to-market): _20 / 100 puntos_.  **Nota**. Estas dos problemáticas deben las ser primeras en ser atendidas en un futuro gobierno SOA del Fondo. ![](images/madurezInfo_graf.png)

1. El futuro gobierno SOA, en conjunto con el plan de la Dirección de Tecnología del FNA, y el próximo plan estratégico (febrero del 2023) debe procurar la ejecución y los recursos necesarios para la realización de estas iteraciones que tienen por objeto mover la adopción SOA del Fondo al siguiente estadio: mayor a 50 puntos de madurez SOA.

1. Para aumentar las capacidades de la arquitectura es necesario realizar un análisis de capacidades de la arquitectura que responda a las capacidades del negocio (alineación negocio, arquitectura). De igual nivel de importancia que el caso anterior, esta problemática del aumento de las capacidades debe hacer parte de los planes de la Dirección de Tecnología del FNA y del próximo plan estratégico (febrero del 2023).

1. Con este enfoque, el gobierno SOA futuro debe lograr, primordialmente, aumentar el índice de independencia de proveedor del Fondo. El resultado interno (ver imagen abajo) en la dimensión de Gobierno obtuvo el puntaje más bajo en este análisis: _35 / 100 puntos_ (los otros análisis, flexibilidad y fortaleza SOA, en esta misma dimensión obtuvieron en promedio 40 puntos).


