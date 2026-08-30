# Brief Diario Ligas Fantasy

Datos API: 2026-08-30T12:48:31.585Z
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
- Mercado jugable: 13
- Entrenadores ignorados: 2
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

- DEF Marc Pubill | precio 54.818.931 EUR | valor 54.818.931 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Parrott | precio 23.262.975 EUR | valor 23.262.975 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Ali Houary | precio 1.685.716 EUR | valor 1.685.716 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Deossa | precio 2.226.756 EUR | valor 2.226.756 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- POR P. Campos | precio 784.169 EUR | valor 784.169 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Alberto Calatrava | precio 752.502 EUR | valor 752.502 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Miguel Sierra | precio 1.282.251 EUR | valor 1.282.251 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- POR Germán | precio 507.822 EUR | valor 507.822 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEF Valentín Gómez | precio 1.732.115 EUR | valor 1.732.115 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Nordin Al-Lal | precio 458.524 EUR | valor 458.524 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Hugo Sotelo | precio 1.215.429 EUR | valor 1.215.429 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Martim Neto | precio 1.567.416 EUR | valor 1.534.997 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 1/9/26, 16:38

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 458.524 EUR | valor 458.524 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- POR Germán | precio 507.822 EUR | valor 507.822 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Alberto Calatrava | precio 752.502 EUR | valor 752.502 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- POR P. Campos | precio 784.169 EUR | valor 784.169 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Hugo Sotelo | precio 1.215.429 EUR | valor 1.215.429 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Miguel Sierra | precio 1.282.251 EUR | valor 1.282.251 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Martim Neto | precio 1.567.416 EUR | valor 1.534.997 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 1/9/26, 16:38
- DEL Ali Houary | precio 1.685.716 EUR | valor 1.685.716 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEF Valentín Gómez | precio 1.732.115 EUR | valor 1.732.115 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- CEN Deossa | precio 2.226.756 EUR | valor 2.226.756 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEF Javi Rueda | precio 3.909.409 EUR | valor 3.825.655 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 1/9/26, 16:42

#### Premium a revisar

- DEF Marc Pubill | precio 54.818.931 EUR | valor 54.818.931 EUR | machine | pujas 0 | caduca 31/8/26, 12:46
- DEL Parrott | precio 23.262.975 EUR | valor 23.262.975 EUR | machine | pujas 0 | caduca 31/8/26, 12:46

#### Alertas

- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 36.598.551 EUR
- Valor plantilla: 216.278.576 EUR
- Jugadores plantilla: 13
- Mercado jugable: 30
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 39.703.997 EUR
- DEF Djene | Getafe CF | 12.934.570 EUR
- DEF Huijsen | Real Madrid | 44.038.847 EUR
- DEF Recio | Málaga CF | 962.336 EUR
- DEF Fran García | Real Betis | 15.400.091 EUR
- CEN Izan M. | Málaga CF | 5.053.977 EUR
- CEN Mario Soriano | RC Deportivo | 26.996.779 EUR
- CEN D. Villares | RC Deportivo | 1.847.749 EUR
- CEN Germán V. | Elche CF | 18.739.717 EUR
- CEN R. Terrats | Getafe CF | 4.731.376 EUR
- CEN Agoumé | Sevilla FC | 6.773.004 EUR
- DEL Iñigo Vicente | R. Racing Club | 22.925.455 EUR
- DEL Isi | Rayo Vallecano | 16.170.678 EUR | estado injured

#### Mercado que caduca antes

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 123.963.179 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 30/8/26, 18:22
- DEF Lejeune | precio 32.402.143 EUR | valor 31.243.647 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:29
- DEF El Hilali | precio 11.921.304 EUR | valor 12.073.627 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:30
- CEN Amatucci | precio 14.928.689 EUR | valor 15.300.675 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:30
- CEN G. Villar | precio 8.376.400 EUR | valor 8.925.102 EUR | rival | ofertas 1 | vende alemois | caduca 31/8/26, 8:30
- DEL Bil Nsongo | precio 6.126.056 EUR | valor 6.126.056 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEL Endrick | precio 5.277.767 EUR | valor 5.277.767 EUR | machine | pujas 0 | caduca 31/8/26, 10:53 | estado doubtful
- CEN Goti | precio 1.648.240 EUR | valor 1.648.240 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Carlos Sánchez | precio 568.920 EUR | valor 568.920 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- CEN Arda Güler | precio 70.737.376 EUR | valor 70.737.376 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Boyomo | precio 23.136.569 EUR | valor 23.136.569 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Trent | precio 19.055.137 EUR | valor 19.055.137 EUR | machine | pujas 0 | caduca 31/8/26, 10:53

#### Baratos a revisar

- POR Llorenç | precio 490.792 EUR | valor 490.792 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Carlos Sánchez | precio 568.920 EUR | valor 568.920 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Balliu | precio 820.492 EUR | valor 820.492 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- CEN Carlos Macià | precio 1.000.000 EUR | valor 810.325 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 1/9/26, 18:56
- CEN Goti | precio 1.648.240 EUR | valor 1.648.240 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Diakhaby | precio 4.845.182 EUR | valor 4.845.182 EUR | machine | pujas 0 | caduca 31/8/26, 10:53

#### Premium a revisar

- DEL Lamine Yamal | precio 160.000.000 EUR | valor 123.963.179 EUR | rival | ofertas 1 | vende West Jamon C.F.D. | caduca 30/8/26, 18:22
- DEL Mikautadze | precio 72.969.361 EUR | valor 73.131.618 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 1/9/26, 17:33
- CEN Arda Güler | precio 70.737.376 EUR | valor 70.737.376 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEL Pepe | precio 66.947.016 EUR | valor 66.947.016 EUR | machine | pujas 1 | caduca 31/8/26, 10:53
- CEN Bernardo Silva | precio 58.400.175 EUR | valor 58.400.175 EUR | machine | pujas 0 | caduca 31/8/26, 10:53
- DEF Grimaldo | precio 40.870.055 EUR | valor 40.870.055 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 2/9/26, 11:05
- CEN Kubo | precio 34.900.000 EUR | valor 27.808.291 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 1/9/26, 2:05
- DEF Lejeune | precio 32.402.143 EUR | valor 31.243.647 EUR | rival | ofertas 0 | vende alemois | caduca 31/8/26, 8:29

#### Alertas

- Endrick: estado doubtful en mercado.
- Asencio: estado injured en mercado.
- Sorloth: estado injured en mercado.
- Gattoni: estado out_of_league en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 864.906 EUR
- Valor plantilla: 240.678.698 EUR
- Jugadores plantilla: 13
- Mercado jugable: 13
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
- DEL Giuliano | precio 43.375.972 EUR | valor 43.959.818 EUR | machine | pujas 1 | caduca 30/8/26, 22:10
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

- DEL Giuliano | precio 43.375.972 EUR | valor 43.959.818 EUR | machine | pujas 1 | caduca 30/8/26, 22:10
- DEF Boyomo | precio 23.814.409 EUR | valor 23.136.569 EUR | machine | pujas 0 | caduca 30/8/26, 22:10

#### Alertas

- Marcos Alonso: estado suspended en mercado.
- Luiz Felipe: estado injured en mercado.
- Rodrygo: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

