# Sample Cases — Reviewer Examples

## Example 1 — DRT Section 19 original application

> *"Draft a DRT original application under Section 19 RDDB Act for recovery of ₹[SUM-X] from [BORROWER] with default events documented and security interest enumerated."*

Tool sequence: list_case_types → get_case_type_format("drt-original-application") → get_pleading_base → draft → save_draft_as_docx

## Example 2 — NI Act 138 cheque-dishonour complaint

> *"Draft a complaint under Section 138 NI Act for dishonour of cheque No. [CHQ-N] dated [DATE] for ₹[SUM-Y] drawn by [DRAWER] with statutory notice served and 15-day window expired."*

Tool sequence: list_case_types → get_case_type_format("ni-act-138-complaint") → get_pleading_base → draft → save_draft_as_docx

## Example 3 — IBC Section 9 operational creditor application

> *"Draft an IBC Section 9 application as operational creditor against [CORPORATE-DEBTOR] for default of ₹[SUM-Z]. Section 8 demand notice served on [DATE], no dispute raised."*

Tool sequence: list_case_types → get_case_type_format("ibc-section-7-application") → get_pleading_base → draft → save_draft_as_docx

## Notes
- All placeholders. No real client data. `save_draft_as_docx` requires `pandoc`.
