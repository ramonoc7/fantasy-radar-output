# Brief Diario Ligas Fantasy

Datos API: 2026-08-21T07:53:14.106Z
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
- Valor plantilla: 219.295.525 EUR
- Jugadores plantilla: 19
- Mercado jugable: 18
- Entrenadores ignorados: 2
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.819.776 EUR
- DEF Koski | Deportivo Alavés | 1.270.806 EUR
- DEF Nuñez | RCD Espanyol | 4.719.275 EUR
- DEF Suazo | Sevilla FC | 5.097.265 EUR
- DEF Davinchi | Getafe CF | 2.939.061 EUR
- DEF Javi Rueda | Celta | 4.422.008 EUR
- DEF Fran García | Real Betis | 9.421.287 EUR
- DEF Javi Rodríguez | Celta | 9.121.026 EUR
- CEN Maguette | R. Racing Club | 3.645.715 EUR
- CEN D. Villares | RC Deportivo | 2.236.850 EUR
- CEN Guido Rodríguez | Valencia CF | 23.907.445 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.052.159 EUR
- CEN Kubo | Real Sociedad | 26.199.258 EUR
- CEN Gorrotxa | Real Sociedad | 5.498.908 EUR | estado injured
- CEN Ibañez | Deportivo Alavés | 3.552.306 EUR
- DEL Dolan | RCD Espanyol | 7.468.471 EUR
- DEL Oyarzabal | Real Sociedad | 63.643.677 EUR
- DEL Hugo Duro | Valencia CF | 8.561.348 EUR
- DEL Miguel Rodríguez | Deportivo Alavés | 2.718.884 EUR

#### Mercado que caduca antes

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.259.734 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Guliashvili | precio 1.782.288 EUR | valor 1.730.670 EUR | machine | pujas 0 | caduca 21/8/26, 12:46 | estado injured
- CEN Redondo | precio 910.293 EUR | valor 955.225 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- DEF Manu Sánchez | precio 5.049.985 EUR | valor 4.956.561 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEF Diarra | precio 1.006.820 EUR | valor 981.801 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR A. Fortuño | precio 512.928 EUR | valor 507.665 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN G. Villar | precio 6.565.088 EUR | valor 6.764.600 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 614.821 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.880 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Danjuma | precio 5.153.869 EUR | valor 5.118.316 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.229 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.130.819 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Baratos a revisar

- POR A. Fortuño | precio 512.928 EUR | valor 507.665 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- POR Fran González | precio 624.187 EUR | valor 614.821 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- CEN Redondo | precio 910.293 EUR | valor 955.225 EUR | machine | pujas 1 | caduca 21/8/26, 12:46
- CEN Mikel Rodriguez | precio 932.862 EUR | valor 1.052.159 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:31
- DEF Diarra | precio 1.006.820 EUR | valor 981.801 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.880 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Miguel Rodríguez | precio 2.873.004 EUR | valor 2.718.884 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- DEF Davinchi | precio 2.992.221 EUR | valor 2.939.061 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:17
- CEN Maguette | precio 3.805.623 EUR | valor 3.645.715 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 20:27
- POR A. Ferllo | precio 4.483.208 EUR | valor 4.130.819 EUR | rival | ofertas 1 | vende Rubio 05 | caduca 21/8/26, 18:36

#### Premium a revisar

- DEL Lamine Yamal | precio 126.378.854 EUR | valor 126.259.734 EUR | machine | pujas 0 | caduca 21/8/26, 12:46
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.229 EUR | machine | pujas 0 | caduca 21/8/26, 12:46

#### Alertas

- Guliashvili: estado injured en mercado.
- Rioja: estado injured en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 8.679.828 EUR
- Valor plantilla: 229.874.998 EUR
- Jugadores plantilla: 16
- Mercado jugable: 32
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.962.512 EUR
- DEF Djene | Getafe CF | 9.534.360 EUR
- DEF Kumbulla | Rayo Vallecano | 4.807.404 EUR | estado injured
- DEF Koski | Deportivo Alavés | 1.270.806 EUR
- DEF Huijsen | Real Madrid | 36.633.913 EUR
- DEF Álex Balde | FC Barcelona | 23.928.179 EUR
- CEN Moi Gómez | C.A. Osasuna | 1.808.559 EUR
- CEN Germán V. | Elche CF | 21.884.770 EUR
- CEN Izan M. | Málaga CF | 5.852.672 EUR
- CEN Mario Soriano | RC Deportivo | 28.264.470 EUR
- CEN D. Villares | RC Deportivo | 2.236.850 EUR
- CEN R. Terrats | Getafe CF | 3.351.513 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.402.369 EUR
- DEL Isi | Rayo Vallecano | 20.993.105 EUR | estado injured
- DEL T. Morente | Elche CF | 1.707.214 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.236.302 EUR

#### Mercado que caduca antes

- CEN H. González | precio 1.341.507 EUR | valor 1.338.423 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Djalo | precio 940.313 EUR | valor 917.954 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.229 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Catena | precio 32.769.715 EUR | valor 32.641.170 EUR | machine | pujas 1 | caduca 21/8/26, 10:53
- CEN Mangala | precio 10.638.969 EUR | valor 10.656.112 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.880 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN A. Vallecillo | precio 630.413 EUR | valor 620.450 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN G. Villar | precio 6.565.088 EUR | valor 6.764.600 EUR | machine | pujas 2 | caduca 21/8/26, 10:53
- DEL Cucho | precio 42.923.053 EUR | valor 42.549.515 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Maroan | precio 415.138 EUR | valor 413.786 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Marc Santos | precio 829.059 EUR | valor 811.150 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF El Hilali | precio 10.098.553 EUR | valor 10.451.843 EUR | machine | pujas 2 | caduca 21/8/26, 10:53

#### Baratos a revisar

- DEL Maroan | precio 415.138 EUR | valor 413.786 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN A. Vallecillo | precio 630.413 EUR | valor 620.450 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Marc Santos | precio 829.059 EUR | valor 811.150 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Djalo | precio 940.313 EUR | valor 917.954 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Pastor | precio 999.901 EUR | valor 375.740 EUR | rival | ofertas 0 | vende Gabriele28 | caduca 23/8/26, 11:37
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.266.609 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- CEN H. González | precio 1.341.507 EUR | valor 1.338.423 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- CEN Moi Gómez | precio 1.875.959 EUR | valor 1.808.559 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- CEN D. Villares | precio 2.329.238 EUR | valor 2.236.850 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEL Tsitaishvili | precio 2.747.134 EUR | valor 2.685.880 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- POR J. Musso | precio 4.056.137 EUR | valor 3.969.041 EUR | rival | ofertas 0 | vende Archiking | caduca 23/8/26, 11:01

#### Premium a revisar

- DEL Cucho | precio 42.923.053 EUR | valor 42.549.515 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEL Giuliano | precio 41.891.616 EUR | valor 41.207.229 EUR | machine | pujas 0 | caduca 21/8/26, 10:53
- DEF Catena | precio 32.769.715 EUR | valor 32.641.170 EUR | machine | pujas 1 | caduca 21/8/26, 10:53

#### Alertas

- Kumbulla: estado injured en mercado.
- Ruggeri: estado out_of_league en mercado.
- Lo Celso: estado injured en mercado.
- Yeremay: estado doubtful en mercado.
- R.P. Bigas: estado doubtful en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 58.014.963 EUR
- Valor plantilla: 177.961.418 EUR
- Jugadores plantilla: 16
- Mercado jugable: 16
- Entrenadores ignorados: 1
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 22.578.908 EUR
- DEF C. Puga | Málaga CF | 4.982.023 EUR
- DEF Pablo Ramón | R. Racing Club | 611.593 EUR
- DEF Koski | Deportivo Alavés | 1.270.806 EUR
- DEF Hector Fort | FC Barcelona | 2.998.866 EUR
- DEF Javi Rodríguez | Celta | 9.121.026 EUR
- DEF Sergio Gómez | Real Sociedad | 17.552.106 EUR
- CEN R. Terrats | Getafe CF | 3.351.513 EUR
- CEN Javi Guerra | Valencia CF | 24.754.468 EUR
- CEN D. Villares | RC Deportivo | 2.236.850 EUR
- CEN Maguette | R. Racing Club | 3.645.715 EUR
- CEN Germán V. | Elche CF | 21.884.770 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.266.609 EUR
- DEL Chupe | Málaga CF | 46.156.322 EUR
- DEL Villalibre | R. Racing Club | 6.988.495 EUR
- DEL Hugo Duro | Valencia CF | 8.561.348 EUR

#### Mercado que caduca antes

- CEN Herrera | precio 2.945.641 EUR | valor 2.924.797 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Valverde | precio 71.728.607 EUR | valor 72.059.762 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEL Cala | precio 4.082.439 EUR | valor 4.101.867 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Rafa Rodríguez | precio 5.735.307 EUR | valor 5.589.393 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF De Las Sias | precio 566.156 EUR | valor 558.788 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Protesoni | precio 2.392.376 EUR | valor 2.328.105 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mella | precio 3.379.977 EUR | valor 3.349.617 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF Aramburu | precio 18.139.034 EUR | valor 18.273.734 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mangala | precio 10.638.278 EUR | valor 10.656.112 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Riquelme | precio 4.376.894 EUR | valor 4.461.240 EUR | machine | pujas 1 | caduca 21/8/26, 22:10
- CEN Óscar Valentín | precio 4.032.015 EUR | valor 4.146.837 EUR | machine | pujas 2 | caduca 21/8/26, 22:10
- DEF Bright Ede | precio 2.983.840 EUR | valor 3.103.062 EUR | machine | pujas 0 | caduca 21/8/26, 22:10

#### Baratos a revisar

- DEF De Las Sias | precio 566.156 EUR | valor 558.788 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Protesoni | precio 2.392.376 EUR | valor 2.328.105 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Herrera | precio 2.945.641 EUR | valor 2.924.797 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEF Bright Ede | precio 2.983.840 EUR | valor 3.103.062 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Mella | precio 3.379.977 EUR | valor 3.349.617 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- CEN Óscar Valentín | precio 4.032.015 EUR | valor 4.146.837 EUR | machine | pujas 2 | caduca 21/8/26, 22:10
- DEL Cala | precio 4.082.439 EUR | valor 4.101.867 EUR | machine | pujas 0 | caduca 21/8/26, 22:10
- DEL Alemâo | precio 4.344.584 EUR | valor 3.287.840 EUR | rival | ofertas 1 | vende Erdeivis22 | caduca 23/8/26, 9:03
- CEN Riquelme | precio 4.376.894 EUR | valor 4.461.240 EUR | machine | pujas 1 | caduca 21/8/26, 22:10

#### Premium a revisar

- CEN Valverde | precio 71.728.607 EUR | valor 72.059.762 EUR | machine | pujas 0 | caduca 21/8/26, 22:10

#### Alertas

- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

