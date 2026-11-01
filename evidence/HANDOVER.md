# Handover: UK Skilled Worker dependant partner application

Read this first. It explains the case, what is done, what is left, and the rules the evidence pack follows.

## The case

- **Applicant:** Ji Cheng CHAN ("Jessie"), Malaysian, born 29 Sep 2001. Passport name CHAN JI CHENG; also appears as "Ji-Cheng Chan", "Jicheng Chan", "Ji Chan", "Jessie Chan".
- **Current visa:** Graduate visa, valid until **27 Dec 2026**. The application must be submitted in time, inside the UK. Target: early December 2026 at the latest.
- **Sponsor:** Arnaud Pierre Frédéric BADER, Swiss. Skilled Worker visa 20 Oct 2025 – 20 Oct 2028, employer Wintermute Trading Ltd.
- **Route:** unmarried partner (durable relationship, at least 2 years "akin to marriage").
- **Key dates:** matched on Hinge 16 Aug 2024; first date 28 Aug 2024; exclusive 30 Aug 2024; lived apart (Manchester / London) until Feb 2025; both in London from 20 Feb 2025 (she lived at a friend's flat, 5 Kingswood Close, Nine Elms); moved in together **6 Aug 2025** at **Flat 13, 7-8 Bloomsbury Square, London WC1A 2LP** (tenancy in Arnaud's name).

## What is in this folder

| Path | What it is |
|---|---|
| `01_Statement/Relationship-statement.docx` | The relationship statement (sections 1–10), editable. Remaining gaps are marked **[TODO: …]** in bold. |
| `01_Statement/Working-notes-and-letter-drafts_NOT-FOR-SUBMISSION.docx` | Evidence tracker, risk analysis, and drafts of the supporting letters (Arnaud, landlord, Kunyuan, Andrea). **Never submit this.** |
| `01_Statement/relationship-statement_source.html` | The source both DOCX files were generated from (statement above the `<hr>`, notes below). |
| `02_Exhibits/Exhibit-XX_…/` | One folder per exhibit: an **editable `.docx`** (caption + image per page), the finished `.pdf`, the original image files (numbered), and `captions.txt`. |
| `CHECKLIST.md` | Everything still needed from the applicant. |
| `03_Tools/` | `exhibits.json` (the exhibit registry: id, title, status, files, captions) and the Python scripts used to build the PDFs and this pack. Paths inside the scripts point to the original machine and must be changed before reuse. |

## Status: 31 of 40 exhibits sufficient

Withdrawn (do not reintroduce): **8, 12, 13, 20f, 35**.

Done: 1, 2, 3, 4, 5, 9, 10, 11, 16, 18, 20a, 20b, 20c, 20d, 20e, 20g, 20h, 20i, 21, 23, 24, 25, 26, 27, 28, 29, 30, 32, 33, 34, 37.

Remaining (details in `CHECKLIST.md`):

| Exhibit | What | Status |
|---|---|---|
| 6 | WhatsApp, Jul 2025 (about moving in) and Aug 2025 (moving day) | Sep 2024 – Feb 2025 done; Mar – Jun 2025 deliberately skipped (photos in Exhibit 16 cover them). Applicant has parked this. |
| 7 | 3–5 Amazon orders Arnaud paid for, delivered to her before 6 Aug 2025 | Not started. The statement paragraph citing it has a [TODO] for gift examples. |
| 14 | Bank lines for payments to Kunyuan Cheng | Partial; parked until Kunyuan replies. |
| 15 | Kunyuan Cheng's signed letter + ID | Draft ready; waiting for her. |
| 17 | Arnaud's mould complaint email (2 Apr 2024) + May 2024 Amazon mould orders | Not provided. |
| 19 | Landlord's final signed letter | Draft ready; must say "6 August 2025" and "as his partner". |
| 22 | Amazon orders in Arnaud's name paid with her card + matching bank lines | Not started. |
| 31 | Andrea Migliolo's letter + ID, activity bookings, Tricount | Not started. |
| 36 | Arnaud's signed letter + passport + eVisa share code | Draft ready. |

## Rules this pack follows (please keep them)

1. **The documents decide.** If a document shows a different date or fact from what the applicant remembers, change the statement, timeline and letter drafts to match the document. Never the other way round.
2. **Only unedited documents.** Screenshots and PDFs must be exactly as the app, bank or email produced them. Blacking out private text is fine (say so in the caption); changing text, dates or names is not. A single altered document can lead to refusal for deception and a 10-year re-entry ban.
3. **Every claim the statement cites must have its exhibit in the pack.** If evidence is not available, reword the sentence so it does not cite an exhibit, or remove it.
4. **Captions state only what the document shows.** Where a year is not displayed (iPhone Photos hides the current year), say so and give the reason it is known. Where a photo is a forwarded copy without its original date, say that it carries no original date.
5. **Redaction:** blur ID/NI numbers, passport machine-readable lines and access PINs; keep names, photos, DOB and expiry visible. Bank documents are submitted unredacted.

### How documents were checked

- iPhone photos: the info panel (date, time, place) is shown in the screenshot; original JPEGs were checked for EXIF dates where available.
- WhatsApp: date label and contact name must both be visible; the same chat taken twice should differ only in scroll position and status bar.
- Revolut PDF transfer confirmations: the first 8 hex digits of the transaction ID are a Unix timestamp and must match the printed date.
- Emails and bookings: weekday must match the date; dates must agree everywhere in the document; forwarded-header format should match the applicant's other forwards.

### Documents that were not used, and why

These were rejected after checking; do not add them back without a verifiable original:

- A WhatsApp screenshot submitted twice with only the date label differing (11 vs 15 Nov 2024); a fresh capture dated 15 Nov 2024 is used instead and matches the call log.
- An Escape Hunt booking (#163850298) whose header says Tue 20 May 2025 while its booking details say Wed 20 May 2026.
- A Gym Group SMS screenshot with messages out of date order and passes booked months ahead.
- Five Revolut image confirmations dated Oct 2024 – Feb 2025 without transaction IDs; two match verified 2026 transfers by day and amount with the year and direction changed. Exhibit 8 was withdrawn as a result, at the applicant's request.
- Regent's Park photos (22 Feb 2025): removed at the applicant's request.

## Working with the applicant

- Ask **one question at a time**, request **one exhibit at a time**, say what you expect to see, and mark it done when it is sufficient. Show progress as N / 40.
- Do not over-request: a representative sample is enough (e.g. one photo per month, a handful of transfers).
- Do not make assumptions about documents the applicant shares for her own reference; ask what they are for.
- Kunyuan-related items and the moving-in chats are parked by the applicant's choice.
- The statement is written in the first person (the applicant). It is formatted for Google Docs at 12 px in the HTML source.
