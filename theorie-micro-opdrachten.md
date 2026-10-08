# Theorie: 8 micro-opdrachten in de ruimte 🚀

BrakeOut Scratch workshop

## Ter ere van Margaret Hamilton

We maken vandaag alles in een ruimtethema, ter ere van **Margaret Hamilton**. Zij leidde aan MIT het team dat de software schreef voor de boordcomputer van de Apollo-maanmissies. Tijdens de maanlanding van Apollo 11 in 1969 gaf de computer plots alarmen, maar haar software was zo slim gebouwd dat hij gewoon het belangrijkste werk bleef doen. Zo kon de landing doorgaan.

Wat zij deed met heel veel code, doen wij vandaag met blokjes: een computer stap voor stap vertellen wat hij moet doen.

## Hoe werkt het?

- De lesgever doet elke micro-opdracht **live** voor op het grote scherm.
- De deelnemers bouwen **tegelijk** mee op hun eigen computer.
- Elke micro-opdracht leert **één nieuw concept**. Blijf het vorige project gebruiken, zo groeit één ruimteproject stap voor stap.
- Wie sneller klaar is, probeert de **extra uitdaging (★)**.

**Richttijd:** ongeveer 30 minuten in totaal (4 min UI + 8 × 3 à 4 min). Zo blijft er ruim tijd over voor de 4 oefeningen binnen het blok van 70 minuten.

> Tip: blokken heten in Scratch soms net iets anders afhankelijk van de versie. Toon telkens de **kleur** van de categorie, dan vinden de deelnemers het blok sneller.

---

## 0. Scratch UI verkennen (± 4 min)

Open een nieuw project (**Maak** / **Create**) en wijs elk deel aan:

| Deel | Waar | Wat doet het? |
|------|------|---------------|
| **Podium** | rechtsboven | Hier gebeurt alles: je ziet je project spelen. Midden = x: 0, y: 0. Links/rechts loopt x van -240 tot 240, onder/boven loopt y van -180 tot 180. |
| **Groene vlag / stopbord** | boven het podium | Groene vlag start het project, het rode stopbord stopt alles. |
| **Spriteslijst** | onder het podium | Alle figuurtjes (sprites) in je project. Klik op een sprite om zijn scripts te zien. Rechtsonder: nieuwe sprite kiezen. |
| **Achtergronden** | helemaal rechtsonder | Hier kies je de achtergrond van het podium. |
| **Blokpaletten** | links | De blokken, per kleur gesorteerd: Beweging, Uiterlijken, Geluid, Gebeurtenissen, Besturen, Waarnemen, Functies, Variabelen. |
| **Scriptgebied** | midden | Hier sleep je blokken naartoe en klik je ze aan elkaar. |
| **Tabbladen Code / Uiterlijken / Geluiden** | linksboven | Wissel tussen de code, de kostuums (uiterlijken) en de geluiden van de geselecteerde sprite. |

Laat ook even zien:

- Blok in het scriptgebied **slepen**, **vastklikken** en terug naar links slepen om te **verwijderen**.
- Op een blok **klikken** om het meteen uit te proberen.
- De kat (Sprite1) verwijderen: rechtsklik → **verwijder**. We gaan de ruimte in!

---

## 1. Lancering! 🚀

**Concept:** sequentie (opdrachten worden één na één uitgevoerd, van boven naar onder)

**Sprites / achtergrond:**

- Sprite **Rocketship** (categorie *Ruimte*)
- Achtergrond **Stars** (of een andere ruimteachtergrond)

**Blokken:**

- `wanneer op groene vlag wordt geklikt` (Gebeurtenissen)
- `ga naar x: 0 y: -130` (Beweging)
- `wacht 1 sec.` (Besturen)
- `schuif in 2 sec. naar x: 0 y: 150` (Beweging)

**Stap voor stap (lesgever):**

1. Voeg de sprite **Rocketship** en de achtergrond **Stars** toe.
2. Sleep `wanneer op groene vlag wordt geklikt` in het scriptgebied: "Dit is het startblok, hier begint alles."
3. Klik `ga naar x: 0 y: -130` eronder: de raket staat klaar op het lanceerplatform.
4. Daaronder `wacht 1 sec.`
5. Daaronder `schuif in 2 sec. naar x: 0 y: 150`.
6. Klik op de groene vlag. Wat gebeurt er? En als je de blokken in een andere volgorde zet?

**Kernboodschap:** de computer doet precies wat je vraagt, in de volgorde die jij bepaalt.

**Extra uitdaging (★):** laat de raket eerst naar links schuiven en daarna pas omhoog vliegen.

---

## 2. Vlammen en stapjes 🔥

**Concept:** herhalen (lussen)

**Sprites / achtergrond:** dezelfde raket en achtergrond

**Blokken:**

- `herhaal 10 keer` (Besturen)
- `verander y met 15` (Beweging)
- `volgend uiterlijk` (Uiterlijken)
- `wacht 0.1 sec.` (Besturen)

**Stap voor stap (lesgever):**

1. Toon het tabblad **Uiterlijken** van de raket: de raket heeft meerdere kostuums, sommige met vlammen.
2. Vervang `schuif in 2 sec. naar ...` door een `herhaal 10 keer`-blok.
3. Zet in de herhaling: `verander y met 15`, `volgend uiterlijk`, `wacht 0.1 sec.`
4. Groene vlag: de raket stijgt in stapjes en de vlammen flikkeren.
5. Vraag: "Hoeveel blokken hadden we nodig zonder herhaal-blok?" (30!)

**Kernboodschap:** met een lus laat je de computer hetzelfde vaak doen, zonder dat je alles opnieuw moet schrijven.

**Extra uitdaging (★):** voeg de sprite **Planet2** toe en gebruik `herhaal` (altijd) met `draai 15 graden` om de planeet eindeloos te laten draaien.

---

## 3. Van de aarde naar de ruimte 🌍

**Concept:** uiterlijken, achtergronden en grootte (Looks)

**Sprites / achtergrond:**

- Raket
- Twee achtergronden: een op aarde (bv. **Space City 1** of een buitenachtergrond) en **Stars**

**Blokken:**

- `verander achtergrond naar ...` (Uiterlijken)
- `zeg 3, 2, 1... Lancering! gedurende 2 sec.` (Uiterlijken)
- `maak grootte 100 %` en `verander grootte met -5` (Uiterlijken)

**Stap voor stap (lesgever):**

1. Voeg een tweede achtergrond toe (een op aarde).
2. Bovenaan het script, na de groene vlag: `verander achtergrond naar` *(aarde)* en `maak grootte 100 %`.
3. Voor de lus: `zeg 3, 2, 1... Lancering! gedurende 2 sec.`
4. In de herhaling: `verander grootte met -5`. De raket wordt kleiner, alsof hij ver weg vliegt.
5. Na de herhaling: `verander achtergrond naar Stars`.
6. Vraag: "Waarom zetten we de grootte en de achtergrond eerst terug bij de start?"

**Kernboodschap:** met uiterlijken verander je hoe iets eruitziet, niet waar het staat. Goed starten = alles terugzetten bij de groene vlag.

**Extra uitdaging (★):** laat de raket op het einde verdwijnen met `verdwijn` en bij de start weer verschijnen met `verschijn`.

---

## 4. Stuur je raket 🎮

**Concept:** gebeurtenissen (toetsen en klikken)

**Sprites / achtergrond:** raket, achtergrond **Stars**

**Blokken:**

- `wanneer [pijltje rechts] is ingedrukt` (Gebeurtenissen)
- `wanneer [pijltje links] is ingedrukt`, `... pijltje omhoog ...`, `... pijltje omlaag ...`
- `verander x met 10` / `verander x met -10` (Beweging)
- `verander y met 10` / `verander y met -10` (Beweging)
- `wanneer op deze sprite wordt geklikt` (Gebeurtenissen)

**Stap voor stap (lesgever):**

1. Sleep `wanneer [spatiebalk] is ingedrukt` in het scriptgebied, kies **pijltje rechts**.
2. Eronder `verander x met 10`. Probeer: druk op pijltje rechts.
3. Dupliceer (rechtsklik → **kopiëren**) en maak links (`-10`), omhoog (`y` met `10`) en omlaag (`y` met `-10`).
4. Toon dat je **meerdere scripts** tegelijk kan hebben in één sprite: elk start bij een andere gebeurtenis.
5. Bonus: `wanneer op deze sprite wordt geklikt` → `zeg Hallo, aarde! gedurende 2 sec.`

**Kernboodschap:** een script start niet altijd met de groene vlag. Het kan ook starten als *iets gebeurt*.

**Extra uitdaging (★):** laat de raket ook in de juiste richting kijken met `richt naar 90 graden` (rechts) en `richt naar -90 graden` (links).

---

## 5. Motorgeluid en aftellen met je stem 🔊

**Concept:** geluid (afspelen en opnemen)

**Sprites / achtergrond:** raket, achtergrond **Stars**

**Blokken:**

- `start geluid ...` (Geluid)
- `start geluid ... en wacht` (Geluid)

**Stap voor stap (lesgever):**

1. Open het tabblad **Geluiden** van de raket en kies een geluid uit de bibliotheek (bv. zoek op *space* of *laser*).
2. Zet `start geluid ...` vlak voor de lus waarin de raket stijgt.
3. Neem een eigen geluid op: tabblad **Geluiden** → **Opnemen** → "3, 2, 1, lancering!"
4. Zet `start geluid (opname) en wacht` vóór de lancering.
5. Vergelijk: wat is het verschil tussen **start geluid** en **start geluid en wacht**? (Wacht de raket wel of niet tot het geluid gedaan is?)

**Kernboodschap:** sommige blokken wachten tot ze klaar zijn, andere niet. Dat bepaalt wat er *tegelijk* gebeurt.

**Extra uitdaging (★):** gebruik `verander toonhoogte-effect met 10` in de lus, zodat de motor steeds hoger klinkt.

---

## 6. Klaar voor lancering? ✅

**Concept:** voorwaarden (als ... dan ... anders) en vragen stellen

**Sprites / achtergrond:** raket, achtergrond **Stars**

**Blokken:**

- `vraag Klaar voor lancering? (ja/nee) en wacht` (Waarnemen)
- `antwoord` (Waarnemen)
- `( ) = ( )` (Functies)
- `als < > dan ... anders` (Besturen)

**Stap voor stap (lesgever):**

1. Na de groene vlag en de startpositie: `vraag Klaar voor lancering? (ja/nee) en wacht`.
2. Sleep `als < > dan ... anders` eronder.
3. In de voorwaarde: `antwoord = ja` (sleep `antwoord` in het linkervakje, typ `ja` rechts).
4. Sleep het hele lanceer-deel (geluid + lus) in het **dan**-gedeelte.
5. In het **anders**-gedeelte: `zeg Missie uitgesteld! gedurende 2 sec.`
6. Test met *ja* en met *nee*.

**Kernboodschap:** met een voorwaarde kiest de computer zelf wat hij doet, afhankelijk van een situatie of antwoord.

**Extra uitdaging (★):** voeg de sprite **Planet2** toe. Zet in de raket `herhaal` (altijd) met `als <raak ik Planet2?> dan zeg Geland!`. Stuur de raket met de pijltjes naar de planeet.

---

## 7. Het aftelklokje ⏱️

**Concept:** variabelen (iets onthouden dat kan veranderen)

**Sprites / achtergrond:** raket, achtergrond **Stars**

**Blokken:**

- **Maak een variabele** → `aftellen` (Variabelen)
- `maak aftellen 10` (Variabelen)
- `verander aftellen met -1` (Variabelen)
- `zeg (aftellen) gedurende 1 sec.` (Uiterlijken)
- `herhaal 10 keer` (Besturen)

**Stap voor stap (lesgever):**

1. Klik bij **Variabelen** op **Maak een variabele**, noem ze `aftellen`. Toon dat ze op het podium verschijnt.
2. Vóór de lancering: `maak aftellen 10`.
3. Daaronder `herhaal 10 keer` met daarin: `zeg (aftellen) gedurende 1 sec.` en `verander aftellen met -1`.
4. Daarna de lancering zoals voorheen.
5. Vraag: "Wat zit er nu in de variabele na het aftellen?" (0)

**Kernboodschap:** een variabele is een doosje met een naam waarin de computer een waarde onthoudt. Die waarde kan je veranderen.

**Extra uitdaging (★):** maak een variabele `brandstof` die start op 100 en bij elke stap van de raket met 1 daalt. Als `brandstof = 0`, zegt de raket "Tank leeg!" en `stop alle`.

---

## 8. Mission Control zegt: GO! 📡

**Concept:** berichten (sprites laten samenwerken met signalen)

**Sprites / achtergrond:**

- Raket
- Een tweede sprite als **Mission Control** (bv. **Ripley**, **Robot** of een andere figuur)
- Achtergrond op aarde + **Stars**

**Blokken:**

- `zend signaal lancering` (Gebeurtenissen)
- `wanneer ik signaal lancering ontvang` (Gebeurtenissen)

**Stap voor stap (lesgever):**

1. Voeg de sprite **Mission Control** toe.
2. Bij Mission Control: `wanneer op groene vlag wordt geklikt` → `zeg Alle systemen zijn klaar. gedurende 2 sec.` → `zend signaal` → kies **Nieuw bericht** → `lancering`.
3. Bij de raket: vervang de groene vlag van het lanceerscript door `wanneer ik signaal lancering ontvang`. (Het klaarzetten met `ga naar ...` en `maak grootte 100 %` blijft bij de groene vlag.)
4. Groene vlag: Mission Control geeft het signaal, de raket vertrekt.
5. Toon dat ook de **achtergrond** een signaal kan ontvangen: bv. `wanneer ik signaal lancering ontvang` → `verander achtergrond naar Stars`.

**Kernboodschap:** met signalen kunnen sprites met elkaar praten. Zo maak je een verhaal waarin verschillende figuren na elkaar iets doen. Handig voor **Codeer jouw verhaal**!

**Extra uitdaging (★):** laat de raket na de landing een signaal `geland` sturen, waarop Mission Control antwoordt met "Welkom op de maan!".

---

## Overzicht

| # | Micro-opdracht | Concept | Nieuwe blokken |
|---|----------------|---------|----------------|
| 0 | Scratch UI verkennen | de werkomgeving | – |
| 1 | Lancering! | sequentie | groene vlag, ga naar, wacht, schuif |
| 2 | Vlammen en stapjes | herhalen | herhaal … keer, verander y, volgend uiterlijk |
| 3 | Van de aarde naar de ruimte | uiterlijken & achtergronden | verander achtergrond, zeg, grootte |
| 4 | Stuur je raket | gebeurtenissen | wanneer toets ingedrukt, wanneer sprite geklikt |
| 5 | Motorgeluid en aftellen met je stem | geluid | start geluid (en wacht), opnemen |
| 6 | Klaar voor lancering? | voorwaarden | vraag, antwoord, =, als … dan … anders |
| 7 | Het aftelklokje | variabelen | maak variabele, maak … , verander … met |
| 8 | Mission Control zegt: GO! | berichten | zend signaal, wanneer ik signaal ontvang |

**Link met de 4 oefeningen:** beweging en uiterlijken (opdracht 1 en 2), toetsen (opdracht 2 ★), zeggen, stem opnemen en vragen met voorwaarden (opdracht 3) en geluid (opdracht 4) komen allemaal al in de micro-opdrachten aan bod.
