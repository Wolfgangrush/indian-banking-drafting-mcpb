# Case Facts Background — NI Act § 138 cheque-dishonour complaint

All party names, addresses, cheque / account / invoice numbers, monetary figures, and ancillary dates are fictional placeholders.

## Parties

- **Complainant:** [Complainant-A], Sole Proprietor of M/s [Complainant-Firm-Placeholder], having business at [Complainant-Address-Placeholder]. Supplier of [Goods/Services-Placeholder].
- **Accused:** [Drawer-A], Authorised Signatory of M/s [Drawer-Firm-Placeholder], having office at [Drawer-Address-Placeholder]. Drawer of the dishonoured cheque.
- (If the drawer is a company / firm, the company and the signatory are arrayed as separate accused per Aneeta Hada v. Godfather Travels (2012) 5 SCC 661.)

## Underlying transaction

- Running-account dealings of supply of [Goods/Services-Placeholder] during [Trading-Period-Placeholder].
- Three invoices raised totalling Rs. [Total-Liability-Placeholder]/- (see `03-invoice-summary-supporting-debt.docx`), all acknowledged via signed delivery challans and LR numbers.

## Cheque particulars

- Cheque No.: [Cheque-No-Placeholder]
- Date: 10 January 2026
- Drawer: [Drawer-A] / M/s [Drawer-Firm-Placeholder]
- Drawee: [BANK-NAME-PLACEHOLDER], [BRANCH-PLACEHOLDER]
- Amount: Rs. [Cheque-Amount-Placeholder]/-
- Purpose: Discharge / part-discharge of subsisting liability under the three invoices.

## Chronology (key for § 138 / § 142 limitation)

- **10 January 2026** — Cheque issued and delivered to the complainant.
- **15 January 2026** — Cheque presented for clearing at [Presenting-Bank-Placeholder].
- **18 January 2026** — Cheque dishonoured for "Funds Insufficient" (see `01-bank-return-memo-2026-01-18.docx`).
- **25 January 2026** — Statutory demand notice issued under proviso (b) to § 138 NI Act 1881 (see `02-section-138-statutory-notice-2026-01-25.docx`). Despatched by RPAD and email.
- **30 January 2026** — Statutory notice deemed served (per Section 27 General Clauses Act + AC Narayanan v. State of Maharashtra (2014) 11 SCC 790).
- **01 March 2026** — 30-day compliance period expires; drawer has not paid.
- **02 March – 01 April 2026** — Cause of action window under proviso (c) to § 138 — complaint must be filed within 30 days of accrual.
- **As on filing** — within limitation; complainant approaches the JMFC / Metropolitan Magistrate of competent territorial jurisdiction (see Bridgestone India v. Inderpal Singh (2016) 2 SCC 75 for territorial jurisdiction at place of bank where complainant's account is maintained).

## Forum and case type

- **Forum:** Court of the Judicial Magistrate First Class (JMFC) / Metropolitan Magistrate within whose territorial jurisdiction the complainant's bank branch (the bank in which the cheque was deposited / collected) is situated. Per Section 142(2) NI Act + Bridgestone.
- **Case type:** `ni-act-138-complaint`.
- **Pecuniary:** No pecuniary cap for § 138.
- **Limitation:** 30 days from accrual of cause of action under proviso (c) to § 138 NI Act (extendable for sufficient cause under Section 142(1)(b) NI Act).

## Reliefs sought

1. Cognisance and process under Section 142 NI Act.
2. Conviction and sentence under Section 138 NI Act — imprisonment up to 2 years and / or fine up to twice the cheque amount.
3. Compensation under Section 357 CrPC / Section 395 BNSS for the cheque amount with interest from the date of dishonour.
4. Costs of the proceedings.

## Ingredient check (Verifier-stage)

- ✅ Cheque issued in discharge of a legally enforceable debt — proven by invoices + delivery challans.
- ✅ Cheque presented within validity (3 months) — presented 5 days after issue.
- ✅ Dishonour for insufficient funds — bank return memo on record.
- ✅ Statutory notice within 30 days of receipt of dishonour memo — sent 7 days after dishonour.
- ✅ Demand of cheque amount — explicit in notice.
- ✅ 30-day compliance window expired — drawer has not paid.
- ✅ Complaint filed within 30 days of expiry of notice period — within limitation.

## How to use this fixture

1. Point `read_case_folder(path)` at this directory.
2. Reader extracts facts from the 3 `.docx` files plus this `case-facts-background.md`.
3. Call `get_case_type_format("ni-act-138-complaint")` for the NI Act § 138 complaint template.
4. The remaining 5 agents (Format → Drafter → Verifier → Refiner → Overseer) run end-to-end to produce `final-draft.docx` containing the complaint + List of Witnesses + List of Documents + Verification.
