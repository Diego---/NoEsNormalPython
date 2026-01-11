# NoEsNormalPython

Migration and Regactoring of the R code used for Viri Rios' book: No es Normal

Este repositorio contiene una migración y refactorización del código original en R utilizado para el análisis estadístico del libro No es normal: el juego oculto que alimenta la desigualdad mexicana y cómo cambiarlo, de Viri Ríos.

El objetivo de este proyecto no es únicamente traducir el código existente, sino modernizar el pipeline de análisis, mejorando su legibilidad, mantenibilidad y extensibilidad mediante una implementación modular en Python.

## Objetivos del proyecto

- Migrar el código original escrito en R (tidyverse) a Python.

- Refactorizar la lógica para evitar scripts monolíticos y dependencias implícitas.

- Separar claramente:

    - carga y validación de datos

    - transformaciones

    - análisis estadístico

    - generación de tablas y figuras

- Facilitar la reproducibilidad del análisis.

Este repositorio no modifica los supuestos ni conclusiones del análisis original; se centra exclusivamente en su reimplementación técnica.

## Estructura del repositorio

La estructura del repositorio replica deliberadamente la organización del libro, primero por sección y luego por capítulo, manteniendo continuidad conceptual con el trabajo original:

```
.
├── 1.Competir/
│ ├── 1_VenderCaro/
│ ├── 2_Exitos/
│ ├── 3_Empresalandia/
│ ├── 4_BancaAbusa/
│ └── 5_EmpresaChica/
├── 2.Trabajar/
│ ├── 6_Fieston/
│ └── 7_MejoresTrabajadores/
├── 3.Contribuir/
│ ├── 11_RicosMasRicos/
│ ├── 12_Bahamas/
│ ├── 14_Edad/
│ └── 15_Finlandia/
├── 4.Gobernar/
│ ├── 16_Corrupcion/
│ └── 18_GobiernoDeCuates/
├── 5.Ser/
│ ├── 22_Ninis/
│ └── 25_NoEsNormal/
└── README.md
```

Cada carpeta de sección contiene subcarpetas correspondientes a los capítulos del libro. Dentro de la carpeta de cada capítulo se incluye:

- Código Python refactorizado

- Un README.md específico del capítulo

## Créditos

- Análisis original: Viri Ríos
- Migración y refactorización: Diego Olvera
