# Brief Diario Ligas Fantasy

Datos API: 2026-08-29T18:23:03.840Z
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

- Saldo: 21.315.207 EUR
- Valor plantilla: 233.158.485 EUR
- Jugadores plantilla: 15
- Mercado jugable: 16
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 40.348.284 EUR
- DEF Javi Rueda | Celta | 3.909.409 EUR
- DEF Nuñez | RCD Espanyol | 7.002.115 EUR
- DEF Koski | Deportivo Alavés | 2.427.588 EUR
- DEF Fran García | Real Betis | 14.582.255 EUR
- DEF Javi Rodríguez | Celta | 10.787.900 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 2.137.727 EUR
- CEN O. Rey | Levante UD | 968.075 EUR
- CEN Martim Neto | Elche CF | 1.567.416 EUR
- CEN Ibañez | Deportivo Alavés | 4.780.922 EUR
- CEN Valverde | Real Madrid | 72.407.429 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.295.339 EUR
- DEL Dolan | RCD Espanyol | 10.708.881 EUR
- DEL R. Brugué | Levante UD | 1.691.985 EUR
- DEL Oyarzabal | Real Sociedad | 58.543.160 EUR

#### Mercado que caduca antes

- CEN A. Osambela | precio 480.112 EUR | valor 480.112 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- POR Dmitrovic | precio 41.631.576 EUR | valor 41.631.576 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Raba | precio 1.131.405 EUR | valor 1.131.405 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Diego Rico | precio 3.867.915 EUR | valor 3.867.915 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Vanja Drkusic | precio 2.880.840 EUR | valor 2.880.840 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Matteo Prati | precio 4.742.544 EUR | valor 4.742.544 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Barzic | precio 634.642 EUR | valor 634.642 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Larrubia | precio 39.710.796 EUR | valor 39.710.796 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Zakharyan | precio 763.669 EUR | valor 763.669 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Satriano | precio 24.597.725 EUR | valor 24.597.725 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN R. Mendoza | precio 1.136.124 EUR | valor 1.136.124 EUR | machine | pujas 1 | caduca 30/8/26, 12:46
- DEL Niño | precio 1.707.781 EUR | valor 1.707.781 EUR | machine | pujas 0 | caduca 30/8/26, 12:46 | estado injured

#### Baratos a revisar

- CEN A. Osambela | precio 480.112 EUR | valor 480.112 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Barzic | precio 634.642 EUR | valor 634.642 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Zakharyan | precio 763.669 EUR | valor 763.669 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Raba | precio 1.131.405 EUR | valor 1.131.405 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN R. Mendoza | precio 1.136.124 EUR | valor 1.136.124 EUR | machine | pujas 1 | caduca 30/8/26, 12:46
- CEN Martim Neto | precio 1.567.416 EUR | valor 1.567.416 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 1/9/26, 16:38
- DEF Vanja Drkusic | precio 2.880.840 EUR | valor 2.880.840 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- POR J. Musso | precio 3.430.544 EUR | valor 3.276.811 EUR | rival | ofertas 1 | vende leomaldonado10 | caduca 30/8/26, 14:39
- DEF Diego Rico | precio 3.867.915 EUR | valor 3.867.915 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Javi Rueda | precio 3.909.409 EUR | valor 3.909.409 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 1/9/26, 16:42
- CEN Matteo Prati | precio 4.742.544 EUR | valor 4.742.544 EUR | machine | pujas 0 | caduca 30/8/26, 12:46

#### Premium a revisar

- POR Dmitrovic | precio 41.631.576 EUR | valor 41.631.576 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Larrubia | precio 39.710.796 EUR | valor 39.710.796 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Satriano | precio 24.597.725 EUR | valor 24.597.725 EUR | machine | pujas 0 | caduca 30/8/26, 12:46

#### Alertas

- Niño: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 38.165.550 EUR
- Valor plantilla: 213.461.197 EUR
- Jugadores plantilla: 12
- Mercado jugable: 36
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 39.719.725 EUR
- DEF Djene | Getafe CF | 12.469.017 EUR
- DEF Huijsen | Real Madrid | 43.043.241 EUR
- DEF Fran García | Real Betis | 14.582.255 EUR
- CEN Mario Soriano | RC Deportivo | 27.489.360 EUR
- CEN D. Villares | RC Deportivo | 1.887.010 EUR
- CEN Izan M. | Málaga CF | 5.128.515 EUR
- CEN Germán V. | Elche CF | 19.145.412 EUR
- CEN R. Terrats | Getafe CF | 4.531.203 EUR
- CEN Agoumé | Sevilla FC | 6.642.561 EUR
- DEL Iñigo Vicente | R. Racing Club | 22.196.901 EUR
- DEL Isi | Rayo Vallecano | 16.625.997 EUR | estado injured

#### Mercado que caduca antes

- CEN D. Villares | precio 1.983.085 EUR | valor 1.887.010 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 30/8/26, 0:07
- CEN Blanco | precio 15.048.694 EUR | valor 15.030.616 EUR | rival | ofertas 1 | vende Archiking | caduca 30/8/26, 1:55
- CEN Dotor | precio 4.177.749 EUR | valor 4.177.749 EUR | machine | pujas 1 | caduca 30/8/26, 10:53
- CEN Hugo Sotelo | precio 1.246.370 EUR | valor 1.246.370 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Kevin | precio 705.075 EUR | valor 705.075 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Gerard | precio 27.780.049 EUR | valor 27.780.049 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Recio | precio 935.600 EUR | valor 935.600 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Areso | precio 2.636.912 EUR | valor 2.636.912 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Junior | precio 2.590.677 EUR | valor 2.590.677 EUR | machine | pujas 0 | caduca 30/8/26, 10:53 | estado injured
- DEF Murillo | precio 1.371.790 EUR | valor 1.371.790 EUR | machine | pujas 0 | caduca 30/8/26, 10:53 | estado injured
- DEL Paco Cortes | precio 640.542 EUR | valor 640.542 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- CEN Koke | precio 18.877.844 EUR | valor 18.877.844 EUR | machine | pujas 1 | caduca 30/8/26, 10:53

#### Baratos a revisar

- DEL Paco Cortes | precio 640.542 EUR | valor 640.542 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Kevin | precio 705.075 EUR | valor 705.075 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Recio | precio 935.600 EUR | valor 935.600 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- CEN Carlos Macià | precio 1.000.000 EUR | valor 819.300 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 1/9/26, 18:56
- CEN Hugo Sotelo | precio 1.246.370 EUR | valor 1.246.370 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- CEN D. Villares | precio 1.983.085 EUR | valor 1.887.010 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 30/8/26, 0:07
- DEF H. Rincón | precio 2.460.291 EUR | valor 2.460.291 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Areso | precio 2.636.912 EUR | valor 2.636.912 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- CEN Dotor | precio 4.177.749 EUR | valor 4.177.749 EUR | machine | pujas 1 | caduca 30/8/26, 10:53
- CEN Francho | precio 4.700.000 EUR | valor 2.827.683 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 30/8/26, 12:00

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 124.144.127 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 30/8/26, 18:22
- DEL Mikautadze | precio 72.969.361 EUR | valor 72.969.361 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 1/9/26, 17:33
- POR Dmitrovic | precio 43.000.000 EUR | valor 41.631.576 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 31/8/26, 12:18
- POR Sergio Herrera | precio 35.924.225 EUR | valor 35.924.225 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 1/9/26, 12:38
- CEN Kubo | precio 34.900.000 EUR | valor 28.068.098 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 1/9/26, 2:05
- DEF Lejeune | precio 32.402.143 EUR | valor 31.835.899 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:29
- DEL Gerard | precio 27.780.049 EUR | valor 27.780.049 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Aramburu | precio 24.000.000 EUR | valor 17.143.584 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 30/8/26, 12:05

#### Alertas

- Junior: estado injured en mercado.
- Murillo: estado injured en mercado.
- Asencio: estado injured en mercado.
- Sorloth: estado injured en mercado.
- Gattoni: estado out_of_league en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 3.002.705 EUR
- Valor plantilla: 237.434.250 EUR
- Jugadores plantilla: 12
- Mercado jugable: 14
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 28.108.120 EUR
- DEF Sergio Gómez | Real Sociedad | 15.661.401 EUR
- DEF Javi Rodríguez | Celta | 10.787.900 EUR
- DEF Dela | Levante UD | 11.324.956 EUR
- DEF Pablo Ramón | R. Racing Club | 1.164.864 EUR
- DEF Koski | Deportivo Alavés | 2.427.588 EUR
- CEN R. Terrats | Getafe CF | 4.531.203 EUR
- CEN Germán V. | Elche CF | 19.145.412 EUR
- CEN Javi Guerra | Valencia CF | 24.740.500 EUR
- CEN Valverde | Real Madrid | 72.407.429 EUR
- DEL Chupe | Málaga CF | 39.657.785 EUR
- DEL Hugo Duro | Valencia CF | 7.477.092 EUR

#### Mercado que caduca antes

- CEN M. Casadó | precio 1.397.197 EUR | valor 1.370.870 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- DEF Hancko | precio 44.110.889 EUR | valor 44.062.913 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Bardeli | precio 3.224.036 EUR | valor 3.217.312 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- POR Diego Conde | precio 2.267.385 EUR | valor 2.207.285 EUR | machine | pujas 0 | caduca 29/8/26, 22:10 | estado injured
- DEL Gorka Carrera | precio 643.470 EUR | valor 633.983 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Hugo Pérez | precio 1.106.237 EUR | valor 1.078.240 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Mikel Rodriguez | precio 1.995.480 EUR | valor 2.137.727 EUR | machine | pujas 2 | caduca 29/8/26, 22:10
- POR Szczesny | precio 1.783.232 EUR | valor 1.745.466 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- DEF Areso | precio 2.689.202 EUR | valor 2.636.912 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Risco | precio 579.866 EUR | valor 572.924 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- DEF Adama | precio 450.013 EUR | valor 448.265 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Caste | precio 566.085 EUR | valor 559.694 EUR | machine | pujas 0 | caduca 29/8/26, 22:10

#### Baratos a revisar

- DEF Adama | precio 450.013 EUR | valor 448.265 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Caste | precio 566.085 EUR | valor 559.694 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Risco | precio 579.866 EUR | valor 572.924 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- DEL Gorka Carrera | precio 643.470 EUR | valor 633.983 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Hugo Pérez | precio 1.106.237 EUR | valor 1.078.240 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN M. Casadó | precio 1.397.197 EUR | valor 1.370.870 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- POR Szczesny | precio 1.783.232 EUR | valor 1.745.466 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Mikel Rodriguez | precio 1.995.480 EUR | valor 2.137.727 EUR | machine | pujas 2 | caduca 29/8/26, 22:10
- DEF Areso | precio 2.689.202 EUR | valor 2.636.912 EUR | machine | pujas 0 | caduca 29/8/26, 22:10
- CEN Bardeli | precio 3.224.036 EUR | valor 3.217.312 EUR | machine | pujas 0 | caduca 29/8/26, 22:10

#### Premium a revisar

- DEF Hancko | precio 44.110.889 EUR | valor 44.062.913 EUR | machine | pujas 0 | caduca 29/8/26, 22:10

#### Alertas

- Diego Conde: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

