# Wolfgang Rush — Indian Banking & DRT Drafting

**MCPB Desktop Extension** for banking + DRT + SARFAESI + NI Act 138 + IBC drafting work.

> *Also available as a Claude Code Plugin:* *[github.com/Wolfgangrush/indian-banking-drafting-litigation](https://github.com/Wolfgangrush/indian-banking-drafting-litigation)*

## Case types (10)

- `drt-original-application` — DRT Section 19 RDDB
- `drat-appeal` — DRAT Section 20 RDDB
- `sarfaesi-13-2-notice` — SARFAESI Section 13(2)
- `sarfaesi-14-cmm-dm-application` — SARFAESI Section 14
- `sarfaesi-17-securitisation-application` — SARFAESI Section 17
- `ni-act-138-complaint` — NI Act Section 138
- `ni-act-138-reply-notice` — Reply to statutory notice
- `ibc-section-7-application` — IBC Section 7 financial creditor
- `ibc-section-95-application` — IBC Section 95 personal guarantor
- `civil-recovery-suit` — CPC + NI Act recovery suit

## Install

Claude Desktop App → **Settings → Extensions → Install Extension** → `wolfgang-indian-banking-drafting.mcpb` → Enable

## System requirements

Claude Desktop App ≥ 0.10.0 · Python ≥ 3.10 · `pandoc` · `pdftotext` (optional)

## Privacy

Zero data collection. Three-layer privacy firewall. **<https://wolfgangrush.github.io/privacy/>**


## ⚠️ AI verification disclaimer · 🔒 Pseudonymisation procedure

> **⚠️ AI can make mistakes — please verify the information before filing.**
> Every draft produced by this connector is a STARTING POINT. The Verifier
> agent runs an anti-hallucination firewall and the Overseer agent runs an
> opposing-counsel review, but neither replaces an advocate's independent
> verification of statutory references, citation accuracy, factual fidelity,
> and Registry-formatting compliance with the user's High Court / forum.
> The advocate filing the pleading remains responsible for the contents.
>
> **🔒 Protected by pseudonymisation procedure.** The Reader agent applies a
> domain-specific privacy firewall as the first step of the pipeline — party
> names, addresses, identifying numbers (FIR / CR / Crime / Suit / Diary /
> SLP / lower-court case numbers), PAN / Aadhaar references, financial
> figures, witness names, and statutory-notice references are substituted
> with structural placeholders BEFORE any downstream agent sees the facts.
> The Drafter, Verifier, Refiner, and Overseer agents process placeholders
> only. Real values are re-substituted at the final docx render step on the
> user's local machine. No real identifying data leaves the case folder.

## License

MIT. **Publisher:** Rushikesh R. Mahajan publishing as Wolfgang Rush · advrushikeshravindramahajan@gmail.com · <https://github.com/Wolfgangrush/indian-banking-drafting-mcpb>
