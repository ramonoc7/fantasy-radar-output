# Brief Diario Ligas Fantasy

Datos API: 2026-08-20T17:26:30.361Z
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

- Saldo: 12.730.557 EUR
- Valor plantilla: 218.059.706 EUR
- Jugadores plantilla: 19
- Mercado jugable: 18
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.832.799 EUR
- DEF Koski | Deportivo Alavés | 1.152.978 EUR
- DEF Nuñez | RCD Espanyol | 4.477.902 EUR
- DEF Suazo | Sevilla FC | 5.148.334 EUR
- DEF Davinchi | Getafe CF | 2.967.998 EUR
- DEF Javi Rueda | Celta | 4.413.024 EUR
- DEF Fran García | Real Betis | 9.094.216 EUR
- DEF Javi Rodríguez | Celta | 9.072.000 EUR
- CEN Maguette | R. Racing Club | 3.720.017 EUR
- CEN D. Villares | RC Deportivo | 2.278.509 EUR
- CEN Guido Rodríguez | Valencia CF | 24.171.446 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 987.176 EUR
- CEN Kubo | Real Sociedad | 25.729.482 EUR
- CEN Gorrotxa | Real Sociedad | 5.643.341 EUR | estado injured
- CEN Ibañez | Deportivo Alavés | 3.466.395 EUR
- DEL Dolan | RCD Espanyol | 7.054.071 EUR
- DEL Oyarzabal | Real Sociedad | 63.522.612 EUR
- DEL Hugo Duro | Valencia CF | 8.534.584 EUR
- DEL Miguel Rodríguez | Deportivo Alavés | 2.792.822 EUR

#### Mercado que caduca antes

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.370.350 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Guliashvili | precio 1.782.288 EUR | valor 1.782.259 EUR | machine | pujas 0 | caduca 21/8/26, 12:46 | estado injured
- CEN Redondo | precio 910.293 EUR | valor 910.166 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- DEF Manu Sánchez | precio 5.049.985 EUR | valor 5.049.805 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEF Diarra | precio 1.006.820 EUR | valor 1.006.795 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR A. Fortuño | precio 512.928 EUR | valor 512.903 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN G. Villar | precio 6.565.088 EUR | valor 6.565.002 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 624.160 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.747.098 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Danjuma | precio 5.153.869 EUR | valor 5.153.583 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.889.628 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.238.005 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Baratos a revisar

- POR A. Fortuño | precio 512.928 EUR | valor 512.903 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 624.160 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN Redondo | precio 910.293 EUR | valor 910.166 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- CEN Mikel Rodriguez | precio 932.862 EUR | valor 987.176 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:31
- DEF Diarra | precio 1.006.820 EUR | valor 1.006.795 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.747.098 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Miguel Rodríguez | precio 2.873.004 EUR | valor 2.792.822 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- DEF Davinchi | precio 2.992.221 EUR | valor 2.967.998 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:17
- CEN Maguette | precio 3.805.623 EUR | valor 3.720.017 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.238.005 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Premium a revisar

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.370.350 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.889.628 EUR | machine | pujas 0 | caduca 21/8/26, 12:46

#### Alertas

- Guliashvili: estado injured en mercado.
- Rioja: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 4.158.068 EUR
- Valor plantilla: 233.317.949 EUR
- Jugadores plantilla: 17
- Mercado jugable: 30
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 41.309.381 EUR
- DEF Djene | Getafe CF | 9.363.599 EUR
- DEF Kumbulla | Rayo Vallecano | 4.960.718 EUR | estado injured
- DEF Koski | Deportivo Alavés | 1.152.978 EUR
- DEF Huijsen | Real Madrid | 35.898.422 EUR
- DEF Álex Balde | FC Barcelona | 23.792.166 EUR
- CEN Moi Gómez | C.A. Osasuna | 1.841.147 EUR
- CEN Germán V. | Elche CF | 22.180.122 EUR
- CEN Izan M. | Málaga CF | 5.926.845 EUR
- CEN Mario Soriano | RC Deportivo | 27.972.517 EUR
- CEN D. Villares | RC Deportivo | 2.278.509 EUR
- CEN Riquelme | Real Betis | 4.376.894 EUR
- CEN R. Terrats | Getafe CF | 3.274.338 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.395.423 EUR
- DEL Isi | Rayo Vallecano | 20.789.204 EUR
- DEL T. Morente | Elche CF | 1.738.130 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.067.556 EUR

#### Mercado que caduca antes

- CEN H. González | precio 1.341.507 EUR | valor 1.341.425 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Djalo | precio 940.313 EUR | valor 940.288 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Giuliano | precio 41.891.616 EUR | valor 41.889.628 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Catena | precio 32.769.715 EUR | valor 32.767.942 EUR | machine | pujas 1 | caduca 21/8/26, 10:53
- CEN Mangala | precio 10.638.969 EUR | valor 10.638.278 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.747.098 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN A. Vallecillo | precio 630.413 EUR | valor 630.388 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN G. Villar | precio 6.565.088 EUR | valor 6.565.002 EUR | machine | pujas 1 | caduca 21/8/26, 10:53
- DEL Cucho | precio 42.923.053 EUR | valor 42.920.800 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Maroan | precio 415.138 EUR | valor 415.113 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Marc Santos | precio 829.059 EUR | valor 829.034 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF El Hilali | precio 10.098.553 EUR | valor 10.097.368 EUR | machine | pujas 1 | caduca 21/8/26, 10:53

#### Baratos a revisar

- DEL Maroan | precio 415.138 EUR | valor 415.113 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN A. Vallecillo | precio 630.413 EUR | valor 630.388 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Marc Santos | precio 829.059 EUR | valor 829.034 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Djalo | precio 940.313 EUR | valor 940.288 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Pastor | precio 999.901 EUR | valor 375.481 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 23/8/26, 11:37
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.277.844 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- CEN H. González | precio 1.341.507 EUR | valor 1.341.425 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN Moi Gómez | precio 1.875.959 EUR | valor 1.841.147 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- CEN D. Villares | precio 2.329.238 EUR | valor 2.278.509 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.747.098 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- POR J. Musso | precio 4.056.137 EUR | valor 4.056.009 EUR | rival | ofertas 0 | vende Archiking | caduca 23/8/26, 11:01
- CEN Riquelme | precio 4.303.296 EUR | valor 4.376.894 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41

#### Premium a revisar

- DEL Cucho | precio 42.923.053 EUR | valor 42.920.800 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Giuliano | precio 41.891.616 EUR | valor 41.889.628 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Catena | precio 32.769.715 EUR | valor 32.767.942 EUR | machine | pujas 1 | caduca 21/8/26, 10:53

#### Alertas

- Kumbulla: estado injured en mercado.
- Ruggeri: estado out_of_league en mercado.
- Lo Celso: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 61.131.862 EUR
- Valor plantilla: 175.601.127 EUR
- Jugadores plantilla: 15
- Mercado jugable: 16
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 22.037.714 EUR
- DEF Sergio Gómez | Real Sociedad | 17.682.945 EUR
- DEF Javi Rodríguez | Celta | 9.072.000 EUR
- DEF C. Puga | Málaga CF | 4.962.335 EUR
- DEF Pablo Ramón | R. Racing Club | 579.263 EUR
- DEF Koski | Deportivo Alavés | 1.152.978 EUR
- CEN Germán V. | Elche CF | 22.180.122 EUR
- CEN Javi Guerra | Valencia CF | 24.637.219 EUR
- CEN Maguette | R. Racing Club | 3.720.017 EUR
- CEN D. Villares | RC Deportivo | 2.278.509 EUR
- CEN R. Terrats | Getafe CF | 3.274.338 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.277.844 EUR
- DEL Chupe | Málaga CF | 47.148.251 EUR
- DEL Villalibre | R. Racing Club | 7.063.008 EUR
- DEL Hugo Duro | Valencia CF | 8.534.584 EUR

#### Mercado que caduca antes

- POR A. Batalla | precio 38.760.030 EUR | valor 38.529.992 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- CEN Deossa | precio 2.100.772 EUR | valor 2.082.278 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- DEF Hector Fort | precio 3.116.810 EUR | valor 3.054.643 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- DEL Ez Abde | precio 42.067.743 EUR | valor 41.408.166 EUR | machine | pujas 0 | caduca 20/8/26, 22:10 | estado injured
- DEL Guedes | precio 30.272.184 EUR | valor 29.518.278 EUR | machine | pujas 0 | caduca 20/8/26, 22:10 | estado injured
- POR Agirrezabala | precio 3.542.354 EUR | valor 3.828.353 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- POR Bayindir | precio 2.240.016 EUR | valor 2.193.357 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- DEF Cuti Romero | precio 49.120.885 EUR | valor 47.545.944 EUR | machine | pujas 0 | caduca 20/8/26, 22:10 | estado doubtful
- DEF Abel Bretones | precio 4.026.622 EUR | valor 4.128.791 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- POR Padilla | precio 1.412.967 EUR | valor 1.381.412 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- DEL Paco Cortes | precio 753.220 EUR | valor 742.867 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- DEF M. Loureiro | precio 3.469.235 EUR | valor 3.379.674 EUR | machine | pujas 0 | caduca 20/8/26, 22:10

#### Baratos a revisar

- DEL Paco Cortes | precio 753.220 EUR | valor 742.867 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- POR Padilla | precio 1.412.967 EUR | valor 1.381.412 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- CEN Deossa | precio 2.100.772 EUR | valor 2.082.278 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- POR Bayindir | precio 2.240.016 EUR | valor 2.193.357 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- DEF Hector Fort | precio 3.116.810 EUR | valor 3.054.643 EUR | machine | pujas 1 | caduca 20/8/26, 22:10
- DEF M. Loureiro | precio 3.469.235 EUR | valor 3.379.674 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- POR Agirrezabala | precio 3.542.354 EUR | valor 3.828.353 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- DEF Abel Bretones | precio 4.026.622 EUR | valor 4.128.791 EUR | machine | pujas 0 | caduca 20/8/26, 22:10
- DEL Alemâo | precio 4.344.584 EUR | valor 3.344.476 EUR | rival | ofertas 0 | vende Erdeivis22 | caduca 23/8/26, 9:03

#### Premium a revisar

- POR A. Batalla | precio 38.760.030 EUR | valor 38.529.992 EUR | machine | pujas 1 | caduca 20/8/26, 22:10

#### Alertas

- Ez Abde: estado injured en mercado.
- Guedes: estado injured en mercado.
- Cuti Romero: estado doubtful en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

