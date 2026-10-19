# Feedback Writer

**Een Claude-skill die feedback opstelt waar leerlingen en studenten echt iets mee doen.**

Je plakt het werk (geanonimiseerd) en het leerdoel of de rubric, en je krijgt specifieke, haalbare feedback terug: wat sterk is, maximaal drie prioriteiten met een voorbeeld uit het werk, en een concrete volgende stap. Het oordeel en het cijfer blijven bij jou.

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

*English summary: a Claude skill that drafts specific, actionable feedback on student work, tied to the learning objective or rubric, with at most three priorities and a clear next step, while the grade stays with the teacher. Also turns rubric scores into feedback and builds comment banks. It works in Dutch, French and English.*

## Wat de skill doet

- **Koppelt feedback aan het leerdoel of de rubric**, niet aan alles wat opvalt.
- **Kiest wat het meeste verschil maakt:** eerst inhoud en redenering, dan structuur, bronnen, en pas daarna taal en vorm (tenzij taal het leerdoel is).
- **Schrijft feedforward:** wat, waar in het werk (met citaat) en hoe je het verbetert.
- **Maximaal drie prioriteiten**, zodat de leerling ze ook echt kan verwerken.
- **Geeft geen cijfer**, en signaleert wat beter in een gesprek dan op papier past.
- **Denkt aan privacy:** herinnert eraan namen te verwijderen (GDPR).

Daarnaast kan de skill:
- **rubricscores omzetten in feedback** per criterium
- **klassikale feedback** maken op basis van veelvoorkomende fouten
- een **commentaarbank** opbouwen per criterium en niveau
- een **gids voor peerfeedback** schrijven

## Wat je terugkrijgt

1. **Feedback voor de leerling**, klaar om te plakken: sterktes, prioriteiten, eerste actie
2. **Notities voor de leerkracht**: wat de skill niet kon beoordelen, en een voorstel voor opvolging

## Voor wie

Voor leerkrachten, docenten in het hoger onderwijs en trainers die betere feedback willen geven in minder tijd.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): prompts voor leerkrachten, met uitleg waarom ze werken
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessen ontwerpen van leerdoel tot exit-check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): beoordelingsrubrics met observeerbare niveaus
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): lesmateriaal toegankelijk maken met UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): opleidingen en leertrajecten ontwerpen
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (web, desktop of mobiel):**
1. Download [`feedback-writer.skill`](feedback-writer.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `feedback-writer/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"geef feedback op dit betoog van een leerling uit het 4e middelbaar"*. De skill start vanzelf.

## Structuur

```
feedback-writer/
└── SKILL.md              # de volledige instructies van de skill
examples/                 # voorbeelden van input en output
feedback-writer.skill     # installeerbaar pakket
```

## Bijdragen

Ideeën en verbeteringen zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
