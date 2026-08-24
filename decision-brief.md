# Brief Diario Ligas Fantasy

Datos API: 2026-08-24T21:39:15.710Z
Semana actual: 2

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

- Saldo: 34.111.397 EUR
- Valor plantilla: 204.173.521 EUR
- Jugadores plantilla: 15
- Mercado jugable: 13
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 35.417.272 EUR
- DEF Nuñez | RCD Espanyol | 5.606.954 EUR
- DEF Koski | Deportivo Alavés | 1.690.987 EUR
- DEF Fran García | Real Betis | 10.975.391 EUR
- DEF Javi Rodríguez | Celta | 9.237.650 EUR
- CEN Guido Rodríguez | Valencia CF | 23.486.678 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.456.096 EUR
- CEN Kubo | Real Sociedad | 27.571.369 EUR
- CEN Martim Neto | Elche CF | 1.653.565 EUR
- CEN Ibañez | Deportivo Alavés | 4.051.893 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.187.249 EUR
- DEL Dolan | RCD Espanyol | 8.763.759 EUR
- DEL R. Brugué | Levante UD | 1.763.949 EUR
- DEL Oyarzabal | Real Sociedad | 63.018.935 EUR
- DEL Hugo Duro | Valencia CF | 8.291.774 EUR

#### Mercado que caduca antes

- POR Marrero | precio 943.972 EUR | valor 943.828 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN Marc Roca | precio 5.609.002 EUR | valor 5.605.417 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- POR Sergio Herrera | precio 36.946.516 EUR | valor 36.938.296 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Gerard Martín | precio 39.508.746 EUR | valor 39.492.824 EUR | machine | pujas 1 | caduca 25/8/26, 12:46
- POR Swiderski | precio 543.485 EUR | valor 543.347 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN D. Villares | precio 2.079.968 EUR | valor 2.079.694 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN Francho | precio 2.641.403 EUR | valor 2.640.935 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Rüdiger | precio 29.476.040 EUR | valor 29.469.157 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN Moleiro | precio 62.002.118 EUR | valor 61.989.445 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Xanet Olaiz | precio 543.485 EUR | valor 543.347 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN Valverde | precio 72.882.912 EUR | valor 72.857.790 EUR | machine | pujas 1 | caduca 25/8/26, 12:46
- DEF J. Ives Valou | precio 542.949 EUR | valor 542.810 EUR | machine | pujas 0 | caduca 25/8/26, 12:46

#### Baratos a revisar

- DEF J. Ives Valou | precio 542.949 EUR | valor 542.810 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- POR Swiderski | precio 543.485 EUR | valor 543.347 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Xanet Olaiz | precio 543.485 EUR | valor 543.347 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- POR Marrero | precio 943.972 EUR | valor 943.828 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN D. Villares | precio 2.079.968 EUR | valor 2.079.694 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- CEN Francho | precio 2.641.403 EUR | valor 2.640.935 EUR | machine | pujas 0 | caduca 25/8/26, 12:46

#### Premium a revisar

- CEN Valverde | precio 72.882.912 EUR | valor 72.857.790 EUR | machine | pujas 1 | caduca 25/8/26, 12:46
- CEN Moleiro | precio 62.002.118 EUR | valor 61.989.445 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Gerard Martín | precio 39.508.746 EUR | valor 39.492.824 EUR | machine | pujas 1 | caduca 25/8/26, 12:46
- POR Sergio Herrera | precio 36.946.516 EUR | valor 36.938.296 EUR | machine | pujas 0 | caduca 25/8/26, 12:46
- DEF Rüdiger | precio 29.476.040 EUR | valor 29.469.157 EUR | machine | pujas 0 | caduca 25/8/26, 12:46

#### Alertas

- Isi: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 34.504.117 EUR
- Valor plantilla: 206.516.392 EUR
- Jugadores plantilla: 14
- Mercado jugable: 26
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.355.184 EUR
- DEF Koski | Deportivo Alavés | 1.690.987 EUR
- DEF Huijsen | Real Madrid | 39.252.353 EUR
- DEF Djene | Getafe CF | 9.889.886 EUR
- CEN Germán V. | Elche CF | 20.938.838 EUR
- CEN Izan M. | Málaga CF | 5.492.332 EUR
- CEN Mario Soriano | RC Deportivo | 28.955.408 EUR
- CEN D. Villares | RC Deportivo | 2.079.694 EUR
- CEN R. Terrats | Getafe CF | 3.512.950 EUR
- CEN Agoumé | Sevilla FC | 5.688.045 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.030.249 EUR
- DEL T. Morente | Elche CF | 1.601.364 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.696.780 EUR
- DEL Isi | Rayo Vallecano | 19.332.322 EUR | estado injured

#### Mercado que caduca antes

- POR Diego Conde | precio 2.547.767 EUR | valor 2.546.541 EUR | machine | pujas 0 | caduca 25/8/26, 10:53 | estado injured
- DEL B. Iglesias | precio 24.731.038 EUR | valor 24.703.127 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Dumfries | precio 50.094.713 EUR | valor 50.039.536 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Kounde | precio 39.058.979 EUR | valor 38.992.764 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Javi Rueda | precio 4.281.263 EUR | valor 4.277.283 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Barzic | precio 691.575 EUR | valor 690.831 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEL Robbie Ure | precio 12.471.439 EUR | valor 12.445.215 EUR | machine | pujas 2 | caduca 25/8/26, 10:53
- POR Joan García | precio 71.467.652 EUR | valor 71.347.095 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- POR Padilla | precio 1.253.700 EUR | valor 1.252.923 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- POR Ryan | precio 13.397.730 EUR | valor 13.369.964 EUR | machine | pujas 2 | caduca 25/8/26, 10:53
- DEL Ibra Drj | precio 599.658 EUR | valor 598.914 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- CEN Bardeli | precio 3.357.629 EUR | valor 3.355.940 EUR | machine | pujas 0 | caduca 25/8/26, 10:53

#### Baratos a revisar

- DEL Ibra Drj | precio 599.658 EUR | valor 598.914 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Barzic | precio 691.575 EUR | valor 690.831 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Pastor | precio 800.000 EUR | valor 380.861 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 26/8/26, 12:25
- POR Padilla | precio 1.253.700 EUR | valor 1.252.923 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- POR Lunin | precio 1.872.911 EUR | valor 1.872.911 EUR | rival | ofertas 0 | vende Rafishh | caduca 27/8/26, 15:33
- POR Szczesny | precio 1.942.994 EUR | valor 1.942.994 EUR | rival | ofertas 0 | vende Rafishh | caduca 27/8/26, 15:33
- CEN Bardeli | precio 3.357.629 EUR | valor 3.355.940 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Javi Rueda | precio 4.281.263 EUR | valor 4.277.283 EUR | machine | pujas 0 | caduca 25/8/26, 10:53

#### Premium a revisar

- DEL Mbappé | precio 130.241.056 EUR | valor 130.457.709 EUR | rival | ofertas 1 | vende Dynamo de Maghreb FC | caduca 25/8/26, 19:53
- POR Courtois | precio 79.000.000 EUR | valor 66.160.365 EUR | rival | ofertas 0 | vende alemois | caduca 27/8/26, 21:21
- POR Joan García | precio 71.467.652 EUR | valor 71.347.095 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 42.842.468 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 27/8/26, 12:41
- DEF Dumfries | precio 50.094.713 EUR | valor 50.039.536 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEF Kounde | precio 39.058.979 EUR | valor 38.992.764 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEL B. Iglesias | precio 24.731.038 EUR | valor 24.703.127 EUR | machine | pujas 0 | caduca 25/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 22.549.120 EUR | rival | ofertas 0 | vende Rafishh | caduca 27/8/26, 16:01

#### Alertas

- Diego Conde: estado injured en mercado.
- De Haas: estado injured en mercado.
- Yuri: estado suspended en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 3.390.829 EUR
- Valor plantilla: 230.736.483 EUR
- Jugadores plantilla: 12
- Mercado jugable: 11
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 24.103.158 EUR
- DEF Sergio Gómez | Real Sociedad | 16.949.363 EUR
- DEF Javi Rodríguez | Celta | 9.237.650 EUR
- DEF C. Puga | Málaga CF | 4.941.328 EUR
- DEF Pablo Ramón | R. Racing Club | 666.274 EUR
- DEF Koski | Deportivo Alavés | 1.690.987 EUR
- CEN Germán V. | Elche CF | 20.938.838 EUR
- CEN Javi Guerra | Valencia CF | 24.586.243 EUR
- CEN R. Terrats | Getafe CF | 3.512.950 EUR
- CEN Valverde | Real Madrid | 72.857.790 EUR
- DEL Chupe | Málaga CF | 42.960.128 EUR
- DEL Hugo Duro | Valencia CF | 8.291.774 EUR

#### Mercado que caduca antes

- DEL Bardghji | precio 2.267.159 EUR | valor 2.267.159 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- CEN P. Martínez | precio 7.813.597 EUR | valor 7.813.597 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 711.418 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Dubasin | precio 12.784.410 EUR | valor 12.784.410 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Barzic | precio 690.831 EUR | valor 690.831 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- CEN F. De Jong | precio 20.285.760 EUR | valor 20.285.760 EUR | machine | pujas 0 | caduca 25/8/26, 22:10 | estado injured
- DEF Nuñez | precio 5.606.954 EUR | valor 5.606.954 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 898.091 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.965.234 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF V. Chust | precio 5.620.791 EUR | valor 5.620.791 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Bartra | precio 27.720.326 EUR | valor 27.720.326 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Baratos a revisar

- DEF Barzic | precio 690.831 EUR | valor 690.831 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEF Cardoso | precio 711.418 EUR | valor 711.418 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Alexis Ciria | precio 898.091 EUR | valor 898.091 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Premium a revisar

- DEF Bartra | precio 27.720.326 EUR | valor 27.720.326 EUR | machine | pujas 0 | caduca 25/8/26, 22:10
- DEL Iñaki Williams | precio 26.965.234 EUR | valor 26.965.234 EUR | machine | pujas 0 | caduca 25/8/26, 22:10

#### Alertas

- Bardghji: estado injured en mercado.
- F. De Jong: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

