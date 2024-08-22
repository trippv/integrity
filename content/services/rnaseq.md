---
title: 'RNAseq'
date: 2018-11-18T12:33:46+10:00
icon: 'services/rnaseq.png'
draft: false
featured: true
weight: 1
heroHeading: 'RNAseq'
heroSubHeading: ''
heroBackground: 'images/dna.jpg'
---


Un análisis de RNAseq tiene el objetivo de cuantificar y comparar la expresión de genes a nivel de ARN mensajero (ARNm) en diferentes muestras o condiciones experimentales. 

Este análisis permite identificar qué genes están siendo activados o desactivados, y en qué medida, en respuesta a diferentes factores, como condiciones ambientales, tratamientos, estados de enfermedad o diferencias entre especies. 

A través de RNAseq, se puede obtener una visión integral del transcriptoma, que es el conjunto completo de transcripciones de ARN en una célula o tejido en un momento dado. Esto proporciona información valiosa sobre los procesos biológicos subyacentes, las vías moleculares involucradas y puede ayudar en la identificación de biomarcadores y una mejor comprensión de la biología celular y molecular.

## Flujo de trabajo:


{{< figure src="/services/rnaseq_pipe.jpg" height="800px"  width="600px" style="display:block; margin-left:auto; margin-right:auto;">}}

## Este proyecto no incluye:

*   Extracción, purificación, preparación de librerias ni secuenciación de ARN
*   Discusión ni interpretación de los resultados obtenidos 


## Entregables:

*   Resultados de control de calidad de secuencias crudas y procesadas (html)
*   Secuencias del ensamble de transcriptoma (fasta)
*   Resultados de control de calidad del ensamble (BUSCO, Transrate) (pdf)
*   Archivo de anotación del ensamble usando la base de datos Uniprot y pfam (xls)
*   Gráfico de análisis multivariados (PCA; MDS) con los valores de expresión globales (eps/pdf)
*   Lista de genes/transcritos expresados diferencialmente (xls).
*   Gráficas de volcán, MA, heatmaps y patrones de expresión (eps/pdf)
*   Resultados de enriquecimiento funcional (Gene Ontology; KEGG)(xls)
*   Dashboard interactivo con genes expresados diferencialmente (html)
