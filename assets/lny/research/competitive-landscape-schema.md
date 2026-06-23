---
title: Competitive Landscape Schema
asset_type: schema
season: lny
---

# Competitive Landscape Schema — Lunar New Year Season

**Live sheet:** [Greater Sacramento Lunar New Year Season - Competitive Landscape](https://docs.google.com/spreadsheets/d/1IB6beiKHC9R05r2o0imkh8MX_2u-qmhlVxTV3pxibs0/edit?usp=drive_link)

Row 1 in the Sheet must match these headers exactly.

## Scope

**Greater Sacramento** — Sacramento, Elk Grove, South Sac, Folsom, Rancho Cordova, West Sacramento, Davis, Woodland, Lincoln, Locke, Brooks (Cache Creek). **January–March** window around Lunar New Year (late Jan through early Mar).

**Not in scope:** Bay Area, SoCal, or May AAPI Heritage Month events — use `Reference only` or `Ecosystem (not LNY calendar)` rows when cited for vendor/sponsor attention.

## Column dictionary

| Column | Meaning |
|--------|---------|
| Category | Lane — e.g. `Vietnamese Tết / Family Fair`, `Chinese New Year / Spring Festival`, `Pan-Asian / Chamber`, `Church / Parish Tết`, `Ticketed Concert / Casino`, `Mardi Gras / Adjacent Season`, `Iu Mien / Ethnic Heritage`, `Ecosystem (not LNY calendar)`, `Reference / Out of region` |
| Tier | Priority within category — `1` (direct capstone comp), `2`, `3`, or `A`/`B`/`C` for reference rows |
| Event Name | Display name |
| Host / Organizer | Producing org |
| City | Primary city |
| Venue | Location detail |
| Typical / Recent Dates | Last known or planned dates |
| Duration | Hours or days |
| Admission | Free, ticketed, parking notes |
| Attendance (number or range) | Best honest number or range |
| Attendance source | `Field estimate`, `Organizer claim`, `CCSD`, `Internal planning`, etc. |
| Vendor count (approx) | Booth/vendor scale if known |
| Lunar aligned | Yes / Partial / No |
| Vietnamese focus | Yes / Partial / No |
| Kids / family center | Yes / Partial / No |
| Parade / spectacle moment | Yes / Partial / No — parade, lion dance, second line, mall stage |
| LNY overlap | Relationship to cPALSs/NVCC/VACOS capstone — see enums below |
| Notes for reviewers | Steering context, honesty gaps, ecosystem notes |
| Source URL | Primary citation |
| Data gap | What is still unknown or unverified |

## Enums

**LNY overlap (common values):** `Our event`, `Direct comp - same day capstone`, `Direct comp - same weekend cluster`, `Direct comp - same city`, `Season network member`, `Twin season - bridge product`, `Ecosystem partner`, `Low - ticketed concert`, `Substitute - free civic`, `Reference only`

**Attendance source:** Always set when attendance is non-empty. Distinguish press/organizer claims from field reads and CCSD.

## Data gap semantics

- Use **Data gap** for open questions — never leave a fake number in **Attendance** to fill silence
- `N/A - our event` when the row is coalition Elk Grove capstone planning
- `Not LNY season competitive set` for out-of-window ecosystem rows (e.g. AAPI Night Market in May)
- `Out of region` for Bay Area / national ceiling comps

## Season flyer linkage

The 2026 **Lunar New Year Season** one-pager (orange–magenta gradient calendar) listed 12 dated events Jan 24–Mar 7 with cPALSs capstone centered Feb 14–15. Those rows are seeded in the Sheet; source file was not preserved in repo — **this Sheet is now the canonical event list**.

## Future columns (deferred)

Scheduling tier, roll-up arc, R-tier, capstone event, weeks before capstone, recommended 2027 slot, collision flag, network member flag, relationship product, `event_id` slug — add to Sheet + this doc together when substance phase starts.
