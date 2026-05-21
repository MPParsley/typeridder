# 🏰 TypeRidder — Leer Blind Typen

Een gratis, browsergebaseerde typecursus voor kinderen van 7–12 jaar. Geen installatie, geen advertenties, volledig offline bruikbaar.

🔗 **[typeridder.github.io/typeridder](https://mpparsley.github.io/typeridder)** *(na GitHub Pages activatie)*

---

## ✨ Wat is TypeRidder?

TypeRidder is een avontuurlijk typespel waarbij kinderen stap voor stap blind leren typen. Samen met **Pip de Pinguïn** doorkruisen ze vier werelden en leren ze het volledige toetsenbord beheersen — van de thuisrij tot cijfers en hoofdletters.

## 🎮 Functies

- **20 lessen** in 4 werelden: Startdorp → Het Woud → De Bergen → Het Kasteel
- **AZERTY en QWERTY** toetsenbordindelingen
- **Visueel toetsenbord** met kleurcodering per vinger
- **Real-time feedback** — groen bij correct, rood bij fout
- **Adaptief leren** — moeilijke toetsen worden bijgehouden
- **Gamification** — XP, 10 levels, 9 badges, 3-sterren beoordeling
- **Mini-game** — Vallende Letters na elke les
- **Ouderportaal** — WPM-grafiek, nauwkeurigheid, oefentijd, CSV-export
- **Typediploma** — afdrukbaar na voltooiing
- **Geluidseffecten** via Web Audio API
- **Toegankelijkheid** — dyslexievriendelijk lettertype, hoog contrast, kleurenblindmodus

## 🚀 Gebruik

Open `index.html` in een moderne browser. Geen server of installatie vereist.

```bash
git clone https://github.com/MPParsley/typeridder.git
cd typeridder
open index.html   # macOS
# of dubbelklik op index.html in Verkenner
```

## 🏫 GitHub Pages

Activeer GitHub Pages op de `main` branch om de app online te zetten:

1. Ga naar **Settings → Pages**
2. Selecteer **Branch: main** en sla op
3. De app is beschikbaar op `https://mpparsley.github.io/typeridder`

## 🗂️ Bestanden

| Bestand | Inhoud |
|---|---|
| `index.html` | Volledige webapp (HTML + CSS + JS, één bestand) |
| `TypeRidder_PRD.md` | Product Requirements Document |
| `TypeRidder_Technisch.md` | User stories, datamodel, architectuur |

## 🧭 Lessencurriculum

| Wereld | Lessen | Inhoud |
|---|---|---|
| 🏠 Startdorp | 1–5 | Thuisrij (F J D K S L A/Q G H) |
| 🌲 Het Woud | 6–10 | Bovenrij (E I R U T Y W/Z O Q/A P) |
| ⛰️ De Bergen | 11–15 | Onderrij (V M/N C , X . Z/W B N/M) |
| 🏰 Het Kasteel | 16–20 | Shift, zinnen, cijfers, eindexamen |

## 🔒 Privacy

Alle voortgangsdata wordt **lokaal** opgeslagen in `localStorage`. Er worden geen gegevens naar servers gestuurd. Geen cookies, geen tracking, GDPR-conform.

## 📄 Licentie

MIT — vrij te gebruiken, aan te passen en te verspreiden.
