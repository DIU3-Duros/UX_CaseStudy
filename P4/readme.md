## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
-----

Nos ha tocado el grupo DIU2.tertulianos que correspondera con la prueba B y nuestro proyecto con el A, sobre moda Re-.

Enlace a u repositorio: https://github.com/DIU2tertulianos

En este apartado se identifican los usuarios participantes en las pruebas, incluyendo su perfil con valores diferentes para una aproximacion mas exacta y el caso (A o B) que evaluaron.

| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| Oliver  | H / 21   | Estudiante Derecho | Baja       | Introvertido | móvil       | A 
| Maria  | M / 27   | Trabaja en Mercadona  | Media       | Extrovertida       | móvil        | A 
| Gael  | H / 21   | Estudia informatica     | Alta        | Timido    | móvil      | B 
| Encarnacion  | M / 54   | Trabaja en el ayuntamiento  | Baja       | Racional     | móvil        | B 


### 4.b Diseño de las pruebas 
-----
Se describen las pruebas seleccionadas para la evaluación de los prototipos, adaptadas al tipo de aplicación de cada grupo, indicando los objetivos y métricas asociadas.

| # | Tipo de prueba (Maze) | **Caso A – Moda Re-** | **Caso B – La Tertulia** | Métrica principal |
|---|-----------------------|-----------------------|--------------------------|-------------------|
| 1 | Mis-click Test        | Pulsar CTA «Crear Punto» | Pulsar CTA «Reservar»        | % primer clic correcto |
| 2 | Tarea guiada          | **Crear un punto de recogida** con fecha y plazas | **Reservar 2 plazas** para la tertulia de poesía del jueves | Tiempo (s) + nº clics |
| 3 | Tarea guiada          | **Buscar puntos** de recogida en el mapa | **Consultar agenda** de eventos de la semana | Tiempo (s) + % éxito |
| 4 | Tarea guiada          | **Apuntarse** a una donación existente | **Pagar entrada** (simulación) de un concierto del sábado | % éxito |
| 5 | **Cuestionario SUS**  | → ambos casos | → ambos casos | Puntuación 0-100 |
| 6 | **Eye-tracking**      | — (no se aplica) | varias pantallas | TTFF + %AOI |

### 4.c Cuestionario SUS
----
Aquí se recogen las puntuaciones del test de usabilidad SUS tras el uso de cada prototipo, lo que permite valorar la percepción general de usabilidad por parte de los usuarios.

| # | Ítem SUS                                                                                                  | Oliver | María | Gael | Encarnación |
|---|-----------------------------------------------------------------------------------------------------------|:------:|:-----:|:----:|:-----------:|
| 1 | Creo que me gustará visitar con frecuencia este website                                                   | **5**  | **5** |  **4** |     **4**    |
| 2 | Encontré el website innecesariamente complejo                                                             | **1**  | **2** |  **2** |     **3**    |
| 3 | Pensé que era fácil utilizar este website                                                                 | **5**  | **4** |  **4** |     **3**    |
| 4 | Creo que necesitaría del apoyo de un experto para recorrer el website                                     | **3**  | **2** |  **2** |     **2**    |
| 5 | Encontré las funciones del website bastante bien integradas                                               | **5**  | **4** |  **4** |     **3**    |
| 6 | Pensé que había demasiada inconsistencia en el website                                                    | **3**  | **2** |  **3** |     **2**    |
| 7 | Imagino que la mayoría de las personas aprenderían muy rápidamente a utilizar el website                  | **5**  | **4** |  **3** |     **3**    |
| 8 | Encontré el website muy grande al recorrerlo                                                              | **3**  | **2** |  **3** |     **3**    |
| 9 | Me sentí muy confiado en el manejo del website                                                            | **5**  | **4** |  **3** |     **3**    |
|10 | Necesito aprender muchas cosas antes de manejarme en el website                                           | **2**  | **3** |  **3** |     **3**    |

| Usuario | Caso | SUS | Escala lingüística |
|---------|------|-----|--------------------|
| Oliver        | A | **82** | Bueno |
| María         | A | **74** | Bueno |
| Gael          | B | **61** | Aceptable |
| Encarnación   | B | **56** | Marginal |
| **Media**     | **A / B** | **78 / 59** | — |

Asi que Moda Re- (A) obtiene **+19 puntos** respecto a La Tertulia (B), situándose en la franja “Bueno”.



### 4.d A/B Testing
-----
Se presentan los resultados de las tareas clave para cada caso (A y B), evaluando el porcentaje de éxito, tiempo y número de clics. Cada app se analiza dentro de su propio contexto funcional.

#### Caso A – Moda Re-

| Tarea (Moda Re-) | % Éxito | Tiempo medio | Clics medios |
|------------------|---------|--------------|--------------|
| Crear punto de recogida | **100 %** | **48 s** | **7** |
| Buscar puntos en mapa   | **100 %** | **22 s** | 3 |
| Apuntarse a una donación| **75 %**  | **27 s** | 4 |
| **Media general**       | **92 %**  | **32 s** | 4,7 |

#### Caso B – La Tertulia

| Tarea (La Tertulia)        | % Éxito | Tiempo medio | Clics medios |
|----------------------------|---------|--------------|--------------|
| Reservar 2 plazas tertulia | **75 %** | **95 s** | **11** |
| Consultar agenda semanal   | **75 %** | **34 s** | 5 |
| Pagar entrada concierto    | **50 %** | **38 s** | 6 |
| **Media general**          | **67 %** | **56 s** | 7,3 |

Cada app se evalúa sobre sus procesos críticos. Moda Re- logra mayores tasas de éxito y menor esfuerzo en su propio dominio, mientras que La Tertulia muestra cuellos de botella en reserva y pago.

### 4.e Aplicación del método Eye Tracking 
----

Se analiza el recorrido visual de los usuarios mediante mapas de calor. El objetivo es detectar problemas de visibilidad y jerarquía visual en los elementos clave de la interfaz.

- Herramienta: GazeRecorder (Free) — 3 usuarios, 4 pantallas.

| AOI | TTFF (s) | % Usuarios que la vieron | 
|-----|----------|--------------------------|
| Crear un punto de recogida               | **2,1** | 67 % | 
| Hablar por el chat de la cominidad de sevilla             | 1,5  | 100 % | 
| pagar una tertulia       | 5,0  | 33 % | 
| Iniciar sesion de la tertulia | 1,3 | 100 % | 

### 4.f  Usability Report – Caso B (La Tertulia)
----
El informe final de usabilidad sobre la app del grupo compañero, con un resumen de los problemas detectados, su gravedad y recomendaciones para mejorar la experiencia del usuario.

| Severidad | Hallazgo | Evidencia | Recomendación |
|-----------|----------|-----------|---------------|
| **Alta**  | CTA «Reservar» con contraste débil | TTFF 2,1 s; 33 % mis-clicks | Cambiar a color primario `#FF7043` y agrandar |
| **Alta**  | Botón «Pagar» bajo el fold | 67 % no lo encuentran | Mover al área visible tras selección de plazas |
| **Media** | Flujo de reserva requiere 11 clics | 25 % abandono | Introducir autocompletado y resumen en pantalla única |
| **Baja**  | Falta indicar formato del evento (tertulia / concierto) | Feedback cualitativo | Añadir etiquetas de tipo de evento encima del título |

La Tertulia combina oferta cultural atractiva con barreras de visibilidad y pasos redundantes. Priorizar mejora de jerarquía de CTA y reducir el flujo de pago puede añadir ≈ 15 puntos SUS y recortar tiempos un 25 %.

### Reflexión del equipo

Comparar dos dominios distintos (donación vs. reservas) nos obligó a diseñar tareas equivalentes. Vimos que la jerarquía visual y el número de pasos son determinantes: el usuario perdona un mapa que se carga lento si luego puede crear un punto en 2 toques, pero abandona si debe desplazarse para pagar un concierto.

<br>
