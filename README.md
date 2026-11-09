# Grade 8 Math Catch-Up

A free, bilingual (English/Spanish) web app that helps 8th-grade students who are behind in math close the gap on the Texas **STAAR Readiness Standards**.

**Live app:** https://pblc21.github.io/Math-TEKS-grade8-catchup/

Each skill is taught in three stages, so students get an explanation and guided support before practicing on their own:

| Stage | What the student does |
|---|---|
| **1. Learn** | Reads a short explanation, key vocabulary in English and Spanish, and the most common mistake. Then steps through a worked example one step at a time. |
| **2. Guided practice** | Solves a new problem broken into small steps. After one wrong answer, a hint appears. After two, the step is shown worked out so the student never gets stuck. |
| **3. On my own** | Practices independently with unlimited new problems. Three correct in a row marks the skill as mastered. After a miss, the student can return to guided practice or the lesson. |

## Features

- **Quick check:** a 13-question diagnostic (one per readiness standard) that identifies gaps and builds a practice order.
- **Skill map:** shows each standard's status (Not started, Gap, Practicing, Looks solid, Mastered), ordered by how many STAAR questions each category usually carries.
- **Unlimited problems:** every problem is generated with new numbers, so students can't memorize answers.
- **English/Spanish toggle:** all lessons, problems, hints and solutions are available in both languages.
- **Works on any device:** Chromebooks, laptops, tablets and phones, in light or dark mode.

## Standards covered

All 13 Grade 8 Math Readiness Standards (TEKS):

| Reporting category | STAAR items | Standards |
|---|---|---|
| Proportional & non-proportional reasoning | 12–14 | 8.4B, 8.4C, 8.5G, 8.5I |
| 2-D geometry & transformations | 6–9 | 8.3C, 8.10C |
| 3-D geometry | 5–6 | 8.7A, 8.7B |
| Real numbers | 4–5 | 8.2D |
| Personal financial literacy | 3–4 | 8.12D |
| Equations | 2–4 | 8.8C |
| Pythagorean theorem | 2–4 | 8.7C |
| Data analysis | 2–4 | 8.5D |

STAAR item ranges come from the lead4ward Grade 8 Math Snapshot and reflect past assessments.

## Suggested routine

20–25 minutes, 4–5 days a week:

1. **5 min:** review a skill learned earlier.
2. **15 min:** one target skill, moving from Learn to Guided to On my own.
3. **5 min:** a few problems from mixed skills.

A short weekly check-in with a teacher or parent, looking at the skill map together, helps keep independent study on track.

## For teachers and families

- **No login, no setup.** Share the link or embed it in Google Sites (**Insert → Embed → By URL → Whole page**).
- **Privacy:** the app collects no student information and sends nothing anywhere. Progress is saved only in the student's own browser.
- **Progress is per browser.** If a student switches devices or clears browser data, their skill map starts over. On shared Chromebooks, progress follows each student's Chrome profile.
- **Embedded vs. full page:** some browsers (notably Safari on iPads) may not save progress when the app is embedded inside another site. Opening the full-page link avoids this.

## Technical notes

- A single self-contained file: `index.html` (HTML, CSS and vanilla JavaScript; no build step, no frameworks, no backend).
- Fonts load from Google Fonts. If they are blocked, the app falls back to system fonts.
- Progress is stored with the browser's `localStorage`.

### Updating the app

1. Upload a new `index.html` to this repository (keep the exact file name).
2. GitHub Pages redeploys automatically within a minute or two. Check the **Actions** tab for a green check.

## Credits

- Standards and STAAR item ranges: lead4ward *Snapshot – Grade 8 Math* (source: Texas Education Agency).
- This project is not affiliated with or endorsed by the Texas Education Agency or lead4ward.

---

## En español

**Grade 8 Math Catch-Up** es una aplicación web gratuita y bilingüe para ayudar a estudiantes de 8.º grado que van atrasados en matemáticas a dominar los **Estándares de Preparación de STAAR**. Cada habilidad se enseña en tres etapas: **Aprende** (explicación y ejemplo resuelto paso a paso), **Práctica guiada** (problemas divididos en pasos con pistas) y **Por mi cuenta** (práctica independiente). Usa el botón **ES** para cambiar todo el contenido a español. La aplicación no recopila información de los estudiantes; el progreso se guarda solo en el navegador de cada estudiante.
