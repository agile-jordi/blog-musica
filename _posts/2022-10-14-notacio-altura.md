---
layout: music
title: El pentagrama i l'altura de les notes
date: 2022-10-14
categories: musica
author: Jordi
excerpt_separator: <!--more-->
tags:
  - melodia
  - notació
aliases:
  - El pentagrama i l'altura de les notes
---

En anteriors articles de melodia he parlat del [nom de les notes](2022-10-10-el-nom-de-les-notes), de les [alteracions](2022-10-13-te-bemolls-i-sostinguts) i fins i tot he calculat la [mesura física d'un semitò](2022-10-12-el-valor-dun-semito). Vegem ara com s'escriuen aquestes notes en una partitura. <!--more-->

🚨 Alerta! En aquest article, quan mencioni l'[índex acústic](https://es.wikipedia.org/wiki/%C3%8Dndice_ac%C3%BAstico) d'una nota, el numeret que indica l'octava a la qual pertany la nota, ho faré en el sistema internacional, no en el sistema franco-belga en ús a Espanya.

La notació de l'altura de les notes a una partitura es fa escrivint-les a més o menys altura del pentagrama, un conjunt de 5 línies horitzontals que té el seu origen a l'Edat Mitjana:

```music
E F G A B C5 D E F
```
Pentagrama amb notes a diverses altures
{:.figcaption}

El principi és ben senzill. Cada símbol de nota es representa exactament sobre una de les línies o bé exactament a l'espai entre dues línies. Com que enlloc de tractar les 12 possibles notes d'una octava amb la mateixa precedència n'hi ha 7 que tenen nom, només aquestes 7 tenen el seu propi lloc reservat al pentagrama. Cada vegada que pugem d'un espai a la línia del damunt o d'una línia a l'espai del damunt estem pujant una nota.

Però quina nota representa al símbol que està al primer espai entre la quarta i la cinquena línia (entre les dues línies de dalt), per exemple? 

```music
E5
```
Pentagrama amb nota entre la quarta i cinquena línies
{:.figcaption}

Doncs depèn. De moment n'hi ha prou a dir que si afegim el símbol de la clau de Sol a la partitura podem afirmar sense dubtes que la nota representada entre la quarta i cinquena línies és un Mi5[^1].  Aleshores el Fa5 estarà sobre la cinquena línia (la de dalt de tot) i el Sol5 estarà per damunt.
```music-abc
L:1/4
e f g
```
Pentagrama amb clau de sol: Mi5, Fa5 i Sol5
{:.figcaption}

Però aleshores com representem la següent nota en altura, el La5? La solució de la notació musical és posar-lo al lloc on aniria la següent línia més alta i, per a que no hi hagi confusió, afegir un fragment de la mateixa línia. Així podem pujar tantes notes com ens calgui:

```music-abc
L: 1/4
e f g a b c'
```
Mi5, Fa5, Sol5, La5, Si5, Do6 en clau de Sol.
{:.figcaption}

Per sota podem fer el mateix. La primera línia (la de baix de tot), en clau de sol, correspon al Mi4. Podem anar baixant l'altura i afegint segments addicionals quan ens allunyem de les línies del pentagrama:

```music-abc
L:1/4
E D C B, A, G,
```
Mi4, Re4, Do4, Si3, La3 i Sol3 en clau de Sol.
{:.figcaption}

Tornem, però, a aquesta famosa clau de sol. Què vol dir? Si ens hi fixem, aquesta mena de G recargolada té el centre de l'espiral a la segona línia del pentagrama (contant des de baix) que, en clau de sol es correspon a la nota... Sol!

I per què cal aquest símbol? Perquè 5 línies són molt poques... M'explico.

Cada instrument té un [àmbit](https://ca.wikipedia.org/wiki/%C3%80mbit), que és l'interval entre el so més greu i el més agut que es pot tocar amb l'instrument; també les veus humanes. I per què menciono ara això? Poc a poc. 
Si el teu instrument és un violí el seu àmbit serà l'interval entre el Sol3 i el La7 i, per tant, les partitures que llegiràs tindran notes en aquest interval:
```music-abc
L:1/4
G, C c c' c'' a''
```
Àmbit del violí (Sol3 a La7) i tots els Do intermitjos, en clau de sol.
{:.figcaption}

Malgrat que a les parts més agudes hauràs de comptar ratlletes, per a la majoria de partitures estaràs fent servir tot l'espai del pentagrama. És més, en el cas del violí els principiants no movem encara la mà esquerra de llloc; diem que estem en primera posició. I en aquesta, només podem tocar notes entre el Sol3 i el Si5 (Do6 excepcionalment allargant molt el dit petit):

```music-abc
L:1/4
G, C c c'
```
Àmbit de la primera posició de violí (Sol3 a Do6) en clau de sol (i tots els Do intermitjos).
{:.figcaption}

Però què passa si toques, per exemple, la tuba? El seu àmbit és de Re1 a Fa4, que representat en clau de sol seria:
```music-abc
L:1/4
D,,, C,, C, C F
```
Àmbit de la tuba (Re1 a Fa4) i tots els Do intermitjos, en clau de Sol 
{:.figcaption}

En aquest cas, no només hauries d'estar comptant ratlletes tota l'estona si no que, a més, 4 de les 5 línies del pentagrama no les faries servir per res, ja que el teu instrument no pot tocar les notes que hi van.

La solució és posar les notes a un altre lloc del pentagrama. Si, per exemple, posem el Fa4 a la quarta línia del pentagrama, tindrem el pentagrama més al mig de l'àmbit de la tuba i, per tant, serà molt més fàcil de llegir per als intèrprets de tuba. Per a indicar que hem decidit posar el Fa a la quarta línia dibuixem la clau de Fa en quarta o, el que és el mateix, el símbol de clau de Fa centrat en la quarta línia:
```music-abc
K:bass
L:1/4
D,,, C,, C, C F
```
Àmbit de la tuba (Re1 a Fa4) i tots els Do intermitjos, en clau de Fa 
{:.figcaption}

Quina és la llista completa de claus? N'hi ha força, però només quatre estan en ús. Vegem-les i, per a cada una, representem la nota central i un Do4.

La clau de Sol (en segona) és la més comú i es fa servir per als instruments més aguts: l'oboè, la flauta, el violí, les veus de soprano i contralt, alguns instruments de percussió i la mà dreta del piano i altres instruments de teclat:
```music-abc
L:1/4
G C
```
Clau de Sol, Sol4 i Do4
{:.figcaption}

La clau de Fa (en quarta) es fa servir pels instruments més greus: el violoncel, el contrabaix, la tuba, el trombó, el fagot, el contrafagot i la mà esquerra del piano i altres instruments de teclat:
```music-abc
K:bass
L:1/4
F, C
```
Clau de Fa, Fa4 i Do4
{:.figcaption}

La clau de Do en tercera (sobre la tercera línia) es fa servir per a viola, viola de gamba, mandola i pot aparèixer en determinades partitures per trombó alt, oboè o flauta dolça:
```music-abc
L:1/4
K: alto
C
```
Clau de Do en 3a i Do4
{:.figcaption}

La clau de Do en quarta (sobre la quarta línia) es fa servir per a fagot i per a representar notes agudes d'instruments com el violoncel, el trombó tenor o el bombardí.
```music-abc
L:1/4
K: `tenor`
C
```
Clau de Do en 4a i Do4
{:.figcaption}

Ah! I abans no me n'oblidi! Si estàs aprenent a llegir partitures, ja sigui en clau de Sol o en altres claus, et caldrà desenvolupar la memòria més automàtica. Es tracta d'automatitzar la lectura del pentagrama per a llegir-lo sense haver de parar a pensar quina nota és cada una, igual que llegim un text sense parar-nos a pensar quina lletra és cada una. Per a això, no conec altra manera que la pràcitca. Jo recomano una aplicació per mòbil que s'anomena Music Tutor i que podeu trobar per a [iOS](https://apps.apple.com/us/app/music-tutor-sight-reading/id514363426) i [Android](https://play.google.com/store/apps/details?id=com.jsplash.musictutor&hl=en&gl=US).

---
[^1]: En el meu cas, violinista Suzuki, Mi5 és la nota que fa el violí en fregar la corda més aguda a l'aire (sense prémer-la a cap alçada).