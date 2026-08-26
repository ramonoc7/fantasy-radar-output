# Brief Diario Ligas Fantasy

Datos API: 2026-08-26T11:39:14.058Z
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
- Mercado jugable: 17
- Entrenadores ignorados: 1
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

- CEN Gerenabarrena | precio 1.149.297 EUR | valor 1.149.297 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Herrera | precio 3.323.516 EUR | valor 3.323.516 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEL Marcos | precio 1.082.525 EUR | valor 1.082.525 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Requena | precio 1.612.539 EUR | valor 1.612.539 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEF Gayá | precio 10.466.363 EUR | valor 10.466.363 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Guillén | precio 3.862.148 EUR | valor 3.862.148 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN O. Rey | precio 849.670 EUR | valor 849.670 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Gorka Carrera | precio 664.893 EUR | valor 664.893 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEL Arnau Ortiz | precio 1.236.545 EUR | valor 1.236.545 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Julián Alvarez | precio 62.517.017 EUR | valor 62.517.017 EUR | machine | pujas 0 | caduca 27/8/26, 12:46 | estado doubtful
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.550 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Kang-In Lee | precio 48.966.230 EUR | valor 48.966.230 EUR | machine | pujas 1 | caduca 27/8/26, 12:46

#### Baratos a revisar

- DEL Gorka Carrera | precio 664.893 EUR | valor 664.893 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN O. Rey | precio 849.670 EUR | valor 849.670 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Marcos | precio 1.082.525 EUR | valor 1.082.525 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Gerenabarrena | precio 1.149.297 EUR | valor 1.149.297 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEL Arnau Ortiz | precio 1.236.545 EUR | valor 1.236.545 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- CEN Requena | precio 1.612.539 EUR | valor 1.612.539 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Herrera | precio 3.323.516 EUR | valor 3.323.516 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.550 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Guillén | precio 3.862.148 EUR | valor 3.862.148 EUR | machine | pujas 0 | caduca 27/8/26, 12:46

#### Premium a revisar

- CEN Kang-In Lee | precio 48.966.230 EUR | valor 48.966.230 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- CEN Kubo | precio 27.842.322 EUR | valor 27.986.814 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 29/8/26, 0:14
- CEN Guido Rodríguez | precio 24.019.590 EUR | valor 24.520.433 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 29/8/26, 0:14

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Julián Alvarez: estado doubtful en mercado.
- V. Rosier: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 26.224.320 EUR
- Valor plantilla: 220.497.914 EUR
- Jugadores plantilla: 15
- Mercado jugable: 24
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.006.685 EUR
- DEF Djene | Getafe CF | 10.923.694 EUR
- DEF Huijsen | Real Madrid | 40.852.244 EUR
- DEF Koski | Deportivo Alavés | 1.990.232 EUR
- DEF Fran García | Real Betis | 12.329.561 EUR
- CEN Mario Soriano | RC Deportivo | 28.627.468 EUR
- CEN D. Villares | RC Deportivo | 1.983.113 EUR
- CEN Izan M. | Málaga CF | 5.290.417 EUR
- CEN Germán V. | Elche CF | 20.154.034 EUR
- CEN R. Terrats | Getafe CF | 3.941.037 EUR
- CEN Agoumé | Sevilla FC | 6.066.565 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.399.577 EUR
- DEL T. Morente | Elche CF | 1.531.691 EUR
- DEL Iñigo Vicente | R. Racing Club | 21.210.070 EUR
- DEL Isi | Rayo Vallecano | 18.191.526 EUR | estado injured

#### Mercado que caduca antes

- DEF Aihen | precio 1.104.624 EUR | valor 1.104.624 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Yeray | precio 5.791.820 EUR | valor 5.791.820 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Francho | precio 2.708.372 EUR | valor 2.708.372 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Moleiro | precio 59.912.184 EUR | valor 59.912.184 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Mandi | precio 8.055.512 EUR | valor 8.055.512 EUR | machine | pujas 2 | caduca 27/8/26, 10:53
- DEF Cabrera | precio 13.056.216 EUR | valor 13.056.216 EUR | machine | pujas 0 | caduca 27/8/26, 10:53 | estado suspended
- DEF Salinas | precio 886.022 EUR | valor 886.022 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Xanet Olaiz | precio 529.715 EUR | valor 529.715 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Oyarzabal | precio 61.029.593 EUR | valor 61.029.593 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.550 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Sucic | precio 3.547.132 EUR | valor 3.547.132 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- POR Lunin | precio 1.872.911 EUR | valor 1.808.011 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33

#### Baratos a revisar

- DEF Xanet Olaiz | precio 529.715 EUR | valor 529.715 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Salinas | precio 886.022 EUR | valor 886.022 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Aihen | precio 1.104.624 EUR | valor 1.104.624 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Iker Muñoz | precio 1.167.383 EUR | valor 1.194.987 EUR | rival | ofertas 2 | vende Mynavo Kyiv | caduca 28/8/26, 17:03
- DEL T. Morente | precio 1.566.110 EUR | valor 1.531.691 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 28/8/26, 23:47
- POR Lunin | precio 1.872.911 EUR | valor 1.808.011 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33
- CEN Francho | precio 2.708.372 EUR | valor 2.708.372 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Sucic | precio 3.547.132 EUR | valor 3.547.132 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.550 EUR | machine | pujas 0 | caduca 27/8/26, 10:53

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 126.467.655 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 0:28
- DEL Mikautadze | precio 68.270.452 EUR | valor 69.651.107 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 28/8/26, 17:05
- DEL Oyarzabal | precio 61.029.593 EUR | valor 61.029.593 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 40.811.902 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 20:12
- CEN Moleiro | precio 59.912.184 EUR | valor 59.912.184 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 21.384.105 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 16:01
- CEN Germán V. | precio 20.542.089 EUR | valor 20.154.034 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 28/8/26, 23:46

#### Alertas

- Cabrera: estado suspended en mercado.
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

