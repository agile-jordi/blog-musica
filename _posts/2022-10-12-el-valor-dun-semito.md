---
layout: music
title:  "El valor d'un semitò"
date:   2022-10-12
categories: musica
author: 'Jordi'
excerpt_separator: <!--more-->
tags: notes
---

Avui faré un passeig curt per les matemàtiques de la música. Si no t'agraden les matemàtiques, te'l pots saltar, perquè res del que posaré aquí surt als llibres de música que llegeixo ni res és necessari per a entendre la música... <!--more--> a menys que vulguis entendre bé aquesta frase:

> Podríem pensar que les freqüències entre els dos La de l’exemple es reparteixen de forma equitativa entre els 6 espais entre notes… però no és així. De fet, al piano,  entre una nota i la segúent del mateix nom (entre el Do i el Do de la  figura de dalt, per exemple), hi ha 12 tecles, no pas només set: les set blanques i cinc tecles negres.

Tal com [vaig explicar](../2022-10-10/el-nom-de-les-notes) si una nota té una certa freqüència x, com el La, que té 440 Hz de freqüència, la nota que té el doble de freqüència es diu igual i està separada per 12 semitons de distància de la primera. Això em porta a preguntar-me, puc calcular les freqüències de les notes intermitges?

| Nota                    | Freqüència |
| ----------------------- | ---------- |
| La4                     | 440 Hz     |
| La4 + 1 semitò          | ?          |
| ...                     | ?          |
| La4 + 11 semitons       | ?          |
| L 4 + 12 semitons (La5) | 440 Hz * 2 |

Com que de La a La el que fem no és sumar una certa freqüència sinó multiplicar per 2, és fàcil arribar a la conclusió que a cada semitò el que fem és multiplicar la freqüència anterior per una certa constant _C_. Aquest valor, el valor pel que multiplica un semitò la freqüència d'un so, és el que busco.

Pensant en aquest factor multiplicatiu, podem reescriure la taula anterior com: 

| Nota           | Freqüència   |
| -------------- | ------------ |
| La4            | 440 Hz       |
| La4 + 1 semitò | 440 Hz * C = 440 Hz * C<sup>1</sup> |
| La4 + 2 semitons | (440 Hz * C) * C = 440 Hz * C<sup>2</sup> |
| ...                     | ...          |
| L 4 + 12 semitons (La5) | 440 Hz * C<sup>12</sup> = 440 Hz * 2 |

Per tant, podem concloure que 2 = C<sup>12</sup> i, per tant, que C = 2<sup>1/12</sup> que és l'arrel dotzena de 2; literalment, el número que cal multiplicar per ell mateix 12 vegades per obtenir un 2. I si el calculem, és aproximadament 1,059463.

1,059463. Apa, ja puc dormir tranquil. Demà més.

---

La solució la vaig trobar en [aquest article](https://www.ams.jhu.edu/dan-mathofmusic/notes-intervals/) (en anglès) de la mateixa web que un altre que ja vaig citar. 



