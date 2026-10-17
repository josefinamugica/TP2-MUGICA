# TP2 - Reporte de movimientos de Ecobici

**Materia:** Programación Orientada a Datos  
**Universidad:** Universidad Católica Argentina (UCA)  
**Trabajo:** Trabajo Práctico 2 - Individual  
**Autor:** Josefina Mugica

## 1. Descripción del proyecto

Este proyecto consiste en el desarrollo de una aplicación en Python destinada al análisis de los viajes realizados mediante el sistema de bicicletas públicas Ecobici de la Ciudad Autónoma de Buenos Aires.

La aplicación permitirá procesar registros de viajes para obtener información sobre los movimientos de bicicletas entre las distintas estaciones durante un período determinado, facilitando la organización, el análisis y la interpretación de los datos.

## 2. Problema

El sistema Ecobici registra viajes entre diferentes estaciones de la ciudad. El análisis manual de estos movimientos puede resultar complejo, especialmente cuando se trabaja con numerosos registros que pueden contener información incompleta, duplicada o incorrecta.

Estas inconsistencias pueden afectar los resultados y dificultar la identificación de patrones de movimiento entre estaciones.

Por este motivo, se propone desarrollar una herramienta que permita procesar, validar y organizar los datos de manera sistemática, generando reportes que faciliten la comprensión de la actividad registrada en cada estación.

## 3. Usuarios

La aplicación está dirigida a estudiantes, investigadores y personas interesadas en analizar el funcionamiento del sistema de bicicletas públicas Ecobici.

También podría resultar útil para quienes estudian la movilidad urbana y necesitan obtener información organizada sobre los movimientos registrados entre estaciones.

## 4. Solución propuesta

Se desarrollará una aplicación en Python que permitirá realizar las siguientes operaciones:

- Importar archivos de viajes en formatos CSV y JSON.
- Verificar la estructura de los datos y validar los registros.
- Identificar registros incompletos, duplicados o inconsistentes.
- Limpiar y organizar la información para su posterior análisis.
- Seleccionar los viajes correspondientes a un período determinado.
- Calcular la cantidad de salidas y llegadas por estación.
- Obtener el balance neto de movimientos de cada estación.
- Generar un reporte con los resultados obtenidos.
- Registrar los viajes rechazados junto con los motivos de su exclusión.

El programa seguirá un proceso de lectura, validación, limpieza, análisis y presentación de resultados, permitiendo repetir las operaciones con los mismos datos de entrada.

## 5. Resultados esperados

La aplicación generará un reporte que incluirá, para cada estación analizada:

- **Cantidad de salidas:** total de viajes que comenzaron en la estación.
- **Cantidad de llegadas:** total de viajes que finalizaron en la estación.
- **Balance neto:** diferencia entre la cantidad de llegadas y salidas.

El balance se calculará mediante la siguiente expresión:

**Balance neto = Llegadas - Salidas**

Un balance positivo indicará que se registraron más llegadas que salidas, mientras que un balance negativo indicará lo contrario. Un balance igual a cero señalará que ambas cantidades fueron equivalentes.

Estos resultados permitirán identificar las estaciones con mayores diferencias entre los movimientos de entrada y salida durante el período seleccionado.

## 6. Alcance y limitaciones

En esta primera versión, la aplicación se centrará exclusivamente en el análisis de los movimientos de bicicletas registrados durante un período determinado.

Los viajes serán seleccionados según su fecha y hora de inicio, contabilizando tanto la estación de origen como la estación de destino de cada viaje válido.

El balance obtenido no representará la cantidad real de bicicletas disponibles en una estación, ya que no se contará con información sobre el inventario inicial, las reposiciones o los movimientos externos al conjunto de viajes analizado.

Para el desarrollo y las pruebas de la aplicación se utilizará un conjunto de datos simulados, que permitirá evaluar su funcionamiento en diferentes situaciones. Por lo tanto, los resultados obtenidos no deberán interpretarse como estadísticas reales del sistema Ecobici.

## 7. Estado del proyecto

El proyecto se encuentra en desarrollo.

Actualmente se ha definido el problema, los usuarios, la solución propuesta y el alcance de la aplicación.

A medida que avance el trabajo, se incorporarán las secciones correspondientes a la procedencia y estructura de los datos, instalación, ejecución del programa, pruebas, resultados e interpretación de los mismos.

