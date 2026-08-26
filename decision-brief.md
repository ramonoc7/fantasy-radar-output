# Brief Diario Ligas Fantasy

Datos API: 2026-08-26T16:32:57.003Z
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
- Valor plantilla: 281.564.571 EUR
- Jugadores plantilla: 16
- Mercado jugable: 17
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 37.086.219 EUR
- DEF Nuñez | RCD Espanyol | 6.216.925 EUR
- DEF Koski | Deportivo Alavés | 1.989.948 EUR
- DEF Fran García | Real Betis | 12.328.936 EUR
- DEF Javi Rodríguez | Celta | 9.903.176 EUR
- CEN Kubo | Real Sociedad | 27.986.125 EUR
- CEN Guido Rodríguez | Valencia CF | 24.519.633 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.745.916 EUR
- CEN Martim Neto | Elche CF | 1.624.626 EUR
- CEN Ibañez | Deportivo Alavés | 4.387.569 EUR
- CEN Valverde | Real Madrid | 72.386.574 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.194.923 EUR
- DEL Dolan | RCD Espanyol | 9.577.160 EUR
- DEL R. Brugué | Levante UD | 1.705.063 EUR
- DEL Oyarzabal | Real Sociedad | 61.028.823 EUR
- DEL Hugo Duro | Valencia CF | 7.882.955 EUR

#### Mercado que caduca antes

- CEN Gerenabarrena | precio 1.149.297 EUR | valor 1.149.277 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Herrera | precio 3.323.516 EUR | valor 3.323.385 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Marcos | precio 1.082.525 EUR | valor 1.082.516 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Requena | precio 1.612.539 EUR | valor 1.612.531 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEF Gayá | precio 10.466.363 EUR | valor 10.466.044 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Guillén | precio 3.862.148 EUR | valor 3.862.124 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN O. Rey | precio 849.670 EUR | valor 849.631 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Gorka Carrera | precio 664.893 EUR | valor 664.885 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEL Arnau Ortiz | precio 1.236.545 EUR | valor 1.236.529 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Julián Alvarez | precio 62.517.017 EUR | valor 62.516.430 EUR | machine | pujas 0 | caduca 27/8/26, 12:46 | estado doubtful
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.514 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Kang-In Lee | precio 48.966.230 EUR | valor 48.964.158 EUR | machine | pujas 1 | caduca 27/8/26, 12:46

#### Baratos a revisar

- DEL Gorka Carrera | precio 664.893 EUR | valor 664.885 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN O. Rey | precio 849.670 EUR | valor 849.631 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- DEL Marcos | precio 1.082.525 EUR | valor 1.082.516 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Gerenabarrena | precio 1.149.297 EUR | valor 1.149.277 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- DEL Arnau Ortiz | precio 1.236.545 EUR | valor 1.236.529 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- CEN Requena | precio 1.612.539 EUR | valor 1.612.531 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Herrera | precio 3.323.516 EUR | valor 3.323.385 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.514 EUR | machine | pujas 0 | caduca 27/8/26, 12:46
- CEN Guillén | precio 3.862.148 EUR | valor 3.862.124 EUR | machine | pujas 0 | caduca 27/8/26, 12:46

#### Premium a revisar

- CEN Kang-In Lee | precio 48.966.230 EUR | valor 48.964.158 EUR | machine | pujas 1 | caduca 27/8/26, 12:46
- CEN Kubo | precio 27.842.322 EUR | valor 27.986.125 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 29/8/26, 0:14
- CEN Guido Rodríguez | precio 24.019.590 EUR | valor 24.519.633 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 29/8/26, 0:14

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Julián Alvarez: estado doubtful en mercado.
- V. Rosier: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 26.224.320 EUR
- Valor plantilla: 220.491.948 EUR
- Jugadores plantilla: 15
- Mercado jugable: 27
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.005.929 EUR
- DEF Djene | Getafe CF | 10.922.775 EUR
- DEF Huijsen | Real Madrid | 40.850.969 EUR
- DEF Koski | Deportivo Alavés | 1.989.948 EUR
- DEF Fran García | Real Betis | 12.328.936 EUR
- CEN Mario Soriano | RC Deportivo | 28.627.016 EUR
- CEN D. Villares | RC Deportivo | 1.983.085 EUR
- CEN Izan M. | Málaga CF | 5.290.343 EUR
- CEN Germán V. | Elche CF | 20.153.565 EUR
- CEN R. Terrats | Getafe CF | 3.940.650 EUR
- CEN Agoumé | Sevilla FC | 6.066.831 EUR
- DEL Ángel Pérez | Deportivo Alavés | 7.399.321 EUR
- DEL T. Morente | Elche CF | 1.531.675 EUR
- DEL Iñigo Vicente | R. Racing Club | 21.209.482 EUR
- DEL Isi | Rayo Vallecano | 18.191.423 EUR | estado injured

#### Mercado que caduca antes

- DEF Aihen | precio 1.104.624 EUR | valor 1.104.612 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Yeray | precio 5.791.820 EUR | valor 5.791.533 EUR | machine | pujas 2 | caduca 27/8/26, 10:53
- CEN Francho | precio 2.708.372 EUR | valor 2.708.395 EUR | machine | pujas 1 | caduca 27/8/26, 10:53
- CEN Moleiro | precio 59.912.184 EUR | valor 59.911.108 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Mandi | precio 8.055.512 EUR | valor 8.055.251 EUR | machine | pujas 3 | caduca 27/8/26, 10:53
- DEF Cabrera | precio 13.056.216 EUR | valor 13.056.116 EUR | machine | pujas 0 | caduca 27/8/26, 10:53 | estado suspended
- DEF Salinas | precio 886.022 EUR | valor 886.014 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Xanet Olaiz | precio 529.715 EUR | valor 529.707 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Oyarzabal | precio 61.029.593 EUR | valor 61.028.823 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.514 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Sucic | precio 3.547.132 EUR | valor 3.547.032 EUR | machine | pujas 1 | caduca 27/8/26, 10:53
- POR Lunin | precio 1.872.911 EUR | valor 1.807.989 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33

#### Baratos a revisar

- DEF Xanet Olaiz | precio 529.715 EUR | valor 529.707 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Salinas | precio 886.022 EUR | valor 886.014 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEF Aihen | precio 1.104.624 EUR | valor 1.104.612 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- CEN Iker Muñoz | precio 1.167.383 EUR | valor 1.194.923 EUR | rival | ofertas 2 | vende Mynavo Kyiv | caduca 28/8/26, 17:03
- DEL T. Morente | precio 1.566.110 EUR | valor 1.531.675 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 28/8/26, 23:47
- POR Lunin | precio 1.872.911 EUR | valor 1.807.989 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 15:33
- CEN Francho | precio 2.708.372 EUR | valor 2.708.395 EUR | machine | pujas 1 | caduca 27/8/26, 10:53
- CEN Sucic | precio 3.547.132 EUR | valor 3.547.032 EUR | machine | pujas 1 | caduca 27/8/26, 10:53
- POR Gulácsi | precio 3.633.550 EUR | valor 3.633.514 EUR | machine | pujas 0 | caduca 27/8/26, 10:53

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 126.465.255 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 0:28
- DEL Mbappé | precio 129.980.560 EUR | valor 129.977.728 EUR | rival | ofertas 0 | vende Dynamo de Maghreb FC | caduca 29/8/26, 13:50
- DEL Mikautadze | precio 68.270.452 EUR | valor 69.648.856 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 28/8/26, 17:05
- DEL Oyarzabal | precio 61.029.593 EUR | valor 61.028.823 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Yeremay | precio 60.000.000 EUR | valor 40.811.508 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 28/8/26, 20:12
- CEN Moleiro | precio 59.912.184 EUR | valor 59.911.108 EUR | machine | pujas 0 | caduca 27/8/26, 10:53
- DEL Etta Eyong | precio 22.549.120 EUR | valor 21.383.955 EUR | rival | ofertas 1 | vende Rafishh | caduca 27/8/26, 16:01
- CEN Germán V. | precio 20.542.089 EUR | valor 20.153.565 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 28/8/26, 23:46

#### Alertas

- Cabrera: estado suspended en mercado.
- Isi: estado injured en mercado.
- Asencio: estado injured en mercado.
- Sorloth: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 9.590.829 EUR
- Valor plantilla: 229.689.982 EUR
- Jugadores plantilla: 12
- Mercado jugable: 15
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 25.897.575 EUR
- DEF Sergio Gómez | Real Sociedad | 16.387.388 EUR
- DEF Javi Rodríguez | Celta | 9.903.176 EUR
- DEF C. Puga | Málaga CF | 4.914.391 EUR
- DEF Pablo Ramón | R. Racing Club | 868.488 EUR
- DEF Koski | Deportivo Alavés | 1.989.948 EUR
- CEN Germán V. | Elche CF | 20.153.565 EUR
- CEN Javi Guerra | Valencia CF | 24.116.431 EUR
- CEN R. Terrats | Getafe CF | 3.940.650 EUR
- CEN Valverde | Real Madrid | 72.386.574 EUR
- DEL Chupe | Málaga CF | 41.248.841 EUR
- DEL Hugo Duro | Valencia CF | 7.882.955 EUR

#### Mercado que caduca antes

- CEN Buonanotte | precio 5.613.729 EUR | valor 5.480.720 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR Leo Román | precio 40.472.701 EUR | valor 40.296.105 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Dela | precio 11.251.772 EUR | valor 11.239.950 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEF Costa | precio 1.008.872 EUR | valor 983.106 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Yoel Lago | precio 677.391 EUR | valor 770.434 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEL Gordon | precio 66.795.866 EUR | valor 66.712.842 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR A. Fortuño | precio 492.645 EUR | valor 487.528 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEL Abdelkarim | precio 3.801.390 EUR | valor 3.808.087 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Barrios | precio 47.420.966 EUR | valor 47.910.198 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Guridi | precio 6.986.094 EUR | valor 7.095.558 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Mantilla | precio 2.424.504 EUR | valor 2.379.827 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Beitia | precio 492.587 EUR | valor 487.473 EUR | machine | pujas 0 | caduca 26/8/26, 22:10

#### Baratos a revisar

- DEF Beitia | precio 492.587 EUR | valor 487.473 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR A. Fortuño | precio 492.645 EUR | valor 487.528 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Yoel Lago | precio 677.391 EUR | valor 770.434 EUR | machine | pujas 1 | caduca 26/8/26, 22:10
- DEF Costa | precio 1.008.872 EUR | valor 983.106 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF Mantilla | precio 2.424.504 EUR | valor 2.379.827 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEL Abdelkarim | precio 3.801.390 EUR | valor 3.808.087 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- DEF C. Puga | precio 4.908.305 EUR | valor 4.914.391 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:13

#### Premium a revisar

- DEL Gordon | precio 66.795.866 EUR | valor 66.712.842 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Barrios | precio 47.420.966 EUR | valor 47.910.198 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- POR Leo Román | precio 40.472.701 EUR | valor 40.296.105 EUR | machine | pujas 0 | caduca 26/8/26, 22:10
- CEN Germán V. | precio 20.542.089 EUR | valor 20.153.565 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 28/8/26, 23:22

#### Alertas

- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

