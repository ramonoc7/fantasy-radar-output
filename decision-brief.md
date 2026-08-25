# Brief Diario Ligas Fantasy

Datos API: 2026-08-25T11:37:53.208Z
Semana actual: 3

## Objetivo

Tomar decisiones en 5-10 minutos para tres ligas: fichar, vender, pujar y preparar once.

## Peticion lista para ChatGPT/Codex

```text
Revisa LigasFantasyBot/data/latest-api.json, LigasFantasyBot/data/api-report.md y este decision-brief.md.
Para cada liga, dime de forma accionable:
1. FICHAR YA: jugador, precio recomendado, puja maxima y motivo.
2. SOLO SI ESTA BARATO: jugador y precio limite.
3. EVITAR: lesionados, suplentes, sobreprecio o entrenadores bloqueados.
4. VENDER: jugadores de mi plantilla que deberia sacar.
5. ONCE: alineacion recomendada si hay jornada cerca.
Regla clave: no ejecutes compras, ventas, pujas ni cambios de once. Solo aconseja; Ramon confirma manualmente en Fantasy.
No recomiendes vender a nadie solo por 0 puntos actuales. Los puntos actuales pesan poco, especialmente al principio de temporada.
Prioriza titularidad actual, titularidad futura, precio/valor, minutos y titularidades de temporada pasada, rol, competencia, lesion/sancion, numero de pujas, caducidad y necesidades concretas de cada plantilla.
Separa claramente Los Primacos, Fantasmas League y Los Mastuerzos.
```

## Resumen automatico

### Los Primacos

- Saldo: -32.946.402 EUR
- Valor plantilla: 279.872.673 EUR
- Jugadores plantilla: 16
- Mercado jugable: 13
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 36.341.454 EUR
- DEF Nuñez | RCD Espanyol | 5.933.780 EUR
- DEF Koski | Deportivo Alavés | 1.849.904 EUR
- DEF Fran García | Real Betis | 11.671.750 EUR
- DEF Javi Rodríguez | Celta | 9.593.544 EUR
- CEN Kubo | Real Sociedad | 27.861.757 EUR
- CEN Guido Rodríguez | Valencia CF | 24.042.382 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.596.258 EUR
- CEN Martim Neto | Elche CF | 1.642.331 EUR
- CEN Ibañez | Deportivo Alavés | 4.230.449 EUR
- CEN Valverde | Real Madrid | 72.843.452 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.167.798 EUR
- DEL Dolan | RCD Espanyol | 9.168.563 EUR
- DEL R. Brugué | Levante UD | 1.720.571 EUR
- DEL Oyarzabal | Real Sociedad | 62.130.656 EUR
- DEL Hugo Duro | Valencia CF | 8.078.024 EUR

#### Mercado que caduca antes

- DEL Isi | precio 19.918.995 EUR | valor 18.755.543 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 26/8/26, 2:30 | estado injured
- CEN Sergio | precio 1.314.482 EUR | valor 1.314.482 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.245.640 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Bellingham | precio 94.508.594 EUR | valor 94.508.594 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Carreira | precio 6.426.769 EUR | valor 6.426.769 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 994.889 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 63.583.559 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.628.990 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 965.525 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 49.036.895 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Umaru | precio 678.390 EUR | valor 678.390 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Kike García | precio 2.637.726 EUR | valor 2.637.726 EUR | machine | pujas 0 | caduca 26/8/26, 12:46 | estado injured

#### Baratos a revisar

- DEL Umaru | precio 678.390 EUR | valor 678.390 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 965.525 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 994.889 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.245.640 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Sergio | precio 1.314.482 EUR | valor 1.314.482 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.628.990 EUR | machine | pujas 0 | caduca 26/8/26, 12:46

#### Premium a revisar

- CEN Bellingham | precio 94.508.594 EUR | valor 94.508.594 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 63.583.559 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 49.036.895 EUR | machine | pujas 0 | caduca 26/8/26, 12:46

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Kike García: estado injured en mercado.
- Isi: estado injured en mercado.
- V. Rosier: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 39.904.117 EUR
- Valor plantilla: 207.764.192 EUR
- Jugadores plantilla: 14
- Mercado jugable: 24
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.256.635 EUR
- DEF Koski | Deportivo Alavés | 1.849.904 EUR
- DEF Huijsen | Real Madrid | 40.164.511 EUR
- DEF Djene | Getafe CF | 10.376.756 EUR
- CEN Germán V. | Elche CF | 20.548.884 EUR
- CEN Izan M. | Málaga CF | 5.373.087 EUR
- CEN Mario Soriano | RC Deportivo | 28.979.208 EUR
- CEN D. Villares | RC Deportivo | 2.027.430 EUR
- CEN R. Terrats | Getafe CF | 3.739.152 EUR
- CEN Agoumé | Sevilla FC | 5.909.030 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.226.277 EUR
- DEL T. Morente | Elche CF | 1.566.552 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.991.223 EUR
- DEL Isi | Rayo Vallecano | 18.755.543 EUR | estado injured

#### Mercado que caduca antes

- DEF Yuri | precio 12.326.369 EUR | valor 11.453.879 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 25/8/26, 19:39 | estado suspended
- DEL Mbappé | precio 130.241.056 EUR | valor 130.078.148 EUR | rival | ofertas 1 | vende Dynamo de Maghreb FC | caduca 25/8/26, 19:53
- DEL Gordon | precio 66.803.630 EUR | valor 66.803.630 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 590.150 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Fran García | precio 11.671.750 EUR | valor 11.671.750 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.308.444 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Marrero | precio 922.063 EUR | valor 922.063 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.257.953 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 532.266 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.842.835 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Sato | precio 12.491.735 EUR | valor 12.491.735 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Nordin Al-Lal | precio 470.333 EUR | valor 470.333 EUR | machine | pujas 0 | caduca 26/8/26, 10:53

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 470.333 EUR | valor 470.333 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 532.266 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 590.150 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Pastor | precio 800.000 EUR | valor 380.819 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 26/8/26, 12:25
- POR Marrero | precio 922.063 EUR | valor 922.063 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.257.953 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.308.444 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Lunin | precio 1.872.911 EUR | valor 1.840.534 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33
- POR Szczesny | precio 1.942.994 EUR | valor 1.902.384 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 127.238.105 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 0:28
- DEL Mbappé | precio 130.241.056 EUR | valor 130.078.148 EUR | rival | ofertas 1 | vende Dynamo de Maghreb FC | caduca 25/8/26, 19:53
- POR Courtois | precio 79.000.000 EUR | valor 66.324.891 EUR | rival | ofertas 0 | vende alemois | caduca 27/8/26, 21:21
- DEL Gordon | precio 66.803.630 EUR | valor 66.803.630 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 41.770.905 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 27/8/26, 12:41
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.842.835 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 21.994.662 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 16:01

#### Alertas

- F. Calero: estado injured en mercado.
- De Haas: estado injured en mercado.
- Yuri: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 9.590.829 EUR
- Valor plantilla: 230.293.575 EUR
- Jugadores plantilla: 12
- Mercado jugable: 11
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 25.040.360 EUR
- DEF Sergio Gómez | Real Sociedad | 16.687.230 EUR
- DEF Javi Rodríguez | Celta | 9.593.544 EUR
- DEF C. Puga | Málaga CF | 4.910.779 EUR
- DEF Pablo Ramón | R. Racing Club | 762.936 EUR
- DEF Koski | Deportivo Alavés | 1.849.904 EUR
- CEN Germán V. | Elche CF | 20.548.884 EUR
- CEN Javi Guerra | Valencia CF | 24.384.675 EUR
- CEN R. Terrats | Getafe CF | 3.739.152 EUR
- CEN Valverde | Real Madrid | 72.843.452 EUR
- DEL Chupe | Málaga CF | 41.854.635 EUR
- DEL Hugo Duro | Valencia CF | 8.078.024 EUR

#### Mercado que caduca antes

- DEL Bardghji | precio 2.267.159 EUR | valor 2.197.518 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- CEN P. Martínez | precio 7.813.597 EUR | valor 7.610.328 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 698.154 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Dubasin | precio 12.784.410 EUR | valor 12.435.123 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Barzic | precio 690.831 EUR | valor 678.390 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- CEN F. De Jong | precio 20.285.760 EUR | valor 19.654.046 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- DEF Nuñez | precio 5.606.954 EUR | valor 5.933.780 EUR | machine | pujas 1 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 877.360 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.691.201 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF V. Chust | precio 5.620.791 EUR | valor 5.695.688 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Bartra | precio 27.720.326 EUR | valor 28.514.361 EUR | machine | pujas 1 | caduca 25/8/26, 22:10

#### Baratos a revisar

- DEF Barzic | precio 690.831 EUR | valor 678.390 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 698.154 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 877.360 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Premium a revisar

- DEF Bartra | precio 27.720.326 EUR | valor 28.514.361 EUR | machine | pujas 1 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.691.201 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Alertas

- Bardghji: estado injured en mercado.
- F. De Jong: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

