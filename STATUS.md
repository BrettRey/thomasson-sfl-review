# Status -- thomasson-sfl-review

## Current state (2026-06-30)

Public GitHub is set up at `https://github.com/BrettRey/thomasson-sfl-review` and the project is shipped under CC BY 4.0. `main.tex` and `main.pdf` are current on pushed `master`.

Public archive records:
- LingBuzz: `https://lingbuzz.net/lingbuzz/010101`
- PhilArchive: `https://philarchive.org/rec/REYAMS`

The draft is a short linguistics review essay on Thomasson's SFL turn. The current argument is an extraction argument: Thomasson's discourse-role insights survive without Halliday's stronger placement of those roles inside grammatical architecture. The live case study is NP-forming/noun-term recastings; modal vocabulary remains background.

## Next action

Polish for submission: check page numbers against the published books, decide venue, and run one final source/page-anchor pass around the Thomasson formal-functional and grammatical-metaphor passages.

## Blockers

- Page numbers in `notes/passage-map.md` are first-pass physical/PDF-derived page numbers and should be manually checked against rendered pages before submission.
- Halliday/Huddleston lineage claims still need independent history-of-linguistics sourcing if used as factual history rather than standpoint.
- Companion-piece framing must use the current projectibility-profile framework from *Kinds as Projectibility Profiles* and *Not Every Stable Cluster Is Homeostatic*, not older "everything is HPC" vocabulary.
- The public draft is suitable as a shipped working version, but not yet a submission package.

## Decisions

See `DECISIONS.md`.

## Pending Brett

- Confirm working title.
- Decide venue (`Journal of Linguistics`, `Language Sciences`, or another target).
- Decide whether to circulate the public draft as-is or first run a submission-oriented review pass.

### 2026-06-30 Afternoon Session Notes
- Finished the final terminological-hygiene pass: title/abstract/conclusion now use "architecture of linguistic description"; the paper avoids projectibility/projection vocabulary in the linguistics-facing prose; noun/NP/nominal wording is tightened.
- Clarified the introduction's extraction claim: the aim is to extract the part of SFL Thomasson needs, not to dismiss the borrowing.
- Changed the CGEL example from `Nom` to `nominal` in the `stone wall` modifier example.
- Rebuilt and pushed the final manuscript state through commit `aa98f7f` on `master`; `git push` reports origin is up to date.
- Created an untracked LingBuzz upload copy: `reynolds-2026-thomasson-sfl-architecture-of-linguistic-description.pdf`.
- Recorded public links: LingBuzz `010101` and PhilArchive `REYAMS`.

### 2026-06-30 Session Notes
- Actioned the review-board-style recommendations on target clarity, scope, and positive alternative.
- Clarified the paper as an extraction argument rather than a claim that Thomasson's metaphilosophy collapses.
- Narrowed the abstract/introduction to NP-forming recastings and made modal vocabulary background.
- Added a Thomasson textual anchor for the risk: formal-functional assessment based in formal-grammatical forms, followed by questions about what transformed formulations add.
- Added explicit distribution-first diagnostics for the relevant NPs and kept discourse roles separate.
- Replaced broad "inside syntax" formulations with "inside grammatical architecture/description" where appropriate.
- Built and checked `main.pdf`; only known `fancyhdr`/`microtype` warnings remain.
- Pushed the manuscript and shutdown-state commits to the public GitHub remote.
