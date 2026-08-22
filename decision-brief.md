# Brief Diario Ligas Fantasy

Datos API: 2026-08-22T10:35:17.472Z
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

- Saldo: 21.981.874 EUR
- Valor plantilla: 211.795.724 EUR
- Jugadores plantilla: 16
- Mercado jugable: 42
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.911.105 EUR
- DEF Koski | Deportivo Alavés | 1.427.042 EUR
- DEF Nuñez | RCD Espanyol | 5.048.751 EUR
- DEF Suazo | Sevilla FC | 5.000.863 EUR
- DEF Javi Rueda | Celta | 4.407.631 EUR
- DEF Fran García | Real Betis | 9.915.219 EUR
- DEF Javi Rodríguez | Celta | 9.095.395 EUR
- CEN D. Villares | RC Deportivo | 2.184.470 EUR
- CEN Guido Rodríguez | Valencia CF | 23.568.177 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.178.881 EUR
- CEN Kubo | Real Sociedad | 26.742.806 EUR
- CEN Gorrotxa | Real Sociedad | 5.334.012 EUR | estado injured
- CEN Ibañez | Deportivo Alavés | 3.696.817 EUR
- DEL Dolan | RCD Espanyol | 7.946.055 EUR
- DEL Oyarzabal | Real Sociedad | 63.786.340 EUR
- DEL Hugo Duro | Valencia CF | 8.552.160 EUR

#### Mercado que caduca antes

- CEN Javi Hernández | precio 9.720.017 EUR | valor 9.534.275 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Jauregi | precio 1.147.245 EUR | valor 1.117.835 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Paredes | precio 5.577.844 EUR | valor 5.583.671 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Rafita | precio 4.694.679 EUR | valor 4.641.938 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Diego López | precio 1.779.142 EUR | valor 1.726.754 EUR | machine | pujas 0 | caduca 22/8/26, 12:46 | estado injured
- CEN Carlos Martín | precio 2.006.245 EUR | valor 1.967.016 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Aubameyang | precio 39.711.492 EUR | valor 41.669.589 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Martim Neto | precio 1.622.431 EUR | valor 1.642.713 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- DEL Mikautadze | precio 65.316.052 EUR | valor 66.127.609 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Copete | precio 1.600.786 EUR | valor 1.553.234 EUR | machine | pujas 0 | caduca 22/8/26, 12:46 | estado injured
- CEN Hjulmand | precio 35.565.352 EUR | valor 34.780.563 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Salinas | precio 987.263 EUR | valor 967.013 EUR | machine | pujas 0 | caduca 22/8/26, 12:46

#### Baratos a revisar

- DEF Pastor | precio 375.736 EUR | valor 377.186 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51
- DEF Julio Díaz | precio 444.643 EUR | valor 443.337 EUR | rival | ofertas 0 | vende RauulCm_ | caduca 24/8/26, 15:51
- DEF Salinas | precio 987.263 EUR | valor 967.013 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Jauregi | precio 1.147.245 EUR | valor 1.117.835 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- CEN Martim Neto | precio 1.622.431 EUR | valor 1.642.713 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Carlos Martín | precio 2.006.245 EUR | valor 1.967.016 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- CEN D. Villares | precio 2.184.470 EUR | valor 2.184.470 EUR | rival | ofertas 0 | vende Ramounsitou | caduca 25/8/26, 10:02
- DEF Rafita | precio 4.694.679 EUR | valor 4.641.938 EUR | machine | pujas 0 | caduca 22/8/26, 12:46

#### Premium a revisar

- DEL Mikautadze | precio 65.316.052 EUR | valor 66.127.609 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- CEN Bernardo Silva | precio 60.074.100 EUR | valor 61.355.545 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51
- DEL Aubameyang | precio 39.711.492 EUR | valor 41.669.589 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Hjulmand | precio 35.565.352 EUR | valor 34.780.563 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Bartra | precio 26.687.165 EUR | valor 26.442.330 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51

#### Alertas

- Diego López: estado injured en mercado.
- Copete: estado injured en mercado.
- Gorrotxa: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 15.280.235 EUR
- Valor plantilla: 223.972.251 EUR
- Jugadores plantilla: 14
- Mercado jugable: 27
- Entrenadores ignorados: 1
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.587.556 EUR
- DEF Djene | Getafe CF | 9.678.830 EUR
- DEF Koski | Deportivo Alavés | 1.427.042 EUR
- DEF Huijsen | Real Madrid | 37.565.619 EUR
- DEF Álex Balde | FC Barcelona | 24.015.427 EUR
- CEN Germán V. | Elche CF | 21.573.797 EUR
- CEN Izan M. | Málaga CF | 5.728.328 EUR
- CEN Mario Soriano | RC Deportivo | 28.577.856 EUR
- CEN D. Villares | RC Deportivo | 2.184.470 EUR
- CEN R. Terrats | Getafe CF | 3.425.997 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.588.063 EUR
- DEL Isi | Rayo Vallecano | 20.500.048 EUR | estado injured
- DEL T. Morente | Elche CF | 1.673.329 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.445.889 EUR

#### Mercado que caduca antes

- CEN D. Villares | precio 2.329.238 EUR | valor 2.184.470 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEF Pau Navarro | precio 8.398.607 EUR | valor 7.795.382 EUR | rival | ofertas 1 | vende Rafishh | caduca 22/8/26, 20:14
- DEF Saba Sazonov | precio 1.041.227 EUR | valor 1.041.227 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF Einar | precio 3.740.735 EUR | valor 3.740.735 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- CEN G. Puerta | precio 14.159.811 EUR | valor 14.159.811 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- CEN Isco | precio 52.232.161 EUR | valor 52.232.161 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF Egiluz | precio 406.051 EUR | valor 406.051 EUR | machine | pujas 0 | caduca 23/8/26, 10:53 | estado injured
- CEN Iván Martín | precio 8.230.041 EUR | valor 8.230.041 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- POR Owono | precio 805.433 EUR | valor 805.433 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- CEN Puado | precio 5.240.261 EUR | valor 5.240.261 EUR | machine | pujas 1 | caduca 23/8/26, 10:53 | estado injured
- DEL Diego López | precio 1.726.754 EUR | valor 1.726.754 EUR | machine | pujas 0 | caduca 23/8/26, 10:53 | estado injured
- CEN Tchouaméni | precio 38.562.545 EUR | valor 38.562.545 EUR | machine | pujas 0 | caduca 23/8/26, 10:53 | estado injured

#### Baratos a revisar

- POR Owono | precio 805.433 EUR | valor 805.433 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF J. Vertrouwd | precio 888.365 EUR | valor 888.365 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF Pastor | precio 999.901 EUR | valor 377.186 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 23/8/26, 11:37
- DEF Saba Sazonov | precio 1.041.227 EUR | valor 1.041.227 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- CEN D. Villares | precio 2.329.238 EUR | valor 2.184.470 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEF Pacheco | precio 3.651.333 EUR | valor 3.651.333 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF Einar | precio 3.740.735 EUR | valor 3.740.735 EUR | machine | pujas 0 | caduca 23/8/26, 10:53

#### Premium a revisar

- CEN Isco | precio 52.232.161 EUR | valor 52.232.161 EUR | machine | pujas 0 | caduca 23/8/26, 10:53
- DEF Grimaldo | precio 45.818.609 EUR | valor 45.218.561 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 24/8/26, 16:10

#### Alertas

- Egiluz: estado injured en mercado.
- Puado: estado injured en mercado.
- Diego López: estado injured en mercado.
- Tchouaméni: estado injured en mercado.
- Yeremay: estado doubtful en mercado.
- R.P. Bigas: estado doubtful en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: 3.390.829 EUR
- Valor plantilla: 232.644.420 EUR
- Jugadores plantilla: 12
- Mercado jugable: 15
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 23.193.054 EUR
- DEF Sergio Gómez | Real Sociedad | 17.471.490 EUR
- DEF Javi Rodríguez | Celta | 9.095.395 EUR
- DEF C. Puga | Málaga CF | 4.982.161 EUR
- DEF Pablo Ramón | R. Racing Club | 632.605 EUR
- DEF Koski | Deportivo Alavés | 1.427.042 EUR
- CEN Germán V. | Elche CF | 21.573.797 EUR
- CEN Javi Guerra | Valencia CF | 24.792.599 EUR
- CEN R. Terrats | Getafe CF | 3.425.997 EUR
- CEN Valverde | Real Madrid | 72.420.699 EUR
- DEL Chupe | Málaga CF | 45.077.421 EUR
- DEL Hugo Duro | Valencia CF | 8.552.160 EUR

#### Mercado que caduca antes

- DEL Fer Niño | precio 13.543.677 EUR | valor 13.279.508 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- POR Letacek | precio 635.904 EUR | valor 626.948 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Denis Suárez | precio 2.345.839 EUR | valor 2.371.784 EUR | machine | pujas 2 | caduca 22/8/26, 22:10
- DEF Jose Angel | precio 622.196 EUR | valor 613.788 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Lemar | precio 4.549.837 EUR | valor 4.423.322 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Isco | precio 52.648.042 EUR | valor 52.232.161 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Goti | precio 2.165.086 EUR | valor 2.099.491 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Nordin Al-Lal | precio 481.126 EUR | valor 478.361 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Arnau Ortiz | precio 1.224.576 EUR | valor 1.250.234 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Diakhaby | precio 5.228.660 EUR | valor 5.113.643 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF J. Berrocal | precio 1.389.303 EUR | valor 1.350.211 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Robbie Ure | precio 14.036.064 EUR | valor 12.253.066 EUR | rival | ofertas 1 | vende Erdeivis22 | caduca 23/8/26, 9:07

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 481.126 EUR | valor 478.361 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Jose Angel | precio 622.196 EUR | valor 613.788 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- POR Letacek | precio 635.904 EUR | valor 626.948 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Arnau Ortiz | precio 1.224.576 EUR | valor 1.250.234 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF J. Berrocal | precio 1.389.303 EUR | valor 1.350.211 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Goti | precio 2.165.086 EUR | valor 2.099.491 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Denis Suárez | precio 2.345.839 EUR | valor 2.371.784 EUR | machine | pujas 2 | caduca 22/8/26, 22:10
- CEN Lemar | precio 4.549.837 EUR | valor 4.423.322 EUR | machine | pujas 0 | caduca 22/8/26, 22:10

#### Premium a revisar

- CEN Isco | precio 52.648.042 EUR | valor 52.232.161 EUR | machine | pujas 0 | caduca 22/8/26, 22:10

#### Alertas

- Ruggeri: estado out_of_league en mercado.
- Cabrera: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

