# The American Renewal Agenda

**A governing framework anyone can adopt: scored, sourced, costed, and written into draft bills.**

*Fix the Foundations · Same Rules for Everyone · Build What Lasts*

The American Renewal Agenda (Project ARA) is a complete public governing framework for healthcare, education, and infrastructure. It contains 112 scored proposals, 16 draft bills, an implementation sequence, a published fiscal ledger, a constitutional review, and a register of 640 sources.

It is free to use, share, and adapt. No permission, fee, or membership is asked of anyone who runs on it. Attribution is appreciated but not required.

## Start here

| If you have | Read |
|---|---|
| Two minutes | `The American Renewal Agenda - One-Page Summary.pdf` |
| Ten minutes | `The American Renewal Agenda - Candidate Brief.pdf` |
| An afternoon | Parts I–III of the full document, starting with the Core Agenda |
| A reason to check the work | Part VI (the money), Part VII (the law), Part XI (the sources) |

## Files

| File | What it is |
|---|---|
| `The American Renewal Agenda.pdf` | The full document, 249 pages. The fiscal model files are attached inside the PDF (open the attachments panel in a PDF reader). |
| `The American Renewal Agenda.md` | The same document as plain text, for searching, quoting, and reuse. |
| `The American Renewal Agenda - One-Page Summary.pdf` | The whole agenda on one page. |
| `The American Renewal Agenda - Candidate Brief.pdf` | Four pages for candidates and staff: what it asks, the twelve first-term priorities, the fiscal case, and short answers to hard questions. |
| `ARA_FiscalModel_2026.zip` | The fiscal model: program, inputs, workbook, and results. |

## How the full document is organized

| Section | Parts | What is in it |
|---|---|---|
| The Case | I–II | The argument and the principles |
| The Platform | III–V | All 112 proposals at a glance, the implementation sequence, and each proposal in depth |
| The Analysis | VI–VII | The fiscal case and the constitutional and procedural review |
| The Texts | VIII–IX | Model executive actions and the draft bills, each with notes for counsel |
| Reference | X–XII | Scoring method, source register, authorship, and glossary |

The **Core Agenda**, at the opening of Part III, is the shortest serious way in: twelve first-term priorities, each with evidence of support across party lines.

## Checking the numbers

Every figure in Part VI comes from a small model you can rerun.

    pip install numpy scipy openpyxl
    python3 fiscal_model.py     # rebuilds the tables
    python3 gen_part6.py        # rebuilds the text of Part VI

All amounts, factors, and source numbers live in one file, `ara_fiscal_inputs.json`. Change an assumption there and run the two commands again to see what happens to the totals.

## What this is not

- **Not legislation ready to introduce.** The bills are drafts; 325 amounts, rates, thresholds, and dates are marked `[TBD]` for legislative counsel and the Congressional Budget Office.
- **Not an official score.** The fiscal review follows the Congressional Budget Office's rules and shows its work, but only CBO and the Joint Committee on Taxation produce official scores.
- **Not legal advice.** The executive-action texts and bills have not been reviewed by government or legislative counsel. Each bill carries notes saying where the legal risks are.
- **Not an organization to join.** Adopt all of it, the Core, one pillar, or a single proposal.

Facts, figures, and legal status are current as of October 2026 unless a later date is given.

## Corrections and criticism

This document is meant to be checked. If you find an error, a broken citation, a number that does not reproduce, or evidence that cuts against a proposal, say so in public. Useful reports name the page or part, quote the claim, and give the source that contradicts it. Corrections supported by evidence will be made and recorded.

Disagreement with the policy choices is welcome too. That is what a serious document is for.

## Who made it

Authored by the Reform Democrats of the New Commonwealth (RDNC), a citizen policy think tank, and published for public adoption by the American Renewal Initiative (ARI).

The work was developed by a human author with the assistance of AI systems: principally Claude, developed by Anthropic, for research, drafting, structure, and editorial review; and GPT, developed by OpenAI, for independent review. Policy choices, judgments, and final decisions were made by the human author. Legislation on AI safety is reserved for human drafting.

**Public document. Free to distribute. The ideas belong to anyone willing to fight for them.**
