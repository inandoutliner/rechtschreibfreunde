# Inhaltskarte

Automatisch erzeugt mit `werkstatt/werkzeuge/karte.py`. Stand: f4d5469, 2026-11-09: Rechenfreundinnen und -freunde 1004: Froschsprung

Vorgehen: Abschnitt hier finden → `grep -n "<Titel>" index.html` → nur diesen Bereich lesen.

## `index.html` – Rechtschreibfreundinnen und -freunde 1007
1689 Zeilen, 607 KB.

**Datenblöcke – nie komplett ausgeben** (z. B. `cut -c1-200` oder `awk 'length<3000'`):

- Zeile 310: 43 KB – `@font-face{font-family:"Herkules";src:url(data:font/otf;bas…`
- Zeile 630: 3 KB – `'1': 'O-ma 👵, O-pa 👴, Ma-ma 👩, Pa-pa 👨, Au-to 🚗, Maus 🐭, So…`
- Zeile 631: 4 KB – `'2': 'Ap-fel 🍎, Fisch 🐟, Schu-le 🏫, Kat-ze 🐱, Blu-me 🌸, Ste…`
- Zeile 632: 6 KB – `'3': 'Fahr-rad 🚲, Schmet-ter-ling 🦋, Zahn 🦷, Brü-cke 🌉, Was…`
- Zeile 1392: 456 KB – `const BUILTIN_CLIPS = [{"cat": "perfect", "id": "b6", "name…`

**Bedien-Bereiche (HTML)**

- 408: `<nav>` Desktop
- 437: `<section>` scrStart – Auswahl
- 489: `<section>` scrPlay
- 523: `<section>` scrEnd
- 540: `<section>` scrRhyme

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 247–367 | Flache Ansichten (Plotter, Old School) |  |
| 367–628 | Handy (nur schmale Bildschirme) | $, $$ |
| 628–697 | Wortlisten (Bindestrich = Silbe) | syllabify, sliceBy, parseList |
| 697–727 | Zustand & Speicher | load, save, reduceMotion, pick, shuffle, esc, getPool |
| 727–771 | Ton | pickVoice, hasSpeech, speak, sfx |
| 771–809 | Schrift vermessen (für die Lineatur) | fontStack, measureFont, adv, geo, layout |
| 809–869 | Wort zeichnen | renderWord |
| 869–1018 | Eingabe | buildTiles, buildInput, matches, syncInput, shakeEl, caseMsg, tryLetter |
| 1018–1223 | Ablauf | bubble, setSteps, setButtons, renderDots, showMsg, showScreen, startRound, beginWord, answerSyl, toMerk, toSpell, peek … +5 |
| 1223–1245 | Startseite | renderStart |
| 1245–1264 | Lernwörter-Dialog | updatePreview, openModal, closeModal, saveModal |
| 1264–1273 | Ansicht | applyTheme |
| 1273–1376 | Reim-Bonus | normRh, rhymePart, rhymes, knownWords, startRhyme, rhCur, showRhyme, rhHint, rhCheck, rhAccept, rhNext |
| 1376–1383 | Pixel-Sterne | pixStar, starsHtml |
| 1383–1493 | Eigene Stimmen | idbReq, loadClips, addClip, delClip, stopClip, playClip, renderVoices, toggleRec, stopRec, openVoices, closeVoices |
| 1493–1531 | Konfetti | confetti, tick |
| 1531–1666 | Ereignisse | bind |
| 1666–1689 | Start | start |

## `mathe/index.html` – Rechenfreundinnen und -freunde 1004
1412 Zeilen, 593 KB.

**Datenblöcke – nie komplett ausgeben** (z. B. `cut -c1-200` oder `awk 'length<3000'`):

- Zeile 310: 43 KB – `@font-face{font-family:"Herkules";src:url(data:font/otf;bas…`
- Zeile 566: 4 KB – `<svg viewBox="0 0 12 8" shape-rendering="crispEdges" aria-h…`
- Zeile 744: 456 KB – `const BUILTIN_CLIPS = [{"cat": "perfect", "id": "b6", "name…`
- Zeile 1015: 4 KB – `const FROG_SVG = '<svg viewBox="0 0 12 8" width="42" height…`

**Bedien-Bereiche (HTML)**

- 556: `<nav>` Desktop
- 583: `<section>` scrStart – Auswahl
- 633: `<section>` scrPlay
- 674: `<section>` scrEnd
- 690: `<section>` scrBonus

**Abschnitte im Code** (Suchbegriff = Titel)

| Zeile | Abschnitt | Funktionen |
|---|---|---|
| 247–367 | Flache Ansichten (Plotter, Old School) |  |
| 367–472 | Mathe |  |
| 472–765 | Handy (nur schmale Bildschirme) | $, $$, load, save, rnd, pick, shuffle, esc, fmt, reduceMotion |
| 765–805 | Ton | sfx, pickVoice, speak, stopClip, playClip |
| 805–830 | Sterne & Konfetti | pixStar, starsHtml, confetti, tick |
| 830–890 | Aufgaben erzeugen | houseSpec, makeHouseTasks, makeFrogTasks, makeMalTasks, taskText |
| 890–1318 | Ablauf | bubble (891), status (892), setSteps (894), showScreen (902), renderDots (908), startRound (912), beginTask (919), renderHouse (930), renderBeads (941), beginHouse (965), toRechne (990), peek (1006), frogScale (1016), renderFrog (1022), beginFrog (1057), frogGuess (1071), renderGrid (1094), beginMal (1108) … +17 |
| 1318–1343 | Startseite | applyTheme, renderStart, goHome |
| 1343–1412 | Ereignisse | bind, start |
