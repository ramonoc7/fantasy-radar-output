# Brief Diario Ligas Fantasy

Datos API: 2026-08-30T00:12:18.642Z
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
- Valor plantilla: 236.448.740 EUR
- Jugadores plantilla: 15
- Mercado jugable: 16
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 41.532.445 EUR
- DEF Javi Rueda | Celta | 3.825.655 EUR
- DEF Nuñez | RCD Espanyol | 7.226.526 EUR
- DEF Koski | Deportivo Alavés | 2.655.368 EUR
- DEF Fran García | Real Betis | 15.400.091 EUR
- DEF Javi Rodríguez | Celta | 11.053.050 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 2.269.761 EUR
- CEN O. Rey | Levante UD | 1.000.084 EUR
- CEN Martim Neto | Elche CF | 1.534.997 EUR
- CEN Ibañez | Deportivo Alavés | 4.974.490 EUR
- CEN Valverde | Real Madrid | 72.831.375 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.329.439 EUR
- DEL Dolan | RCD Espanyol | 11.047.333 EUR
- DEL R. Brugué | Levante UD | 1.698.725 EUR
- DEL Oyarzabal | Real Sociedad | 58.069.401 EUR

#### Mercado que caduca antes

- CEN A. Osambela | precio 480.112 EUR | valor 479.821 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- POR Dmitrovic | precio 41.631.576 EUR | valor 41.405.685 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Raba | precio 1.131.405 EUR | valor 1.105.062 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Diego Rico | precio 3.867.915 EUR | valor 3.767.276 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Vanja Drkusic | precio 2.880.840 EUR | valor 2.813.493 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Matteo Prati | precio 4.742.544 EUR | valor 4.611.511 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Barzic | precio 634.642 EUR | valor 628.170 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Larrubia | precio 39.710.796 EUR | valor 38.731.378 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Zakharyan | precio 763.669 EUR | valor 752.036 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Satriano | precio 24.597.725 EUR | valor 24.169.309 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN R. Mendoza | precio 1.136.124 EUR | valor 1.161.817 EUR | machine | pujas 1 | caduca 30/8/26, 12:46
- DEL Niño | precio 1.707.781 EUR | valor 1.660.282 EUR | machine | pujas 0 | caduca 30/8/26, 12:46 | estado injured

#### Baratos a revisar

- CEN A. Osambela | precio 480.112 EUR | valor 479.821 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Barzic | precio 634.642 EUR | valor 628.170 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Zakharyan | precio 763.669 EUR | valor 752.036 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Raba | precio 1.131.405 EUR | valor 1.105.062 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN R. Mendoza | precio 1.136.124 EUR | valor 1.161.817 EUR | machine | pujas 1 | caduca 30/8/26, 12:46
- CEN Martim Neto | precio 1.567.416 EUR | valor 1.534.997 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 1/9/26, 16:38
- DEF Vanja Drkusic | precio 2.880.840 EUR | valor 2.813.493 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- POR J. Musso | precio 3.430.544 EUR | valor 3.197.573 EUR | rival | ofertas 1 | vende leomaldonado10 | caduca 30/8/26, 14:39
- DEF Diego Rico | precio 3.867.915 EUR | valor 3.767.276 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEF Javi Rueda | precio 3.909.409 EUR | valor 3.825.655 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 1/9/26, 16:42
- CEN Matteo Prati | precio 4.742.544 EUR | valor 4.611.511 EUR | machine | pujas 0 | caduca 30/8/26, 12:46

#### Premium a revisar

- POR Dmitrovic | precio 41.631.576 EUR | valor 41.405.685 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- CEN Larrubia | precio 39.710.796 EUR | valor 38.731.378 EUR | machine | pujas 0 | caduca 30/8/26, 12:46
- DEL Satriano | precio 24.597.725 EUR | valor 24.169.309 EUR | machine | pujas 0 | caduca 30/8/26, 12:46

#### Alertas

- Niño: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 38.165.550 EUR
- Valor plantilla: 215.316.240 EUR
- Jugadores plantilla: 12
- Mercado jugable: 33
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 39.703.997 EUR
- DEF Djene | Getafe CF | 12.934.570 EUR
- DEF Huijsen | Real Madrid | 44.038.847 EUR
- DEF Fran García | Real Betis | 15.400.091 EUR
- CEN Mario Soriano | RC Deportivo | 26.996.779 EUR
- CEN D. Villares | RC Deportivo | 1.847.749 EUR
- CEN Izan M. | Málaga CF | 5.053.977 EUR
- CEN Germán V. | Elche CF | 18.739.717 EUR
- CEN R. Terrats | Getafe CF | 4.731.376 EUR
- CEN Agoumé | Sevilla FC | 6.773.004 EUR
- DEL Iñigo Vicente | R. Racing Club | 22.925.455 EUR
- DEL Isi | Rayo Vallecano | 16.170.678 EUR | estado injured

#### Mercado que caduca antes

- CEN Dotor | precio 4.177.749 EUR | valor 4.268.117 EUR | machine | pujas 1 | caduca 30/8/26, 10:53
- CEN Hugo Sotelo | precio 1.246.370 EUR | valor 1.215.429 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Kevin | precio 705.075 EUR | valor 695.785 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Gerard | precio 27.780.049 EUR | valor 28.427.769 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Recio | precio 935.600 EUR | valor 962.336 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Areso | precio 2.636.912 EUR | valor 2.569.893 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Junior | precio 2.590.677 EUR | valor 2.515.609 EUR | machine | pujas 0 | caduca 30/8/26, 10:53 | estado injured
- DEF Murillo | precio 1.371.790 EUR | valor 1.335.832 EUR | machine | pujas 0 | caduca 30/8/26, 10:53 | estado injured
- DEL Paco Cortes | precio 640.542 EUR | valor 633.834 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- CEN Koke | precio 18.877.844 EUR | valor 19.390.571 EUR | machine | pujas 1 | caduca 30/8/26, 10:53
- CEN Kochorashvili | precio 9.490.534 EUR | valor 9.291.176 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF H. Rincón | precio 2.460.291 EUR | valor 2.403.663 EUR | machine | pujas 0 | caduca 30/8/26, 10:53

#### Baratos a revisar

- DEL Paco Cortes | precio 640.542 EUR | valor 633.834 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEL Kevin | precio 705.075 EUR | valor 695.785 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Recio | precio 935.600 EUR | valor 962.336 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- CEN Carlos Macià | precio 1.000.000 EUR | valor 810.325 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 1/9/26, 18:56
- CEN Hugo Sotelo | precio 1.246.370 EUR | valor 1.215.429 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF H. Rincón | precio 2.460.291 EUR | valor 2.403.663 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- DEF Areso | precio 2.636.912 EUR | valor 2.569.893 EUR | machine | pujas 0 | caduca 30/8/26, 10:53
- CEN Dotor | precio 4.177.749 EUR | valor 4.268.117 EUR | machine | pujas 1 | caduca 30/8/26, 10:53
- CEN Francho | precio 4.700.000 EUR | valor 2.826.053 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 30/8/26, 12:00

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 123.963.179 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 30/8/26, 18:22
- DEL Mikautadze | precio 72.969.361 EUR | valor 73.131.618 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 1/9/26, 17:33
- POR Dmitrovic | precio 43.000.000 EUR | valor 41.405.685 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 31/8/26, 12:18
- POR Sergio Herrera | precio 35.924.225 EUR | valor 35.821.697 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 1/9/26, 12:38
- CEN Kubo | precio 34.900.000 EUR | valor 27.808.291 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 1/9/26, 2:05
- DEF Lejeune | precio 32.402.143 EUR | valor 31.243.647 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:29
- DEL Gerard | precio 27.780.049 EUR | valor 28.427.769 EUR | machine | pujas 2 | caduca 30/8/26, 10:53
- DEF Aramburu | precio 24.000.000 EUR | valor 16.823.249 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 30/8/26, 12:05

#### Alertas

- Junior: estado injured en mercado.
- Murillo: estado injured en mercado.
- Asencio: estado injured en mercado.
- Sorloth: estado injured en mercado.
- Gattoni: estado out_of_league en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 864.906 EUR
- Valor plantilla: 240.678.698 EUR
- Jugadores plantilla: 13
- Mercado jugable: 14
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 29.034.077 EUR
- DEF Sergio Gómez | Real Sociedad | 15.371.522 EUR
- DEF Javi Rodríguez | Celta | 11.053.050 EUR
- DEF Dela | Levante UD | 11.369.702 EUR
- DEF Pablo Ramón | R. Racing Club | 1.228.916 EUR
- DEF Koski | Deportivo Alavés | 2.655.368 EUR
- CEN Germán V. | Elche CF | 18.739.717 EUR
- CEN Javi Guerra | Valencia CF | 24.991.990 EUR
- CEN R. Terrats | Getafe CF | 4.731.376 EUR
- CEN Valverde | Real Madrid | 72.831.375 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 2.269.761 EUR
- DEL Chupe | Málaga CF | 39.094.380 EUR
- DEL Hugo Duro | Valencia CF | 7.307.464 EUR

#### Mercado que caduca antes

- POR P. Campos | precio 797.141 EUR | valor 784.169 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEF Marcos Alonso | precio 29.396.494 EUR | valor 28.722.014 EUR | machine | pujas 0 | caduca 30/8/26, 22:10 | estado suspended
- DEF Fran García | precio 14.582.255 EUR | valor 15.400.091 EUR | machine | pujas 1 | caduca 30/8/26, 22:10
- DEF Boyomo | precio 23.814.409 EUR | valor 23.136.569 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEL Nteka | precio 1.349.506 EUR | valor 1.340.991 EUR | machine | pujas 1 | caduca 30/8/26, 22:10
- DEL Giuliano | precio 43.375.972 EUR | valor 43.959.818 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEF Lozano | precio 559.694 EUR | valor 556.220 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- CEN Alberto Calatrava | precio 764.155 EUR | valor 752.502 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- CEN H. González | precio 1.141.290 EUR | valor 1.114.552 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEF Luiz Felipe | precio 2.552.732 EUR | valor 2.476.512 EUR | machine | pujas 0 | caduca 30/8/26, 22:10 | estado injured
- DEL Rodrygo | precio 2.307.797 EUR | valor 2.265.832 EUR | machine | pujas 0 | caduca 30/8/26, 22:10 | estado injured
- CEN Brahim | precio 9.958.850 EUR | valor 9.739.586 EUR | rival | ofertas 1 | vende Racsuil | caduca 1/9/26, 9:06

#### Baratos a revisar

- DEF Lozano | precio 559.694 EUR | valor 556.220 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- CEN Alberto Calatrava | precio 764.155 EUR | valor 752.502 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- POR P. Campos | precio 797.141 EUR | valor 784.169 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- CEN H. González | precio 1.141.290 EUR | valor 1.114.552 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEL Nteka | precio 1.349.506 EUR | valor 1.340.991 EUR | machine | pujas 1 | caduca 30/8/26, 22:10
- CEN Almeida | precio 2.786.178 EUR | valor 1.736.680 EUR | rival | ofertas 0 | vende Erdeivis22 | caduca 2/9/26, 0:07

#### Premium a revisar

- DEL Giuliano | precio 43.375.972 EUR | valor 43.959.818 EUR | machine | pujas 0 | caduca 30/8/26, 22:10
- DEF Boyomo | precio 23.814.409 EUR | valor 23.136.569 EUR | machine | pujas 0 | caduca 30/8/26, 22:10

#### Alertas

- Marcos Alonso: estado suspended en mercado.
- Luiz Felipe: estado injured en mercado.
- Rodrygo: estado injured en mercado.
- A. Batalla: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

