# Brief Diario Ligas Fantasy

Datos API: 2026-08-26T04:51:29.073Z
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
- Valor plantilla: 281.574.239 EUR
- Jugadores plantilla: 16
- Mercado jugable: 19
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 37.088.167 EUR
- DEF Nuñez | RCD Espanyol | 6.217.215 EUR
- DEF Koski | Deportivo Alavés | 1.990.232 EUR
- DEF Fran García | Real Betis | 12.329.561 EUR
- DEF Javi Rodríguez | Celta | 9.903.779 EUR
- CEN Kubo | Real Sociedad | 27.986.814 EUR
- CEN Guido Rodríguez | Valencia CF | 24.520.433 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.745.975 EUR
- CEN Martim Neto | Elche CF | 1.624.652 EUR
- CEN Ibañez | Deportivo Alavés | 4.387.750 EUR
- CEN Valverde | Real Madrid | 72.389.341 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.194.987 EUR
- DEL Dolan | RCD Espanyol | 9.577.591 EUR
- DEL R. Brugué | Levante UD | 1.705.123 EUR
- DEL Oyarzabal | Real Sociedad | 61.029.593 EUR
- DEL Hugo Duro | Valencia CF | 7.883.026 EUR

#### Mercado que caduca antes

- CEN Sergio | precio 1.314.482 EUR | valor 1.410.523 EUR | machine | pujas 2 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.215.845 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Bellingham | precio 94.508.594 EUR | valor 95.316.537 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Carreira | precio 6.426.769 EUR | valor 6.477.723 EUR | machine | pujas 1 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 1.003.694 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 64.607.793 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.676.220 EUR | machine | pujas 1 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 941.285 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 50.306.563 EUR | machine | pujas 1 | caduca 26/8/26, 12:46
- DEL Umaru | precio 678.390 EUR | valor 665.637 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Kike García | precio 2.637.726 EUR | valor 2.552.741 EUR | machine | pujas 0 | caduca 26/8/26, 12:46 | estado injured
- DEF V. Rosier | precio 5.000.000 EUR | valor 4.101.506 EUR | rival | ofertas 1 | vende leomaldonado10 | caduca 28/8/26, 10:25 | estado injured

#### Baratos a revisar

- DEL Umaru | precio 678.390 EUR | valor 665.637 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Valentini | precio 965.525 EUR | valor 941.285 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Saba Sazonov | precio 994.889 EUR | valor 1.003.694 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN H. González | precio 1.245.640 EUR | valor 1.215.845 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- CEN Sergio | precio 1.314.482 EUR | valor 1.410.523 EUR | machine | pujas 2 | caduca 26/8/26, 12:46
- DEL Peque | precio 2.628.990 EUR | valor 2.676.220 EUR | machine | pujas 1 | caduca 26/8/26, 12:46

#### Premium a revisar

- CEN Bellingham | precio 94.508.594 EUR | valor 95.316.537 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEL Pepe | precio 63.583.559 EUR | valor 64.607.793 EUR | machine | pujas 0 | caduca 26/8/26, 12:46
- DEF Eric | precio 49.036.895 EUR | valor 50.306.563 EUR | machine | pujas 1 | caduca 26/8/26, 12:46
- CEN Kubo | precio 27.842.322 EUR | valor 27.986.814 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 29/8/26, 0:14
- CEN Guido Rodríguez | precio 24.019.590 EUR | valor 24.520.433 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 29/8/26, 0:14

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Kike García: estado injured en mercado.
- Vivian: estado injured en mercado.
- V. Rosier: estado injured en mercado.
- Manuel Fernández: estado out_of_league en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 39.904.117 EUR
- Valor plantilla: 208.168.353 EUR
- Jugadores plantilla: 14
- Mercado jugable: 26
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.006.685 EUR
- DEF Koski | Deportivo Alavés | 1.990.232 EUR
- DEF Huijsen | Real Madrid | 40.852.244 EUR
- DEF Djene | Getafe CF | 10.923.694 EUR
- CEN Germán V. | Elche CF | 20.154.034 EUR
- CEN Izan M. | Málaga CF | 5.290.417 EUR
- CEN Mario Soriano | RC Deportivo | 28.627.468 EUR
- CEN D. Villares | RC Deportivo | 1.983.113 EUR
- CEN R. Terrats | Getafe CF | 3.941.037 EUR
- CEN Agoumé | Sevilla FC | 6.066.565 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.399.577 EUR
- DEL T. Morente | Elche CF | 1.531.691 EUR
- DEL Iñigo Vicente | R. Racing Club | 21.210.070 EUR
- DEL Isi | Rayo Vallecano | 18.191.526 EUR | estado injured

#### Mercado que caduca antes

- DEL Gordon | precio 66.803.630 EUR | valor 66.714.260 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 580.925 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Fran García | precio 11.671.750 EUR | valor 12.329.561 EUR | machine | pujas 4 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.270.487 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- POR Marrero | precio 922.063 EUR | valor 900.039 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.236.545 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 543.098 EUR | machine | pujas 2 | caduca 26/8/26, 10:53
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.752.569 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Sato | precio 12.491.735 EUR | valor 12.241.138 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Nordin Al-Lal | precio 470.333 EUR | valor 465.901 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF F. Calero | precio 2.177.410 EUR | valor 2.109.840 EUR | machine | pujas 0 | caduca 26/8/26, 10:53 | estado injured
- DEF Pastor | precio 800.000 EUR | valor 379.967 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 26/8/26, 12:25

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 470.333 EUR | valor 465.901 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF D. Martínez | precio 532.266 EUR | valor 543.098 EUR | machine | pujas 2 | caduca 26/8/26, 10:53
- POR Galdin | precio 590.150 EUR | valor 580.925 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Pastor | precio 800.000 EUR | valor 379.967 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 26/8/26, 12:25
- POR Marrero | precio 922.063 EUR | valor 900.039 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- CEN Iker Muñoz | precio 1.167.383 EUR | valor 1.194.987 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 28/8/26, 17:03
- DEL Arnau Ortiz | precio 1.257.953 EUR | valor 1.236.545 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEF Johaneko | precio 1.308.444 EUR | valor 1.270.487 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL T. Morente | precio 1.566.110 EUR | valor 1.531.691 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:47
- POR Lunin | precio 1.872.911 EUR | valor 1.808.011 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 126.467.655 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 0:28
- POR Courtois | precio 79.000.000 EUR | valor 66.206.568 EUR | rival | ofertas 0 | vende alemois | caduca 27/8/26, 21:21
- DEL Mikautadze | precio 68.270.452 EUR | valor 69.651.107 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 28/8/26, 17:05
- DEL Gordon | precio 66.803.630 EUR | valor 66.714.260 EUR | machine | pujas 0 | caduca 26/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 40.811.902 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 28/8/26, 20:12
- POR Ionut Radu | precio 35.842.835 EUR | valor 35.752.569 EUR | machine | pujas 1 | caduca 26/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 21.384.105 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 16:01
- CEN Germán V. | precio 20.542.089 EUR | valor 20.154.034 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:46

#### Alertas

- F. Calero: estado injured en mercado.
- Isi: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 9.590.829 EUR
- Valor plantilla: 229.695.839 EUR
- Jugadores plantilla: 12
- Mercado jugable: 15
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 25.899.108 EUR
- DEF Sergio Gómez | Real Sociedad | 16.387.593 EUR
- DEF Javi Rodríguez | Celta | 9.903.779 EUR
- DEF C. Puga | Málaga CF | 4.914.501 EUR
- DEF Pablo Ramón | R. Racing Club | 868.609 EUR
- DEF Koski | Deportivo Alavés | 1.990.232 EUR
- CEN Germán V. | Elche CF | 20.154.034 EUR
- CEN Javi Guerra | Valencia CF | 24.117.468 EUR
- CEN R. Terrats | Getafe CF | 3.941.037 EUR
- CEN Valverde | Real Madrid | 72.389.341 EUR
- DEL Chupe | Málaga CF | 41.247.111 EUR
- DEL Hugo Duro | Valencia CF | 7.883.026 EUR

#### Mercado que caduca antes

- CEN Buonanotte | precio 5.613.729 EUR | valor 5.480.785 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR Leo Román | precio 40.472.701 EUR | valor 40.296.895 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Dela | precio 11.251.772 EUR | valor 11.240.358 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEF Costa | precio 1.008.872 EUR | valor 983.114 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Yoel Lago | precio 677.391 EUR | valor 770.500 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEL Gordon | precio 66.795.866 EUR | valor 66.714.260 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR A. Fortuño | precio 492.645 EUR | valor 487.536 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEL Abdelkarim | precio 3.801.390 EUR | valor 3.808.099 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Barrios | precio 47.420.966 EUR | valor 47.911.505 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Guridi | precio 6.986.094 EUR | valor 7.095.771 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Mantilla | precio 2.424.504 EUR | valor 2.379.856 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Beitia | precio 492.587 EUR | valor 487.481 EUR | machine | pujas 0 | caduca 26/8/26, 22:10

#### Baratos a revisar

- DEF Beitia | precio 492.587 EUR | valor 487.481 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR A. Fortuño | precio 492.645 EUR | valor 487.536 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Yoel Lago | precio 677.391 EUR | valor 770.500 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEF Costa | precio 1.008.872 EUR | valor 983.114 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Mantilla | precio 2.424.504 EUR | valor 2.379.856 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEL Abdelkarim | precio 3.801.390 EUR | valor 3.808.099 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF C. Puga | precio 4.908.305 EUR | valor 4.914.501 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:13

#### Premium a revisar

- DEL Gordon | precio 66.795.866 EUR | valor 66.714.260 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Barrios | precio 47.420.966 EUR | valor 47.911.505 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR Leo Román | precio 40.472.701 EUR | valor 40.296.895 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Germán V. | precio 20.542.089 EUR | valor 20.154.034 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:22

#### Alertas

- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

