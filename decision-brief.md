# Brief Diario Ligas Fantasy

Datos API: 2026-08-21T20:36:20.313Z
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
- Valor plantilla: 209.990.332 EUR
- Jugadores plantilla: 16
- Mercado jugable: 41
- Entrenadores ignorados: 1
- Estrategia: Arreglar porteria y defensa sin desmontar activos caros; convertir dinero concentrado en titulares baratos utiles.

#### Plantilla

- POR Á. Valles | Real Betis | 33.821.088 EUR
- DEF Koski | Deportivo Alavés | 1.270.836 EUR
- DEF Nuñez | RCD Espanyol | 4.719.283 EUR
- DEF Suazo | Sevilla FC | 5.097.160 EUR
- DEF Javi Rueda | Celta | 4.421.896 EUR
- DEF Fran García | Real Betis | 9.420.754 EUR
- DEF Javi Rodríguez | Celta | 9.120.814 EUR
- CEN D. Villares | RC Deportivo | 2.236.837 EUR
- CEN Guido Rodríguez | Valencia CF | 23.907.269 EUR
- CEN Mikel Rodriguez | Deportivo Alavés | 1.052.105 EUR
- CEN Kubo | Real Sociedad | 26.198.257 EUR
- CEN Gorrotxa | Real Sociedad | 5.498.888 EUR | estado injured
- CEN Ibañez | Deportivo Alavés | 3.552.319 EUR
- DEL Dolan | RCD Espanyol | 7.468.559 EUR
- DEL Oyarzabal | Real Sociedad | 63.643.011 EUR
- DEL Hugo Duro | Valencia CF | 8.561.256 EUR

#### Mercado que caduca antes

- CEN Javi Hernández | precio 9.720.017 EUR | valor 9.720.017 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Jauregi | precio 1.147.245 EUR | valor 1.147.245 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Paredes | precio 5.577.844 EUR | valor 5.577.844 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Rafita | precio 4.694.679 EUR | valor 4.694.679 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Diego López | precio 1.779.142 EUR | valor 1.779.142 EUR | machine | pujas 0 | caduca 22/8/26, 12:46 | estado injured
- CEN Carlos Martín | precio 2.006.245 EUR | valor 2.006.245 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Aubameyang | precio 39.711.492 EUR | valor 39.711.492 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Martim Neto | precio 1.622.431 EUR | valor 1.622.431 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- DEL Mikautadze | precio 65.316.052 EUR | valor 65.316.052 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Copete | precio 1.600.786 EUR | valor 1.600.786 EUR | machine | pujas 0 | caduca 22/8/26, 12:46 | estado injured
- CEN Hjulmand | precio 35.565.352 EUR | valor 35.565.352 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Salinas | precio 987.263 EUR | valor 987.263 EUR | machine | pujas 0 | caduca 22/8/26, 12:46

#### Baratos a revisar

- DEF Pastor | precio 375.736 EUR | valor 375.736 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51
- DEF Julio Díaz | precio 444.643 EUR | valor 444.643 EUR | rival | ofertas 0 | vende RauulCm_ | caduca 24/8/26, 15:51
- DEF Salinas | precio 987.263 EUR | valor 987.263 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEL Jauregi | precio 1.147.245 EUR | valor 1.147.245 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- CEN Martim Neto | precio 1.622.431 EUR | valor 1.622.431 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Carlos Martín | precio 2.006.245 EUR | valor 2.006.245 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Rafita | precio 4.694.679 EUR | valor 4.694.679 EUR | machine | pujas 0 | caduca 22/8/26, 12:46

#### Premium a revisar

- DEL Mikautadze | precio 65.316.052 EUR | valor 65.316.052 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- CEN Bernardo Silva | precio 60.074.100 EUR | valor 60.074.100 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51
- DEL Aubameyang | precio 39.711.492 EUR | valor 39.711.492 EUR | machine | pujas 1 | caduca 22/8/26, 12:46
- CEN Hjulmand | precio 35.565.352 EUR | valor 35.565.352 EUR | machine | pujas 0 | caduca 22/8/26, 12:46
- DEF Bartra | precio 26.687.165 EUR | valor 26.687.165 EUR | rival | ofertas 0 | vende Carlos___80 | caduca 24/8/26, 15:51

#### Alertas

- Diego López: estado injured en mercado.
- Copete: estado injured en mercado.
- Gorrotxa: estado injured en mercado.
- Hay 1 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Fantasmas League

- Saldo: 13.470.699 EUR
- Valor plantilla: 225.064.164 EUR
- Jugadores plantilla: 15
- Mercado jugable: 29
- Entrenadores ignorados: 2
- Estrategia: Construir un equipo ganador priorizando 11 titulares reales, gangas de mercado y revalorizacion.

#### Plantilla

- POR Remiro | Real Sociedad | 40.961.775 EUR
- DEF Djene | Getafe CF | 9.533.844 EUR
- DEF Koski | Deportivo Alavés | 1.270.836 EUR
- DEF Huijsen | Real Madrid | 36.633.370 EUR
- DEF Álex Balde | FC Barcelona | 23.927.906 EUR
- CEN Moi Gómez | C.A. Osasuna | 1.808.537 EUR
- CEN Germán V. | Elche CF | 21.884.622 EUR
- CEN Izan M. | Málaga CF | 5.852.631 EUR
- CEN Mario Soriano | RC Deportivo | 28.264.117 EUR
- CEN D. Villares | RC Deportivo | 2.236.837 EUR
- CEN R. Terrats | Getafe CF | 3.351.404 EUR
- DEL Ángel Pérez | Deportivo Alavés | 6.402.186 EUR
- DEL Isi | Rayo Vallecano | 20.992.846 EUR | estado injured
- DEL T. Morente | Elche CF | 1.707.194 EUR
- DEL Iñigo Vicente | R. Racing Club | 20.236.059 EUR

#### Mercado que caduca antes

- DEF Pedro Felipe | precio 2.238.799 EUR | valor 2.238.792 EUR | machine | pujas 0 | caduca 22/8/26, 10:53 | estado injured
- POR Courtois | precio 64.611.784 EUR | valor 64.614.999 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Juan Iglesias | precio 12.331.917 EUR | valor 12.331.573 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- POR P. Campos | precio 949.525 EUR | valor 949.521 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Jorge Salinas | precio 6.003.337 EUR | valor 6.003.084 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Á. Padilla | precio 1.069.903 EUR | valor 1.069.899 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Otu Jr | precio 1.089.277 EUR | valor 1.089.273 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Kang-In Lee | precio 40.801.578 EUR | valor 40.801.614 EUR | machine | pujas 1 | caduca 22/8/26, 10:53
- CEN Gerenabarrena | precio 1.227.028 EUR | valor 1.227.012 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Miguel Rodríguez | precio 2.718.884 EUR | valor 2.718.871 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL B. Mayoral | precio 2.708.402 EUR | valor 2.708.386 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.266.586 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 22/8/26, 11:09

#### Baratos a revisar

- POR P. Campos | precio 949.525 EUR | valor 949.521 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Pastor | precio 999.901 EUR | valor 375.736 EUR | rival | ofertas 1 | vende Gabriele28 | caduca 23/8/26, 11:37
- DEL Á. Padilla | precio 1.069.903 EUR | valor 1.069.899 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Otu Jr | precio 1.089.277 EUR | valor 1.089.273 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Gerenabarrena | precio 1.227.028 EUR | valor 1.227.012 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- CEN Iker Muñoz | precio 1.293.450 EUR | valor 1.266.586 EUR | rival | ofertas 1 | vende Mynavo Kyiv | caduca 22/8/26, 11:09
- CEN Moi Gómez | precio 1.875.959 EUR | valor 1.808.537 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- CEN D. Villares | precio 2.329.238 EUR | valor 2.236.837 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 22/8/26, 14:41
- DEL B. Mayoral | precio 2.708.402 EUR | valor 2.708.386 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEL Miguel Rodríguez | precio 2.718.884 EUR | valor 2.718.871 EUR | machine | pujas 0 | caduca 22/8/26, 10:53

#### Premium a revisar

- POR Courtois | precio 64.611.784 EUR | valor 64.614.999 EUR | machine | pujas 0 | caduca 22/8/26, 10:53
- DEF Grimaldo | precio 45.818.609 EUR | valor 45.818.609 EUR | rival | ofertas 0 | vende Mynavo Kyiv | caduca 24/8/26, 16:10
- CEN Kang-In Lee | precio 40.801.578 EUR | valor 40.801.614 EUR | machine | pujas 1 | caduca 22/8/26, 10:53

#### Alertas

- Pedro Felipe: estado injured en mercado.
- Yeremay: estado doubtful en mercado.
- R.P. Bigas: estado doubtful en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

### Los Mastuerzos

- Saldo: -14.048.436 EUR
- Valor plantilla: 250.022.177 EUR
- Jugadores plantilla: 17
- Mercado jugable: 21
- Entrenadores ignorados: 2
- Estrategia: Solucionar porteria y tercer defensa, manteniendo un centro del campo barato y muy util; cazar gangas antes que perseguir nombres caros.

#### Plantilla

- POR David Soria | Getafe CF | 22.577.754 EUR
- DEF Sergio Gómez | Real Sociedad | 17.551.962 EUR
- DEF Javi Rodríguez | Celta | 9.120.814 EUR
- DEF C. Puga | Málaga CF | 4.981.968 EUR
- DEF Pablo Ramón | R. Racing Club | 611.592 EUR
- DEF Hector Fort | FC Barcelona | 2.998.849 EUR
- DEF Koski | Deportivo Alavés | 1.270.836 EUR
- CEN Germán V. | Elche CF | 21.884.622 EUR
- CEN Javi Guerra | Valencia CF | 24.754.192 EUR
- CEN Maguette | R. Racing Club | 3.645.696 EUR
- CEN D. Villares | RC Deportivo | 2.236.837 EUR
- CEN R. Terrats | Getafe CF | 3.351.404 EUR
- CEN Valverde | Real Madrid | 72.063.324 EUR
- CEN Iker Muñoz | C.A. Osasuna | 1.266.586 EUR
- DEL Chupe | Málaga CF | 46.156.098 EUR
- DEL Villalibre | R. Racing Club | 6.988.387 EUR
- DEL Hugo Duro | Valencia CF | 8.561.256 EUR

#### Mercado que caduca antes

- DEL Fer Niño | precio 13.543.677 EUR | valor 13.543.677 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- POR Letacek | precio 635.904 EUR | valor 635.904 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Denis Suárez | precio 2.345.839 EUR | valor 2.345.839 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Jose Angel | precio 622.196 EUR | valor 622.196 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Lemar | precio 4.549.837 EUR | valor 4.549.837 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Isco | precio 52.648.042 EUR | valor 52.648.042 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Goti | precio 2.165.086 EUR | valor 2.165.086 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Nordin Al-Lal | precio 481.126 EUR | valor 481.126 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Arnau Ortiz | precio 1.224.576 EUR | valor 1.224.576 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Diakhaby | precio 5.228.660 EUR | valor 5.228.660 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF J. Berrocal | precio 1.389.303 EUR | valor 1.389.303 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Robbie Ure | precio 14.036.064 EUR | valor 12.146.361 EUR | rival | ofertas 1 | vende Erdeivis22 | caduca 23/8/26, 9:07

#### Baratos a revisar

- DEL Nordin Al-Lal | precio 481.126 EUR | valor 481.126 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Pablo Ramón | precio 611.592 EUR | valor 611.592 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 24/8/26, 19:15
- DEF Jose Angel | precio 622.196 EUR | valor 622.196 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- POR Letacek | precio 635.904 EUR | valor 635.904 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEL Arnau Ortiz | precio 1.224.576 EUR | valor 1.224.576 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Iker Muñoz | precio 1.266.586 EUR | valor 1.266.586 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 24/8/26, 19:15
- DEF J. Berrocal | precio 1.389.303 EUR | valor 1.389.303 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN Goti | precio 2.165.086 EUR | valor 2.165.086 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- CEN D. Villares | precio 2.236.837 EUR | valor 2.236.837 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 24/8/26, 19:15
- CEN Denis Suárez | precio 2.345.839 EUR | valor 2.345.839 EUR | machine | pujas 0 | caduca 22/8/26, 22:10
- DEF Hector Fort | precio 2.998.849 EUR | valor 2.998.849 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 24/8/26, 19:12
- CEN Maguette | precio 3.645.696 EUR | valor 3.645.696 EUR | rival | ofertas 1 | vende Ramounsitou | caduca 24/8/26, 17:36

#### Premium a revisar

- CEN Isco | precio 52.648.042 EUR | valor 52.648.042 EUR | machine | pujas 0 | caduca 22/8/26, 22:10

#### Alertas

- Saldo negativo: hay que volver a positivo antes del inicio de jornada.
- Ruggeri: estado out_of_league en mercado.
- Cabrera: estado suspended en mercado.
- Hay 2 entrenadores en mercado: ignorar por funcion Premium bloqueada.

