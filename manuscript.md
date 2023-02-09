---
title: Diagnóstico SOA Actual FNA
keywords:
- SOA
- madurez
- gobierno
lang: en-US
date-meta: '2023-02-09'
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
  <meta name="dc.date" content="2023-02-09" />
  <meta name="citation_publication_date" content="2023-02-09" />
  <meta property="article:published_time" content="2023-02-09" />
  <meta name="dc.modified" content="2023-02-09T19:32:01+00:00" />
  <meta property="article:modified_time" content="2023-02-09T19:32:01+00:00" />
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
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-devdoc-f3/v/f0eed734c661a29e73824ba2847d7d1030f55ffe/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-devdoc-f3/v/f0eed734c661a29e73824ba2847d7d1030f55ffe/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-devdoc-f3/v/f0eed734c661a29e73824ba2847d7d1030f55ffe/manuscript.pdf" />
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
([permalink](https://hwong23.github.io/fna-devdoc-f3/v/f0eed734c661a29e73824ba2847d7d1030f55ffe/))
versión indicada a continuación, se encuentra en 
****
[f0eed73](https://github.com/hwong23/fna-devdoc-f3/tree/f0eed734c661a29e73824ba2847d7d1030f55ffe)
de February 9, 2023.



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


#### PR9. Portafolio de iniciativas y brechas (Deliverable)

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

