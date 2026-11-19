# Enunciado del ejercicio

## Contexto

*Energetic Soda* es una empresa que quiere patrocinar a un equipo de fútbol de La Liga (España). El equipo de marketing relevó a todos los clubes y obtuvo:

- el **costo del patrocinio** de cada equipo, y
- el **valor para la marca de cada gol** que convierte ese equipo.

El **presupuesto disponible es de $400.000**.

## Requerimientos

1. Replicar la **tabla general de la temporada 2017-18**.
2. Analizar y recomendar **en qué equipo invertir**, priorizando que sea un equipo **consistente en Primera División** (sin riesgo de descenso) y, idealmente, que juegue **competencias europeas**.

## Reglas

**Puntos por partido:** victoria = 3 · empate = 1 · derrota = 0.

**Clasificación a fin de temporada:**

| Posición | Resultado |
|---|---|
| 1 – 4 | Champions League |
| 5 – 7 | Europa League |
| 8 – 17 | Sin competencia |
| 18 – 20 | Descenso |

## Datos disponibles

- **10 archivos CSV** con los resultados de La Liga de 2008-09 a 2017-18 (380 partidos por temporada).
- **`investments.csv`**: costo de patrocinio y ganancia por gol de los 20 equipos de la temporada 2017-18.

### Estructura de los CSV de partidos

| Campo | Descripción | Ejemplo |
|---|---|---|
| Round | Se descarta | `?` |
| Date | Día, fecha y semana del año | `(Fri) 19 Aug 2016 (33)` |
| Team 1 | Equipo local (con jornada) | `RCD La Coruña (1)` |
| FT | Resultado final | `2-1` |
| HT | Resultado al entretiempo | `0-0` |
| Team 2 | Equipo visitante (con jornada) | `SD Eibar (1)` |
