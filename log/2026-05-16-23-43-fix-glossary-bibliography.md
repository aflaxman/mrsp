# Fix Glossary and Bibliography

## Prompt

Use `task site` to build the pages. Use `task check` to check them. Look at unused
glossary and bibliography entries. Add one reference for each unused glossary entry
IF APPROPRIATE and move it to `_extras/glossary.md` if there is not an obvious
relevant place to mention it. Add a reference to each unused bibliography entry IF
APPROPRIATE, or move it to `_extras/bibliography.md` if there isn't an obvious
relevant place.

## Actions

1. Ran `task site` and `task check` to identify issues:
   - 16 unknown glossary keys (referenced but not defined)
   - 2 key mismatches (continuous-integration vs. ci; audit_trail vs. audit-trail)
   - ~50 unused glossary keys
   - ~30 unused bibliography keys

2. Added 15 new glossary entries for unknown keys to `glossary/index.md`:
   `findability`, `reproducibility`, `pin-dependencies`, `virtual-environment`,
   `container`, `testability`, `test-coverage`, `contribution-pathway`,
   `governance`, `sustainability`, `lottery-factory`, `succession-plan`,
   `sandbagging`, `audit-trail`, `secret-rotation`

3. Fixed key mismatches:
   - `health/index.md`: `continuous-integration` → `ci`
   - `checklist/index.md`: `audit_trail` → `audit-trail`

4. Added glossary references to lessons where natural fits exist:
   - `health/index.md`: doi, fair, rng-seed; citations Lin2020, Wilkinson2016, Taschuk2017
   - `governance/index.md`: hero-project, sense-vote, roberts-rules; citation Freeman1972
   - `checklist/index.md`: gpl, mit-license, unit-test, tdd; citation Petre2014
   - `newcomers/index.md`: community-of-practice; citation Sholler2019
   - `intro/index.md`: persona
   - `hirefire/index.md`: at-will-employment, social-legibility; citation Rivera2015
   - `politics/index.md`: workplace-politics, power-mapping, motivated-reasoning
   - `project/index.md`: refactoring; citation Brooks1995
   - `security/index.md`: phishing, security-fatigue
   - `marketing/index.md`: citation Kuchner2011
   - `burnout/index.md`: citation Jaffe2021
   - `remote/index.md`: citation Skiles2021
   - `lifecycle/index.md`: semantic-versioning

5. Moved remaining unused glossary entries (no natural lesson home) to
   `_extras/glossary.md`.

6. Moved remaining unused bibliography entries (no natural lesson home) to
   `_extras/bibliography.md`.
