# Marie Hadley 2025 minor edits — leftover and follow-up

Source: `incoming/Wiki Minor Edits 2025 Marie.xlsx` (52 rows: 50 content edits + credits).
Processed 16 August 2026 on branch `2025edits`.

**Outcome: 49 of 50 content edits applied. 1 rejected on the law. Credits added (36 names).**

---

## 1. Edits not applied

### Row 35 — "change from 48 hours to 24 hours to reflect current law" — REJECTED

The contributor read the 48-hour figure in the trolling section as the service's compliance
window and assumed it was stale. It is not the same period.

- The **24 hours** referred to elsewhere in the chapter (ss 109/110 removal notices, Adult Cyber
  Abuse Scheme) is the **service's** window to comply after eSafety issues a notice.
- The **48 hours** in the trolling section is the **user's** wait after reporting to the platform
  before they may escalate to eSafety. This matches current eSafety guidance.

Applying the edit would have introduced an error. Text left unchanged.
Marie should be told why, in case she has a source that says otherwise.

### Rows 9 and 36 — conflicting eSafety statistics — RESOLVED DIFFERENTLY

Both rows replace the same paragraph in *Cyberbullying and hate speech* with "the 2025 eSafety
study", but give incompatible numbers:

| | Row 9 | Row 36 |
|---|---|---|
| Content associated with harm | 74% | — |
| Cyberbullied | 53% | 53% ("at some point") |
| Seen online hate | 60% | — |
| Experienced online hate | 27% | 15% (past 12 months) |

Checked against the source (eSafety, *Keeping Kids Safe Online*, surveyed Dec 2024 – Feb 2025,
n = 3,454 children aged 10–17):

- **53% cyberbullied — confirmed** (an "ever" figure).
- **74% seen or heard content associated with harm — confirmed.**
- **25% non-consensual tracking, monitoring or harassment — confirmed** (neither row had this).
- **60% / 27% / 15% online hate — not supported.** The closest published figure is 42% who had
  seen or heard offensive or threatening material directed at others because of their identity.

The paragraph was rewritten using only the verified figures, plus the demographic finding that
trans and gender-diverse children and girls were more likely to be affected. Neither
contributor's hate-speech numbers were used.

---

## 2. Contributor claims corrected during processing

These were applied, but not as submitted. Worth relaying to Marie so the corrections propagate.

| Row | Submitted | Applied |
|---|---|---|
| 5 / 23 | Two near-duplicate dotpoints, penalty "$49.5m" | Merged into one. Penalty restated as 150,000 penalty units ≈ $54.6m as at 1 July 2026 (the unit rose from $330 to $364) |
| 12 | "*Anthony Rotondo v eSafety Commission*" | *eSafety Commissioner v Rotondo* [2023] FCA 1296 — party order was reversed and the respondent is the Commissioner, not the "Commission" |
| 17 | "NSW does not have any similar legislation" | Over-broad. NSW *Crimes Act 1900* s 91N defines "intimate image" to include altered images, so ss 91P–91R do reach deepfakes. Reworded to "no dedicated deepfake provision" |
| 25 | Codes cover "search services" | Search engine code was a separate instrument (registered 12 Sept 2023, effective 12 Mar 2024). The five June 2023 codes cover internet carriage services, not search |
| 29 | NetAlert "adopted by only 12% of households" | The 12% referred to the target market. Replaced with the reported figures (~144,000 filters against a 2.5m household target; ~29,000 still in use) |
| 33 | "[2025] AATA 2582; [2025] AATA 2583" | Those are ART file numbers, and the tribunal is the Administrative Review Tribunal. Cited as *X Corp and Elston v eSafety Commissioner* [2025] ARTA 852 |
| 43 | BOSE Determination "amended in July 2024" | Registered 30 May 2024, commenced 31 May 2024. July 2024 is the date of eSafety's updated guidance |
| 49 | "a study conducted by RMIT University" | Henry, Powell & Flynn (2017) — a joint RMIT / Monash study |
| 50 | "The Liberal Party has expressed their intention" | Attributed to the Government of Canada |
| 39 | "amend footnote 4 … amend footnote 6 to 'n 4'" | The two footnotes were identified correctly but the instructions were swapped. The bare numeric cross-reference was replaced with a short-form citation so it no longer depends on rendered numbering |
| 4 | "European Economic Zone" | European Economic Area. The submitted claim that the GDPR "applies only" within the EEA was also wrong — art 3(2) extends it extraterritorially |
| 53 | "prospective" term extension | Correct on the law and applied. The AUSFTA amendments (effective 1 Jan 2005) did not revive expired copyright |

---

## 3. GitHub issues to raise

No `gh` CLI available in the processing environment — these need to be created manually.

1. **Deepfake creation offence — stale text at content.md line ~198.** Still describes the
   pre-2024 s 474.17A ("aggravated offence … private sexual material"), which the *Criminal Code
   Amendment (Deepfake Sexual Material) Act 2024* (Cth) repealed along with the s 473.1 definition
   of "private sexual material". Needs rewriting to the current transmission offence.

2. **Rotondo civil penalty not recorded.** The chapter stops at the 2023 contempt fine. In 2025
   the Federal Court ordered a $343,500 civil penalty for the s 75 contraventions (Longbottom J).

3. **Penalty unit figures will go stale.** Dollar amounts across `content.md` and `privacy.md` are
   now expressed as penalty units with an "as at" date, but the *Crimes Act 1914* (Cth) s 4AA(8)
   point — whether indexation carries to civil penalty provisions as it does to offences — is not
   settled in the text. Worth a specialist's eye.

4. **Verify the *Elston* citation and appeal status.** [2025] ARTA 852 was derived from a
   secondary source; AustLII blocks automated access. Confirm the medium-neutral citation against
   AustLII, and check whether eSafety has appealed. A `{: .warning}` currency flag is in place
   pending that check.

5. **Third-party explainer videos.** Rows 10, 11 and 20 introduced YouTube videos from a
   compliance vendor (Clym), an independent channel (Mental Outlaw) and VICE News. All three are
   labelled as third-party commentary with links to primary sources alongside, but they sit below
   "primary sources > authoritative secondary > general commentary" in the house hierarchy.
   Editorial call on whether to keep them.

6. **`Sexually explicit deepfakes.pdf` is missing.** Row 17 asked for a footnote linking to this
   local file; it does not exist anywhere in the repo. The footnote is a plain AGLC citation to
   Tom Gotsis, *Sexually Explicit Deepfakes and the Criminal Law in NSW* (NSW Parliamentary
   Research Service, April 2025) with no link. Add the PDF to `/assets/` or link the publisher.

7. **`artificial_intelligence.md` needs a citation pass.** Three dead footnote definitions were
   deleted (McCarthy on "what is artificial intelligence"; Iberdrola; Statista). They plausibly
   belonged to the opening definition and to history/market-size prose that has since been cut.
   The file still mixes italicised and unitalicised Act titles and omits years in places. The
   "AI as a Regulatory Tool" list also has a stub item ("Content regulation is another area").

8. **`privacy.md` — OAIC has changed its publication format.** It stopped issuing standalone
   six-monthly PDF reports after July–December 2024 and now publishes a rolling dashboard plus
   media releases. The chapter's framing around "reporting periods" should be revisited.

9. **`privacy.md` — "SPAM Act" vs *Spam Act*.** The heading and some prose style the short title
   in all caps. New text uses the correct form; the rest needs a cleanup pass.

10. **`copyrightduration.md` — transitional scheme framing.** Sch 9 item 132 of the *US Free Trade
    Agreement Implementation Act 2004* (Cth) covers works and other subject matter generally, not
    just photographs, but the paragraph still frames it inside the photographs sentence.

---

## 4. Rendering bugs fixed in passing

Pre-existing, not raised by the contributor, but breaking on the live site:

- `regulation.md`: an unclosed markdown link in the Newzbin footnote was swallowing three
  paragraphs of body text into the footnote.
- `regulation.md`: `[^johsonpost913]` reference had no definition (typo against
  `[^johnsonpost913]`); duplicate Elmer-DeWitt definition removed.
- `content.md`: five orphaned references `[^14]`–`[^18]` had their definitions stranded in
  `artificial_intelligence.md`. Verified as matching, moved across, relabelled to mnemonics.
- `privacy.md`: labels `[^1]`–`[^4]` were each defined twice, so half those citations rendered
  the wrong source. Second set relabelled.
- `copyrightduration.md`: three duplicate (byte-identical) definitions removed.
- `content.md`: four `•` characters used as bullets converted to markdown list markers.
- `artificial_intelligence.md`: a broken pandoc ASCII-art table rendering as unreadable text
  replaced with a proper markdown table.

All eight touched files now report zero duplicate definitions, zero orphaned references and
zero unused definitions.

---

## 5. Credits

Sheet 2 of the workbook. Added to `content/cyberlaw/credits.md` (35 names) and
`content/ausip/credits.md` (1 name: James Burke). No duplicates against the existing lists.

The two annotations in column D ("36 students for small edits", "52 small
edits/alterations/additions") were read as counts, not names.
