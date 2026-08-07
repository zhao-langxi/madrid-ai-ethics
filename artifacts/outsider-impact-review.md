# Outsider Impact Review · one-pager template

**Purpose:** Before shipping a civic digital service or adding automation, check whether the design assumes the user already belongs.  
**Audience:** Students, clinic builders, public-interest AI adopters.  
**Status:** Reusable template. Not a completed evaluation of any system.

## System under review

| Field | Fill in |
|-------|---------|
| System / flow name | |
| Primary task (what success means) | |
| Reviewer role (outsider persona) | e.g. non-native speaker / new arrival / first-time user |
| Date | |
| Happy-path / a11y review also done? | yes / no (link notes) |

## Outsider checks (mark fail / pass / n/a + one-line note)

1. **Assumed local context** ... Does the flow require address history, national ID, bank relationship, or local knowledge a newcomer lacks?
2. **Unwritten sequencing** ... Must the user complete hidden prerequisite steps not stated in the UI?
3. **Language as access** ... Can the primary task be completed in each supported language (not PDF-only “support”)?
4. **Hours & channels** ... If the digital path fails, is there a usable human path with case ID / status?
5. **Recoverable errors** ... Do errors name the fix, or blame the user and wipe state?
6. **Automation risk** ... If AI/automation is added here, does it amplify any of the above (chatbot loop, opaque routing, no override)?

## Gaps the happy-path review missed

- (list only what this outsider pass found that ordinary review did not)

## Required before ship (if any fails)

- [ ] Plain-language / language path fixed for primary task
- [ ] Sequencing stated in UI
- [ ] Human override / case reopen path
- [ ] Error copy names the fix
- [ ] Automation deferred until access baseline works

## Limitation note (copy onto finished reviews)

Single reviewer; persona-based; not a controlled study. Treat findings as design risks to verify, not proof of harm rates.
