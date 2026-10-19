# Feedback Writer

**A Claude skill that drafts feedback students actually use.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Paste the (anonymised) work and the learning objective or rubric, and get specific, actionable feedback: strengths, at most three priorities with an example from the work, and a concrete next step. The judgment and the grade stay with you.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Tied to the objective or rubric**, not to everything that catches the eye.
- **Prioritises what matters most:** content and reasoning first, then structure, sources, and language last (unless language is the objective).
- **Feedforward:** what to improve, where (with a quote) and how.
- **No grades**, and flags what belongs in a conversation rather than on paper.
- **Also:** rubric scores → feedback, whole-class feedback, comment banks and peer-feedback guides.

## What you get

1. **Feedback for the learner**, ready to paste
2. **Notes for the teacher**

See [examples/](examples/) for a full input and output.

## Who it's for

Teachers, lecturers and trainers who want to give better feedback in less time.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): ready-to-paste prompts for teachers, with the pedagogy behind them
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessons designed from objective to exit check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): assessment rubrics with observable levels
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): accessible lesson materials using UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): training programs and learning journeys
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`feedback-writer.skill`](feedback-writer.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `feedback-writer/` folder to `~/.claude/skills/`.

Then just ask, for example *"feedback on this argumentative essay from a 16-year-old"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
