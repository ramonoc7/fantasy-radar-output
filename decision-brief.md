# Brief Diario Ligas Fantasy

Datos API: 2026-08-21T10:41:06.584Z
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
- Valor plantilla: 219.293.425 EUR
- Jugadores plantilla: 19
- Mercado jugable: 18
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.819.609 EUR
- DEF Koski | Deportivo Alavés | 1.270.786 EUR
- DEF Nuñez | RCD Espanyol | 4.719.222 EUR
- DEF Suazo | Sevilla FC | 5.097.179 EUR
- DEF Davinchi | Getafe CF | 2.939.050 EUR
- DEF Javi Rueda | Celta | 4.421.919 EUR
- DEF Fran García | Real Betis | 9.421.201 EUR
- DEF Javi Rodríguez | Celta | 9.120.974 EUR
- CEN Maguette | R. Racing Club | 3.645.706 EUR
- CEN D. Villares | RC Deportivo | 2.236.844 EUR
- CEN Guido Rodríguez | Valencia CF | 23.907.357 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.052.146 EUR
- CEN Kubo | Real Sociedad | 26.198.445 EUR
- CEN Gorrotxa | Real Sociedad | 5.498.898 EUR | estado injured
- CEN Ibañez | Deportivo Alavés | 3.552.183 EUR
- DEL Dolan | RCD Espanyol | 7.468.384 EUR
- DEL Oyarzabal | Real Sociedad | 63.643.345 EUR
- DEL Hugo Duro | Valencia CF | 8.561.302 EUR
- DEL Miguel Rodríguez | Deportivo Alavés | 2.718.875 EUR

#### Mercado que caduca antes

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.259.116 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Guliashvili | precio 1.782.288 EUR | valor 1.730.668 EUR | machine | pujas 0 | caduca 21/8/26, 12:46 | estado injured
- CEN Redondo | precio 910.293 EUR | valor 955.215 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- DEF Manu Sánchez | precio 5.049.985 EUR | valor 4.956.547 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEF Diarra | precio 1.006.820 EUR | valor 1.006.795 EUR | machine | pujas 0 | caduca 21/8/26, 12:46 | estado out_of_league
- POR A. Fortuño | precio 512.928 EUR | valor 507.663 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN G. Villar | precio 6.565.088 EUR | valor 6.764.457 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 614.815 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.874 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Danjuma | precio 5.153.869 EUR | valor 5.118.174 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.105 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.130.792 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Baratos a revisar

- POR A. Fortuño | precio 512.928 EUR | valor 507.663 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 614.815 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN Redondo | precio 910.293 EUR | valor 955.215 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- CEN Mikel Rodriguez | precio 932.862 EUR | valor 1.052.146 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:31
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.874 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Miguel Rodríguez | precio 2.873.004 EUR | valor 2.718.875 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- DEF Davinchi | precio 2.992.221 EUR | valor 2.939.050 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:17
- CEN Maguette | precio 3.805.623 EUR | valor 3.645.706 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.130.792 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Premium a revisar

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.259.116 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.105 EUR | machine | pujas 0 | caduca 21/8/26, 12:46

#### Alertas

- Guliashvili: estado injured en mercado.
- Diarra: estado out_of_league en mercado.
- Rioja: estado doubtful en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 8.679.828 EUR
- Valor plantilla: 229.873.551 EUR
- Jugadores plantilla: 16
- Mercado jugable: 31
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.962.349 EUR
- DEF Djene | Getafe CF | 9.534.292 EUR
- DEF Kumbulla | Rayo Vallecano | 4.807.397 EUR | estado injured
- DEF Koski | Deportivo Alavés | 1.270.786 EUR
- DEF Huijsen | Real Madrid | 36.633.642 EUR
- DEF Álex Balde | FC Barcelona | 23.928.043 EUR
- CEN Moi Gómez | C.A. Osasuna | 1.808.554 EUR
- CEN Germán V. | Elche CF | 21.884.696 EUR
- CEN Izan M. | Málaga CF | 5.852.651 EUR
- CEN Mario Soriano | RC Deportivo | 28.264.293 EUR
- CEN D. Villares | RC Deportivo | 2.236.844 EUR
- CEN R. Terrats | Getafe CF | 3.351.430 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.402.219 EUR
- DEL Isi | Rayo Vallecano | 20.992.976 EUR | estado injured
- DEL T. Morente | Elche CF | 1.707.198 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.236.181 EUR

#### Mercado que caduca antes

- DEF Pedro Felipe | precio 2.238.799 EUR | valor 2.238.795 EUR | machine | pujas 0 | caduca 22/8/26, 10:53 | estado injured
- POR Courtois | precio 64.611.784 EUR | valor 64.611.387 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Juan Iglesias | precio 12.331.917 EUR | valor 12.331.839 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- POR P. Campos | precio 949.525 EUR | valor 949.523 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Jorge Salinas | precio 6.003.337 EUR | valor 6.003.211 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Á. Padilla | precio 1.069.903 EUR | valor 1.069.901 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Otu Jr | precio 1.089.277 EUR | valor 1.089.275 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Kang-In Lee | precio 40.801.578 EUR | valor 40.801.247 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Gerenabarrena | precio 1.227.028 EUR | valor 1.227.026 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Miguel Rodríguez | precio 2.718.884 EUR | valor 2.718.875 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL B. Mayoral | precio 2.708.402 EUR | valor 2.708.394 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.266.591 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 22/8/26, 11:09

#### Baratos a revisar

- POR P. Campos | precio 949.525 EUR | valor 949.523 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Pastor | precio 999.901 EUR | valor 375.738 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 23/8/26, 11:37
- DEL Á. Padilla | precio 1.069.903 EUR | valor 1.069.901 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Otu Jr | precio 1.089.277 EUR | valor 1.089.275 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Gerenabarrena | precio 1.227.028 EUR | valor 1.227.026 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.266.591 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- CEN Moi Gómez | precio 1.875.959 EUR | valor 1.808.554 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- CEN D. Villares | precio 2.329.238 EUR | valor 2.236.844 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEL B. Mayoral | precio 2.708.402 EUR | valor 2.708.394 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Miguel Rodríguez | precio 2.718.884 EUR | valor 2.718.875 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- POR J. Musso | precio 4.056.137 EUR | valor 3.969.401 EUR | rival | ofertas 1 | vende Archiking | caduca 23/8/26, 11:01

#### Premium a revisar

- POR Courtois | precio 64.611.784 EUR | valor 64.611.387 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Kang-In Lee | precio 40.801.578 EUR | valor 40.801.247 EUR | machine | pujas 0 | caduca 22/8/26, 10:53

#### Alertas

- Pedro Felipe: estado injured en mercado.
- Kumbulla: estado injured en mercado.
- Ruggeri: estado out_of_league en mercado.
- Lo Celso: estado injured en mercado.
- Yeremay: estado doubtful en mercado.
- R.P. Bigas: estado doubtful en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 58.014.963 EUR
- Valor plantilla: 177.960.143 EUR
- Jugadores plantilla: 16
- Mercado jugable: 16
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 22.578.331 EUR
- DEF C. Puga | Málaga CF | 4.981.996 EUR
- DEF Pablo Ramón | R. Racing Club | 611.586 EUR
- DEF Koski | Deportivo Alavés | 1.270.786 EUR
- DEF Hector Fort | FC Barcelona | 2.998.858 EUR
- DEF Javi Rodríguez | Celta | 9.120.974 EUR
- DEF Sergio Gómez | Real Sociedad | 17.552.034 EUR
- CEN R. Terrats | Getafe CF | 3.351.430 EUR
- CEN Javi Guerra | Valencia CF | 24.754.330 EUR
- CEN D. Villares | RC Deportivo | 2.236.844 EUR
- CEN Maguette | R. Racing Club | 3.645.706 EUR
- CEN Germán V. | Elche CF | 21.884.696 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.266.591 EUR
- DEL Chupe | Málaga CF | 46.156.210 EUR
- DEL Villalibre | R. Racing Club | 6.988.469 EUR
- DEL Hugo Duro | Valencia CF | 8.561.302 EUR

#### Mercado que caduca antes

- CEN Herrera | precio 2.945.641 EUR | valor 2.924.751 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Valverde | precio 71.728.607 EUR | valor 72.059.363 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEL Cala | precio 4.082.439 EUR | valor 4.101.845 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Rafa Rodríguez | precio 5.735.307 EUR | valor 5.589.382 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF De Las Sias | precio 566.156 EUR | valor 558.786 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Protesoni | precio 2.392.376 EUR | valor 2.328.098 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mella | precio 3.379.977 EUR | valor 3.349.604 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF Aramburu | precio 18.139.034 EUR | valor 18.273.627 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mangala | precio 10.638.278 EUR | valor 10.656.056 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Riquelme | precio 4.376.894 EUR | valor 4.461.207 EUR | machine | pujas 1 | caduca 21/8/26, 22:10
- CEN Óscar Valentín | precio 4.032.015 EUR | valor 4.147.093 EUR | machine | pujas 2 | caduca 21/8/26, 22:10
- DEF Bright Ede | precio 2.983.840 EUR | valor 3.103.033 EUR | machine | pujas 0 | caduca 21/8/26, 22:10

#### Baratos a revisar

- DEF De Las Sias | precio 566.156 EUR | valor 558.786 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Protesoni | precio 2.392.376 EUR | valor 2.328.098 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Herrera | precio 2.945.641 EUR | valor 2.924.751 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF Bright Ede | precio 2.983.840 EUR | valor 3.103.033 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mella | precio 3.379.977 EUR | valor 3.349.604 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Óscar Valentín | precio 4.032.015 EUR | valor 4.147.093 EUR | machine | pujas 2 | caduca 21/8/26, 22:10
- DEL Cala | precio 4.082.439 EUR | valor 4.101.845 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEL Alemâo | precio 4.344.584 EUR | valor 3.287.830 EUR | rival | ofertas 1 | vende Erdeivis22 | caduca 23/8/26, 9:03
- CEN Riquelme | precio 4.376.894 EUR | valor 4.461.207 EUR | machine | pujas 1 | caduca 21/8/26, 22:10

#### Premium a revisar

- CEN Valverde | precio 71.728.607 EUR | valor 72.059.363 EUR | machine | pujas 0 | caduca 21/8/26, 22:10

#### Alertas

- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

