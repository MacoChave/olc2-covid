# Manual de usuario

- [Manual de usuario](#manual-de-usuario)
  - [Introducción](#introducción)
  - [Interfaz gráfica](#interfaz-gráfica)
    - [Área de navegación](#área-de-navegación)

## Introducción

Esta aplicación tendrá como objetivo principal que un usuario pueda generar distintos análisis de información basados de un origen de datos (un archivo en Excel, CSV o JSON) y diferentes variables que se deberán configurar dentro del sistema según sea el ánalisis a realizar.

## Interfaz gráfica

![](./assets/GUI.jpeg)
La aplicación, cuenta con tres apartados:

- `Seleccionar análisis` 
Se encuentran diversas opciones a seleccionar según el análisis que se desee. En el cuál encontraremos:

```sh
Tendencia de la infección por COVID-19 en un País
Predicción de infectados
Índice de progresión de la pandemia
Predicción de mortalidad por COVID-19 en un Departamento
Predicción de mortalidad por COVID-19 en un País
Análisis del número de muertes por COVID-19 en un País
Tendencia del número de infectados por día de COVID-19 de un País
Predicción de casos de un País para un año
Tendencia de la vacunación de un País
```

- `Subir archivo` 
En este apartado se debe de seleccionar un archivo externo para subir al analizador de COVID-19 y después se encuentra el apartado de: Separador; éste será seleccionado según se encuentren separados los datos en el archivo de referencia y estos pueden ser:

| Nombre         | Símbolo |
| -------------- | ------- |
| Coma           | ,       |
| Punto y coma   | ;       |
| Barra vertical | \|      |

- `Completar campos` 
Se encuentran diversas parámetros de columnas que deben ser completadas con los datos necesarios que se subdividen en País, Casos confirmados y Fecha. También es necesario definir los filtros colocando el País de interés para la obtención del análisis realizado por el programa.

### Área de navegación

![](./assets/GUI_Navigation.jpg)

Los pasos para la usabilidad de la aplicación web es la siguiente:

1. Seleccionar una de las opciones que se presentan en la pantalla como por ejemplo: `Tendencia de la infección por COVID-19 en un País`.
2. Presionar el botón `Siguiente`
3. Selección y subir un archivo externo con los datos necesarios para el análisis del programa.
4. Sellecionar el separador que se esté utilizando en el archivo externo  para separar los datos, como por ejemplo: punto y coma `;`
5. Presionar el botón `Siguiente`
6. Llenar los campos requeridos en las cajas y definir los filtros.
7. Presiónar el botón `ANALIZAR`
8. Si se desea realizar un nuevo análisis, presionar el botón `RESET` y empezar el proceso nuevamente según se indica en el numeral 1.