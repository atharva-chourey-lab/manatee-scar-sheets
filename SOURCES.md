# Sources Map — A Frozen Sketch Catalogue, Audited (Blue Spring manatee scar sheets)

Author: Atharva Chourey
Affiliation: Atharva Chourey Lab (independent research lab)

*Manuscript — not yet peer-reviewed.*

This file maps every key number, verdict and reference in `paper.md` to the source file it was taken from. Nothing in the paper was taken from a source outside this list.

## Primary sources

- `~/workspace/manatee-scar-sheets/MANUSCRIPT.md` — the full manuscript draft (not submitted to any venue). `paper.md` in this repository is that manuscript with only the header/status block converted to the lab's publication format; no result, number or claim was altered.
- `~/workspace/manatee-scar-sheets/PREREGISTRATION.md` — six predictions (P1–P6) with fixed thresholds, the persistence-curve definition, and the fallback rule (ruler joining <40% → report as coverage audit + case series), committed 2026-11-18 (commit 795ac16) before any transcription or join.
- `~/workspace/manatee-scar-sheets/RESULTS.md` — the run record: headline, both datasets, the scorecard as registered, and the persistence figures.
- `~/workspace/manatee-scar-sheets/transcription.csv` — the two-pass adjudicated transcription. Verified during the publication build: 210 entries, 209 with a BS catalogue ID — matches the manuscript.
- `~/workspace/manatee-scar-sheets/TRANSCRIPTION-METHODS.md` — transcription conventions and the measured error structure (±1 scar-count disagreements on 79 entries; section-missing prevalence 11–23% by convention).
- `~/workspace/manatee-scar-sheets/ruler.csv` — the public ruler: 165 sourced rows covering 91 distinct individuals, each row read from a named source (Hartley's *Genealogies of the Blue Spring Manatees*, newest edition; Save the Manatee Club updates and articles, 2025–2026).
- `~/workspace/manatee-scar-sheets/NOVELTY.md` — the novelty scrub for the audit.
- `~/workspace/manatee-scar-sheets/MIPS-REQUEST-DRAFT.md` — the prepared formal request for the MIPS presence-matrix join (draft; not sent).

## Key numbers and their sources

| Claim in paper | Value | Source file |
|---|---|---|
| Frozen set | 210 entries; 209 with BS ID (sole exception: "Nick", no legible ID) | transcription.csv (verified); RESULTS.md |
| Scar groups (from the sheet alone) | HIGH 151, MID 39, LOW 20 | RESULTS.md, "The two datasets" |
| Join coverage | 45 of 209 (21.5%) — fallback rule fires (<40%) | RESULTS.md, Headline |
| Re-identified after 2013 | 34 of 45 joined; median last record 2025 | RESULTS.md; MANUSCRIPT.md §3 |
| Known deaths among joined | 11 of 45 (24.4%), deaths 2014–2025 | MANUSCRIPT.md §3 (P4) |
| Scar-load gradient | HIGH 69.7% vs LOW 66.7% (+3.0 pts) — P3 failed | MANUSCRIPT.md §3 (scorecard) |
| Cohort comparison | pre-1990 86.7% vs 2000–2013 82.4% — P5 failed, reverse direction | MANUSCRIPT.md §3 (scorecard) |
| Scorecard | P1 fail, P2 pass, P3 fail, P4 pass, P5 fail, P6 void | RESULTS.md; MANUSCRIPT.md §3 |
| Longest span | first identified 1970, recorded January 2026 (56 years) | MANUSCRIPT.md §3 |
| Worked examples | BS4 "Lilly" (1974), BS19 "Merlin" (1970), BS189 "Ann", BS286 "Amber", BS260 "Calista" | MANUSCRIPT.md §3 |

## Novelty and framing notes

- The paper's framing is the registered fallback framing — a coverage audit and non-representative case series — and this publication does not upgrade it. The joined subset is visibly selected (genealogy matriarchs and programme adoptees), and the paper says so wherever the subset is used.
- Absence from the public ruler is counted as *unjoined*, never as death or identification failure, per the registration; all persistence figures are floors.
- The manuscript's reference list is marked in the source as indicative, to be completed at submission; it is reproduced as-is so the public record does not overstate the draft's state.
- The MIPS request is a prepared draft only. It has not been sent; nothing in this publication implies custodian involvement or endorsement.
