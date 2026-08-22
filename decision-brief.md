# Brief Diario Ligas Fantasy

Datos API: 2026-08-19T11:39:05.743Z
Semana actual: 1

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

- Saldo: 56.578.353 EUR
- Valor plantilla: 174.616.285 EUR
- Jugadores plantilla: 20
- Mercado jugable: 17
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.742.174 EUR
- DEF Koski | Deportivo Alavés | 1.038.751 EUR
- DEF Javi Rodríguez | Celta | 9.065.805 EUR
- DEF Nuñez | RCD Espanyol | 4.224.428 EUR
- DEF Trent | Real Madrid | 22.349.536 EUR
- DEF Riedel | RCD Espanyol | 4.781.700 EUR
- DEF Suazo | Sevilla FC | 5.212.434 EUR
- DEF Davinchi | Getafe CF | 2.992.753 EUR
- DEF Javi Rueda | Celta | 4.382.431 EUR
- CEN D. Villares | RC Deportivo | 2.329.238 EUR
- CEN Kubo | Real Sociedad | 25.271.514 EUR
- CEN Maguette | R. Racing Club | 3.805.951 EUR
- CEN Guido Rodríguez | Valencia CF | 24.458.876 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 933.372 EUR
- CEN Gorrotxa | Real Sociedad | 5.731.847 EUR
- CEN Ibañez | Deportivo Alavés | 3.412.482 EUR
- DEL Dolan | RCD Espanyol | 6.702.093 EUR
- DEL Rodrygo | Real Madrid | 2.794.611 EUR | estado injured
- DEL Hugo Duro | Valencia CF | 8.513.114 EUR
- DEL Miguel Rodríguez | Deportivo Alavés | 2.873.175 EUR

#### Mercado que caduca antes

- DEF Vivian | precio 10.512.541 EUR | valor 9.620.708 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 19/8/26, 20:35 | estado injured
- DEL Budimir | precio 51.852.202 EUR | valor 51.850.909 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Lejeune | precio 36.749.815 EUR | valor 36.749.699 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEL Nico Williams | precio 61.686.109 EUR | valor 61.685.833 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Catena | precio 32.979.197 EUR | valor 32.979.053 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN Comesaña | precio 32.971.145 EUR | valor 32.971.086 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Timera | precio 642.097 EUR | valor 642.095 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN Carlos Macià | precio 776.030 EUR | valor 776.009 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Novoa | precio 856.469 EUR | valor 856.467 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN C. Soler | precio 32.756.916 EUR | valor 32.756.677 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEL Oyarzabal | precio 63.342.611 EUR | valor 63.339.794 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Fran García | precio 9.399.804 EUR | valor 9.398.165 EUR | machine | pujas 0 | caduca 20/8/26, 12:46

#### Baratos a revisar

- DEF Timera | precio 642.097 EUR | valor 642.095 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN Carlos Macià | precio 776.030 EUR | valor 776.009 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Novoa | precio 856.469 EUR | valor 856.467 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.353.524 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36
- DEF Riedel | precio 4.582.772 EUR | valor 4.781.700 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 21/8/26, 1:11

#### Premium a revisar

- DEL Oyarzabal | precio 63.342.611 EUR | valor 63.339.794 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEL Nico Williams | precio 61.686.109 EUR | valor 61.685.833 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEL Budimir | precio 51.852.202 EUR | valor 51.850.909 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Lejeune | precio 36.749.815 EUR | valor 36.749.699 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Catena | precio 32.979.197 EUR | valor 32.979.053 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN Comesaña | precio 32.971.145 EUR | valor 32.971.086 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- CEN C. Soler | precio 32.756.916 EUR | valor 32.756.677 EUR | machine | pujas 0 | caduca 20/8/26, 12:46
- DEF Trent | precio 22.364.018 EUR | valor 22.349.536 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 9:53

#### Alertas

- Vivian: estado injured en mercado.
- Rodrygo: estado injured en mercado.
- Rioja: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: -6.893.472 EUR
- Valor plantilla: 238.800.161 EUR
- Jugadores plantilla: 19
- Mercado jugable: 22
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 41.758.197 EUR
- DEF Djene | Getafe CF | 9.149.126 EUR
- DEF Kumbulla | Rayo Vallecano | 5.114.695 EUR | estado doubtful
- DEF Koski | Deportivo Alavés | 1.038.751 EUR
- DEF Huijsen | Real Madrid | 35.005.150 EUR
- DEF Álex Balde | FC Barcelona | 23.653.326 EUR
- CEN Moi Gómez | C.A. Osasuna | 1.875.959 EUR
- CEN Germán V. | Elche CF | 22.495.449 EUR
- CEN Izan M. | Málaga CF | 6.013.254 EUR
- CEN Mario Soriano | RC Deportivo | 27.522.850 EUR
- CEN D. Villares | RC Deportivo | 2.329.238 EUR
- CEN O. Rey | Levante UD | 737.289 EUR
- CEN Riquelme | Real Betis | 4.303.296 EUR
- CEN R. Terrats | Getafe CF | 3.183.959 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.419.899 EUR
- DEL Isi | Rayo Vallecano | 20.451.145 EUR
- DEL T. Morente | Elche CF | 1.769.342 EUR
- DEL Iñigo Vicente | R. Racing Club | 19.826.992 EUR
- DEL Isaac | Sevilla FC | 6.152.244 EUR

#### Mercado que caduca antes

- DEL Marcos | precio 1.292.281 EUR | valor 1.292.276 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- POR A. Iturbe | precio 766.234 EUR | valor 766.232 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEL Guedes | precio 30.273.901 EUR | valor 30.273.859 EUR | machine | pujas 0 | caduca 20/8/26, 10:53 | estado injured
- DEL Lamine Yamal | precio 126.108.531 EUR | valor 126.107.285 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Carlos Macià | precio 776.030 EUR | valor 776.009 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Marín | precio 1.417.543 EUR | valor 1.417.541 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEF Gerard Martín | precio 37.347.615 EUR | valor 37.346.512 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEF Nacho Perez | precio 572.258 EUR | valor 572.248 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEL Lookman | precio 72.745.938 EUR | valor 72.745.670 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEF Mantilla | precio 2.698.134 EUR | valor 2.698.125 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Fermín | precio 69.369.236 EUR | valor 69.368.610 EUR | machine | pujas 1 | caduca 20/8/26, 10:53
- DEL Isaac | precio 6.443.426 EUR | valor 6.152.244 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 20/8/26, 10:53

#### Baratos a revisar

- DEF Nacho Perez | precio 572.258 EUR | valor 572.248 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN O. Rey | precio 737.289 EUR | valor 737.289 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 11:05
- POR A. Iturbe | precio 766.234 EUR | valor 766.232 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Carlos Macià | precio 776.030 EUR | valor 776.009 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- POR Marrero | precio 1.042.937 EUR | valor 1.042.934 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- DEL Marcos | precio 1.292.281 EUR | valor 1.292.276 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.293.442 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- CEN Marín | precio 1.417.543 EUR | valor 1.417.541 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEF Mantilla | precio 2.698.134 EUR | valor 2.698.125 EUR | machine | pujas 0 | caduca 20/8/26, 10:53

#### Premium a revisar

- DEL Lamine Yamal | precio 126.108.531 EUR | valor 126.107.285 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEL Lookman | precio 72.745.938 EUR | valor 72.745.670 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- CEN Fermín | precio 69.369.236 EUR | valor 69.368.610 EUR | machine | pujas 1 | caduca 20/8/26, 10:53
- DEF Eric | precio 44.561.543 EUR | valor 44.708.338 EUR | rival | ofertas 1 | vende alemois | caduca 20/8/26, 14:03
- DEF Gerard Martín | precio 37.347.615 EUR | valor 37.346.512 EUR | machine | pujas 0 | caduca 20/8/26, 10:53
- DEF Llorente  | precio 25.000.000 EUR | valor 13.021.989 EUR | rival | ofertas 0 | vende West Jamon C.F.D. | caduca 22/8/26, 10:59

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Guedes: estado injured en mercado.
- R.P. Bigas: estado doubtful en mercado.
- E. Militão: estado injured en mercado.
- Purić: estado out_of_league en mercado.
- Cabrera: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 67.282.931 EUR
- Valor plantilla: 168.630.222 EUR
- Jugadores plantilla: 15
- Mercado jugable: 13
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 21.482.951 EUR
- DEF C. Puga | Málaga CF | 5.010.157 EUR
- DEF Pablo Ramón | R. Racing Club | 546.278 EUR
- DEF Koski | Deportivo Alavés | 1.038.751 EUR
- DEF Sergio Gómez | Real Sociedad | 17.699.193 EUR
- CEN Pedro Díaz | Rayo Vallecano | 1.722.667 EUR
- CEN R. Terrats | Getafe CF | 3.183.959 EUR
- CEN Javi Guerra | Valencia CF | 24.545.512 EUR
- CEN D. Villares | RC Deportivo | 2.329.238 EUR
- CEN Maguette | R. Racing Club | 3.805.951 EUR
- CEN Germán V. | Elche CF | 22.495.449 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.293.442 EUR
- DEL Chupe | Málaga CF | 47.830.671 EUR
- DEL Villalibre | R. Racing Club | 7.132.889 EUR
- DEL Hugo Duro | Valencia CF | 8.513.114 EUR

#### Mercado que caduca antes

- DEL Joaquín | precio 6.704.555 EUR | valor 6.334.354 EUR | rival | ofertas 1 | vende JoseJa94 | caduca 19/8/26, 19:23
- POR Swiderski | precio 584.074 EUR | valor 573.948 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Pol Lozano | precio 2.183.973 EUR | valor 2.137.439 EUR | machine | pujas 1 | caduca 19/8/26, 22:10
- DEF J. Vázquez | precio 1.696.069 EUR | valor 1.675.986 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Prados | precio 1.365.124 EUR | valor 1.332.505 EUR | machine | pujas 1 | caduca 19/8/26, 22:10
- DEL B. Mayoral | precio 2.854.940 EUR | valor 2.800.731 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- DEL Osorio | precio 1.361.883 EUR | valor 1.320.644 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- DEF J. Ives Valou | precio 583.389 EUR | valor 573.290 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Diatta | precio 537.940 EUR | valor 529.659 EUR | machine | pujas 0 | caduca 19/8/26, 22:10 | estado suspended
- CEN Manel Usedo | precio 761.846 EUR | valor 744.609 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- DEF Javi Rodríguez | precio 9.059.783 EUR | valor 9.065.805 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- DEL Etta Eyong | precio 25.480.174 EUR | valor 24.961.008 EUR | machine | pujas 0 | caduca 19/8/26, 22:10

#### Baratos a revisar

- DEF J. Ives Valou | precio 583.389 EUR | valor 573.290 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- POR Swiderski | precio 584.074 EUR | valor 573.948 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Manel Usedo | precio 761.846 EUR | valor 744.609 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- DEL Osorio | precio 1.361.883 EUR | valor 1.320.644 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Prados | precio 1.365.124 EUR | valor 1.332.505 EUR | machine | pujas 1 | caduca 19/8/26, 22:10
- DEF J. Vázquez | precio 1.696.069 EUR | valor 1.675.986 EUR | machine | pujas 0 | caduca 19/8/26, 22:10
- CEN Pol Lozano | precio 2.183.973 EUR | valor 2.137.439 EUR | machine | pujas 1 | caduca 19/8/26, 22:10
- DEL B. Mayoral | precio 2.854.940 EUR | valor 2.800.731 EUR | machine | pujas 0 | caduca 19/8/26, 22:10

#### Premium a revisar

- DEL Etta Eyong | precio 25.480.174 EUR | valor 24.961.008 EUR | machine | pujas 0 | caduca 19/8/26, 22:10

#### Alertas

- Diatta: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

