# Brecha de ingresos laborales en Ecuador

**Tablero sociodemográfico interactivo sobre ingresos laborales, género y territorio en Ecuador.**

- **Tablero publicado:** https://accaicedoa.github.io/Brecha-de-ingresos-laborales-en-Ecuador/
- **Repositorio:** https://github.com/accaicedoa/Brecha-de-ingresos-laborales-en-Ecuador
- **Fuente principal:** ENEMDU 2025
- **Autora:** Alanis Cristhine Caicedo A.

## Descripción

Este proyecto analiza la brecha de ingresos laborales en Ecuador desde una perspectiva territorial y sociodemográfica. El tablero permite explorar diferencias por provincia, género, área urbana/rural, edad y nivel educativo.

Aunque el plan inicial consideraba información relacionada con 2022, se utilizó ENEMDU 2025 para trabajar con datos más actualizados del mercado laboral ecuatoriano.

## Objetivo

Transformar datos abiertos de ENEMDU 2025 en un tablero interactivo que comunique, de forma clara y visual, las diferencias de ingresos laborales en Ecuador.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | Tablero web interactivo publicado en GitHub Pages. |
| `CAICEDO_Proceso_ETL_caso_socio_económico (1).ipynb` | Notebook con extracción, limpieza, carga SQLite, dimensiones, índices y validaciones. |
| `2_BDD_DATOS_ABIERTOS_ENEMDU_2025_CSV (2).zip` | Fuente de datos ENEMDU 2025. |
| `CAICEDO ALANIS. CD (1).pdf` | Plan visual del proyecto. |
| `README.md` | Documentación del proyecto. |

## Proceso realizado

1. **Identificación y captura:** selección de ENEMDU 2025 como fuente principal.
2. **ETL:** limpieza de columnas, nulos, claves, tipos de datos e ingresos.
3. **Base relacional:** creación de una base SQLite con tablas staging, fact tables, dimensiones, diccionarios e índices.
4. **Validación:** conteos de filas, claves únicas y relación persona-vivienda.
5. **Indicadores:** cálculo de KPIs nacionales, provinciales y sociodemográficos.
6. **Visualización:** construcción del tablero HTML con mapa, KPIs, gráficos, ranking y simulador.
7. **Publicación:** despliegue en GitHub Pages.

## Indicadores incluidos

- Ingreso laboral promedio.
- Ingreso per cápita promedio.
- Ingreso promedio de hombres.
- Ingreso promedio de mujeres.
- Brecha absoluta y porcentual hombre/mujer.
- Tasa de empleo 15+.
- Tasa de desempleo 15+.
- Población expandida.
- Indicadores por provincia, educación, edad, género y área.

## Funcionalidades del tablero

- Mapa geográfico coroplético por provincias.
- Inset de Galápagos.
- Leyenda integrada en el SVG.
- Hover con glow sobre provincias.
- Tooltip moderno con información provincial.
- KPIs principales.
- Ranking provincial Top 5 y Bottom 5.
- Comparador entre provincias.
- Gráficos de brecha de género, tendencia mensual, educación, edad y área urbana/rural.
- Simulador sociodemográfico interactivo.

## Gobernanza de datos

El proyecto aplica principios de gobernanza de datos:

- **Calidad:** limpieza de nulos, claves, columnas y valores inválidos.
- **Consistencia:** estandarización de nombres, categorías y tipos de datos.
- **Integridad:** validación de relaciones entre personas, hogares, vivienda, período y geografía.
- **Trazabilidad:** flujo documentado desde datos crudos hasta tablero final.
- **Seguridad:** publicación únicamente de datos agregados.
- **Disponibilidad:** tablero desplegado en GitHub Pages.
- **Usabilidad:** interfaz comprensible para usuarios no técnicos.
- **Transparencia:** documentación del cambio de datos 2022 a ENEMDU 2025.
- **Reproducibilidad:** notebook ETL reutilizable para futuras versiones.

## Cómo usar el tablero

1. Abrir el enlace del tablero publicado.
2. Seleccionar el indicador principal del mapa.
3. Hacer clic sobre una provincia para actualizar KPIs y lecturas automáticas.
4. Usar los botones Top 5 y Bottom 5 para explorar extremos.
5. Comparar dos provincias.
6. Usar el simulador para analizar perfiles por sexo, área, edad, educación y provincia.

## Enlace del tablero

https://accaicedoa.github.io/Brecha-de-ingresos-laborales-en-Ecuador/
