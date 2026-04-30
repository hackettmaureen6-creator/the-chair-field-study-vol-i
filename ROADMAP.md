# The Chair — Roadmap

## Shipped
### v0.4 — Chair-as-CTA (current)
- Cold open (warm paper, 4-line Brooklyn tease)
- Isolated chair on transparent background, slow rotation, clickable as primary CTA
- Vertical scenario list reveals after cold open with Brooklyn pre-selected
- Stadium hero (Barclays) crossfades in behind chair on reveal
- Scenario row clicks swap stadium hero behind chair (only Brooklyn has art so far)
- Chair fades out on commit, scrolls to active case
- Brooklyn 3-junction adventure (Oct 12 2021 vax / Aug 8 2022 Tsai / Nov 1 2022 Nash)

## v0.5 — Stadium hero pack + Houston live case
- Generate matching stadium hero photos at actual time-of-day for: Toyota Center, Crypto.com Arena, Wells Fargo Center, Chase Center, Target Center, Intuit Dome, United Center
- Build Houston live case as 3-junction adventure (Doc Rivers exit, Sengun usage, Udoka tenure beats)
- Library cards become real links instead of alert popups

## v0.6 — Junction taxonomy reframe
**Major reframe**: tool stops being team-by-team failure stories, becomes a decision instrument organized by junction archetype.

**Junction archetypes** (each pulls real precedents from the public record, positive AND negative):
- The star ultimatum — KD/Tsai 2022 (-), LeBron/Cavs 2010 (-), Giannis/Bucks 2020 (+), Kawhi/Spurs 2018 (-)
- The coach-star authority break — Nash/Kyrie 2022 (-), Pop/Kawhi 2018 (-), Doc/Harden 2023 (-), Spoelstra/LeBron 2010 (+)
- The medical-trust schism — Kawhi 2018 (-), Kyrie ankle silence (-), Embiid recurring (-)
- The trade vs. retain at the cliff — Rockets/Harden 2020 (-), Nuggets/Jokić extension (+), Bucks/Giannis 2020 (+)
- The graceful unwinding — Heat 2014 (+), Spurs Duncan retirement (+), Dirk farewell (+) vs. Brooklyn liquidation (-)

## v0.7 — Positive case studies
Pair every collapse with an "executed well" counterpart at the same junction:
- **2014 Spurs** (vs. 2018 Spurs) — same franchise, opposite medical-trust call
- **2008 Celtics formation** (vs. 2021 Brooklyn) — deliberate Big Three vs. cascade
- **2023 Nuggets** (vs. 2018 Rockets / 2014 Lakers) — patient star development
- **2014 Heat exit** (vs. 2010 Heat formation) — the unwinding done well
- **2019–22 Bucks** — Giannis retention navigated cleanly

## Editorial Principle
The point of the field study is not to catalog failure. It is to give an operator the room *before* the bleed becomes the news, and show what working through that room can look like — including, sometimes, what working it well looks like.

## Tech / Port
- VS Code port packet: CLAUDE.md, STYLE.md, Next.js scaffold, env-driven scenario configs
- Each scenario as data file, not hardcoded HTML
- Squarespace embed as fallback
