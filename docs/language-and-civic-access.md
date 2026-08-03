# Language and civic access

**Status:** Essay outline · Spring 2026 reflection  
**Connects to:** [ServeIT i18n / mixed-language accessibility notes](https://jadexzhao.github.io/jadexzhao/i18n-wcag.html)

## Thesis

Language is not a cosmetic layer on top of a working system. For civic and government-facing apps, **language choice is access control** ... often as strong as a login wall, but invisible in the product requirements.

## What I mean by “civic access”

Access here means: can you **complete the task** (register, pay, appeal, schedule, prove eligibility) without insider help?

Barriers that show up repeatedly abroad:

| Barrier | Builder takeaway |
|---------|------------------|
| UI only in one language | Treat translation as UX, not a late string export |
| Legal or bureaucratic Spanish with no plain summary | Plain language is an accessibility requirement |
| Mixed-language households | `lang` attributes, screen reader behavior, character density ... see portfolio i18n note |
| Phone support as the “real” interface | If the app fails, access fails ... especially for outsiders |
| PDF-only “English version” | Not equivalent to an usable English flow |

## Bilingual when the room needs it

Public portfolio framing: 福州 roots, bilingual when the room needs it. Madrid made that less abstract. Elementary Spanish (`HISP-S 100`) was not fluency on arrival ... it was enough to notice when systems pretended everyone already had native proficiency.

That is the same instinct behind mixed-language DOM work at ServeIT: **mark language in the structure**, don’t leave assistive tech to guess.

## Civic apps vs. consumer apps

Consumer apps optimize for engagement. Civic apps optimize for **compliance with a process someone else designed**. The user did not choose the workflow; they are trying not to miss a deadline.

Design implications:

1. **Progress visibility** ... Where am I in the process? What happens next?
2. **Recoverable errors** ... Save state; don’t wipe the form on one bad field
3. **Human escalation path** ... A real person, a clear case ID, not a chatbot loop
4. **Offline / paper parity** ... Not everyone lives inside a perfect mobile signal or app ecosystem

## WCAG overlap (public-interest tech)

From clinic work: accessibility is keyboard paths, contrast, focus order, and **comprehensibility**. Language fits under comprehensibility even when WCAG checklists focus on markup.

Checklist seed for civic-facing builds:

- [ ] Primary task completable in each supported language without switching mid-flow
- [ ] `lang` set on mixed-language blocks; not one default on the whole page
- [ ] Error text names the fix, not the failure
- [ ] Screen reader spot-check in each language offered
- [ ] Plain-language summary adjacent to legal text where policy allows

Full clinic baseline: [zhao-langxi/serveit-accessibility](https://github.com/zhao-langxi/serveit-accessibility).

## Open questions (to expand)

- [ ] Document one observed civic flow: language pivot points only (no private data)
- [ ] Compare EU multilingual policy rhetoric vs. single-language app defaults
- [ ] Draft ELI5 sidebar pattern for nonprofit + civic handoffs

## See also

- [Systems friction abroad](./systems-friction-abroad.md)
- [From Madrid to ServeIT](./from-madrid-to-serveit.md)
