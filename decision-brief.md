# Brief Diario Ligas Fantasy

Datos API: 2026-08-25T14:58:27.703Z
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
- Valor plantilla: 279.665.715 EUR
- Jugadores plantilla: 16
- Mercado jugable: 13
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 36.306.255 EUR
- DEF Nuñez | RCD Espanyol | 5.925.483 EUR
- DEF Koski | Deportivo Alavés | 1.846.512 EUR
- DEF Fran García | Real Betis | 11.655.177 EUR
- DEF Javi Rodríguez | Celta | 9.582.510 EUR
- CEN Kubo | Real Sociedad | 27.842.322 EUR
- CEN Guido Rodríguez | Valencia CF | 24.019.590 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.593.363 EUR
- CEN Martim Neto | Elche CF | 1.641.507 EUR
- CEN Ibañez | Deportivo Alavés | 4.225.407 EUR
- CEN Valverde | Real Madrid | 72.799.916 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.167.383 EUR
- DEL Dolan | RCD Espanyol | 9.157.381 EUR
- DEL R. Brugué | Levante UD | 1.720.165 EUR
- DEL Oyarzabal | Real Sociedad | 62.106.491 EUR
- DEL Hugo Duro | Valencia CF | 8.076.253 EUR

#### Mercado que caduca antes

- DEL Isi | precio 19.918.995 EUR | valor 18.753.529 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 26/8/26, 2:30 | estado injured
- CEN Sergio | precio 1.314.482 EUR | valor 1.312.515 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.245.342 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Bellingham | precio 94.508.594 EUR | valor 94.432.072 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Carreira | precio 6.426.769 EUR | valor 6.421.453 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 994.326 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 63.526.855 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.626.538 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 965.300 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 48.988.995 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Umaru | precio 678.390 EUR | valor 678.166 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Kike García | precio 2.637.726 EUR | valor 2.637.366 EUR | machine | pujas 0 | caduca 26/8/26, 12:46 | estado injured

#### Baratos a revisar

- DEL Umaru | precio 678.390 EUR | valor 678.166 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 965.300 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 994.326 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.245.342 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Sergio | precio 1.314.482 EUR | valor 1.312.515 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.626.538 EUR | machine | pujas 0 | caduca 26/8/26, 12:46

#### Premium a revisar

- CEN Bellingham | precio 94.508.594 EUR | valor 94.432.072 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 63.526.855 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 48.988.995 EUR | machine | pujas 0 | caduca 26/8/26, 12:46

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Kike García: estado injured en mercado.
- Isi: estado injured en mercado.
- V. Rosier: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 39.904.117 EUR
- Valor plantilla: 207.624.873 EUR
- Jugadores plantilla: 14
- Mercado jugable: 24
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.234.198 EUR
- DEF Koski | Deportivo Alavés | 1.846.512 EUR
- DEF Huijsen | Real Madrid | 40.128.664 EUR
- DEF Djene | Getafe CF | 10.363.871 EUR
- CEN Germán V. | Elche CF | 20.542.089 EUR
- CEN Izan M. | Málaga CF | 5.371.600 EUR
- CEN Mario Soriano | RC Deportivo | 28.961.429 EUR
- CEN D. Villares | RC Deportivo | 2.026.972 EUR
- CEN R. Terrats | Getafe CF | 3.734.008 EUR
- CEN Agoumé | Sevilla FC | 5.902.209 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.219.073 EUR
- DEL T. Morente | Elche CF | 1.566.110 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.974.609 EUR
- DEL Isi | Rayo Vallecano | 18.753.529 EUR | estado injured

#### Mercado que caduca antes

- DEF Yuri | precio 12.326.369 EUR | valor 11.452.278 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 25/8/26, 19:39 | estado suspended
- DEL Mbappé | precio 130.241.056 EUR | valor 130.006.520 EUR | rival | ofertas 1 | vende Dynamo de Maghreb FC | caduca 25/8/26, 19:53
- DEL Gordon | precio 66.803.630 EUR | valor 66.795.866 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 589.925 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Fran García | precio 11.671.750 EUR | valor 11.655.177 EUR | machine | pujas 2 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.308.219 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Marrero | precio 922.063 EUR | valor 921.826 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.257.387 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 531.695 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.821.261 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Sato | precio 12.491.735 EUR | valor 12.490.283 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Nordin Al-Lal | precio 470.333 EUR | valor 470.108 EUR | machine | pujas 0 | caduca 26/8/26, 10:53

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 470.333 EUR | valor 470.108 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 531.695 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 589.925 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Pastor | precio 800.000 EUR | valor 380.594 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 26/8/26, 12:25
- POR Marrero | precio 922.063 EUR | valor 921.826 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.257.387 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.308.219 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Lunin | precio 1.872.911 EUR | valor 1.839.896 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33
- POR Szczesny | precio 1.942.994 EUR | valor 1.901.904 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 127.169.397 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 0:28
- DEL Mbappé | precio 130.241.056 EUR | valor 130.006.520 EUR | rival | ofertas 1 | vende Dynamo de Maghreb FC | caduca 25/8/26, 19:53
- POR Courtois | precio 79.000.000 EUR | valor 66.285.191 EUR | rival | ofertas 0 | vende alemois | caduca 27/8/26, 21:21
- DEL Gordon | precio 66.803.630 EUR | valor 66.795.866 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 41.761.399 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 27/8/26, 12:41
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.821.261 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 21.989.472 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 16:01

#### Alertas

- F. Calero: estado injured en mercado.
- De Haas: estado injured en mercado.
- Yuri: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 9.590.829 EUR
- Valor plantilla: 230.163.650 EUR
- Jugadores plantilla: 12
- Mercado jugable: 11
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 25.013.097 EUR
- DEF Sergio Gómez | Real Sociedad | 16.681.074 EUR
- DEF Javi Rodríguez | Celta | 9.582.510 EUR
- DEF C. Puga | Málaga CF | 4.908.305 EUR
- DEF Pablo Ramón | R. Racing Club | 761.366 EUR
- DEF Koski | Deportivo Alavés | 1.846.512 EUR
- CEN Germán V. | Elche CF | 20.542.089 EUR
- CEN Javi Guerra | Valencia CF | 24.373.101 EUR
- CEN R. Terrats | Getafe CF | 3.734.008 EUR
- CEN Valverde | Real Madrid | 72.799.916 EUR
- DEL Chupe | Málaga CF | 41.845.419 EUR
- DEL Hugo Duro | Valencia CF | 8.076.253 EUR

#### Mercado que caduca antes

- DEL Bardghji | precio 2.267.159 EUR | valor 2.197.205 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- CEN P. Martínez | precio 7.813.597 EUR | valor 7.608.711 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 697.929 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Dubasin | precio 12.784.410 EUR | valor 12.432.713 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Barzic | precio 690.831 EUR | valor 678.166 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- CEN F. De Jong | precio 20.285.760 EUR | valor 19.651.386 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- DEF Nuñez | precio 5.606.954 EUR | valor 5.925.483 EUR | machine | pujas 2 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 877.135 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.680.359 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF V. Chust | precio 5.620.791 EUR | valor 5.691.155 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Bartra | precio 27.720.326 EUR | valor 28.485.752 EUR | machine | pujas 1 | caduca 25/8/26, 22:10

#### Baratos a revisar

- DEF Barzic | precio 690.831 EUR | valor 678.166 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 697.929 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 877.135 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Premium a revisar

- DEF Bartra | precio 27.720.326 EUR | valor 28.485.752 EUR | machine | pujas 1 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.680.359 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Alertas

- Bardghji: estado injured en mercado.
- F. De Jong: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

