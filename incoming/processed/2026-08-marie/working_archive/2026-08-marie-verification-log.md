# 2026-08-marie — citation and factual corrections made during integration

Errors found in the source documents and corrected before integration. Each is a change to what the
contribution asserted, not a stylistic edit.

| # | Doc | As submitted | Corrected to | Basis |
|---|-----|--------------|--------------|-------|
| 1 | 6 | Bill "passed by both houses on 10 December 2024"; Royal Assent also 10 December 2024 | Passed both Houses 29 November 2024; Royal Assent 10 December 2024 | Doc 22 states 29 November; `privacy.md` § 7(g) already records "It passed the Senate with minor changes on 29 November 2024". Assent on the day of passage is not possible. |
| 2 | 21 | *Telecommunications (Interception and Access) Act 1979* "mandates that internet entities must retain metadata for seven years" | Two years | TIA Act pt 5-1A s 187C. |
| 3 | 21 | APP 2 and APP 11 cited as *Privacy Act 1988* (Cth) s 14 | *Privacy Act 1988* (Cth) sch 1 (APP 2), (APP 11.2) | Section 14 provides that the APPs are set out in Schedule 1; it is not the source of the principles' content. |
| 4 | 21 | "*Attorney-General for the State of Queensland v GFA* [2025 QSC 19" | *Attorney-General (Qld) v GFA* [2025] QSC 19 | Malformed citation. |
| 5 | 21 | China, Russia **and North Korea** block Tor | China and Russia | The North Korea claim is not meaningful — there is no general public internet access to block. Dropped rather than asserted. |
| 6 | 21 | Author "Adam Ghazi" | Adam Ghazi-Tehrani | Author of the cited *Journal of Contemporary Criminal Justice* article. |
| 7 | 22 | Identification-information offence cited as *Crimes Act 1900* (Cth) | *Criminal Code Act 1995* (Cth) div 372, noting the NSW equivalent in *Crimes Act 1900* (NSW) s 192K | There is no Commonwealth *Crimes Act 1900*. The 1900 Act is NSW/ACT. |
| 8 | 22 | Doxxing offences inserted by sch 1 of the amending Act | Schedule 3 | The Act has three schedules: sch 1 privacy reforms, sch 2 serious invasions of privacy, sch 3 doxxing offences. Verified against the Act's own structure on the Federal Register of Legislation. |
| 9 | 12 | Telemarketing complaints grew "during the 2010's", motivating the 2006 Act | Removed the decade claim | The Act is from 2006; the 2010s post-date it. |
| 10 | 12 | Civil penalties "$1.56 million" / "$3.13 million" | Regulator's published figures ($222,000 per day infringement notices; $2.22 million per day court-imposed), with a note that maxima are set in penalty units and should be checked against the current unit value | The submitted dollar figures were computed at a superseded penalty unit value. `content.md` and `privacy.md` already handle penalty units this way. |
| 11 | 12 | Australia Institute survey "in 2008", "63% believed telemarketing should be banned" | Attributed to the Institute's discussion paper without asserting the year; "around two-thirds" | The year could not be verified and a 2008 survey cannot have motivated a 2006 Act. The 8.5 calls/month figure was corroborated. |
| 12 | 14 | Pump-and-dump enforced by ASIC under *ASIC Market Integrity Rules (Securities Market) 2017* (Cth), fines to $1,000,000 | *Corporations Act 2001* (Cth) pt 7.10 (market misconduct) | The Market Integrity Rules govern market operators and participants; the prohibition on market manipulation is in the Act. |
| 13 | 14 | "approximately one-quarter of bitcoin users (26%) and almost one-half of bitcoin transactions (46%) are related to illegal activity" stated as fact | Retained with attribution and a `{: .warning}` caveat that estimates vary by method and that the figure is from a single 2019 bitcoin study | *Tone & Writing*: "Present facts without sensationalizing"; *Source Management*: represent contested findings as contested. |
| 14 | 24 | *Privacy Act* **1998** (Cth) | *Privacy Act 1988* (Cth) | Typo. |
| 15 | 24 | "AI characters are considered high risk [under the EU AI Act] and have strict regulatory requirements" | Systems intended to interact with natural persons are subject to transparency obligations under art 50; high-risk classification attaches to the uses listed in the Act, not to conversational systems as a class | Regulation (EU) 2024/1689 arts 6, 50 and annex III. |
| 16 | 24 | BOSE "requires internet service providers" to deliver AI safely | Covered services (social media services, relevant electronic services, designated internet services) | The Determination does not apply to ISPs as such. |
| 17 | 24 | "Australia's Artificial Ethics Principles" | Australia's AI Ethics Principles | Name of the framework. |
| 18 | 20 | Infringement claims brought "under s 116 of the *Copyright Act*"; remedies at s 116(1E) | Section 115 | Section 115 confers the action and remedies; s 116 concerns conversion and detention. |
| 19 | 20 | Negligence presented as an available remedy for authors ("foreseeable duty of care ... clear economic loss") | Reframed in a `{: .note}` as facing substantial doctrinal obstacles, with no successful claim | Australian law restricts recovery for pure economic loss; asserting a duty here would be a statement of law the sources do not support. |
| 20 | 20 | *University of New South Wales v Moorhouse* (1975) 6 ALR 193 | (1975) 133 CLR 1 | Authorised report preferred per *Source Management → Hierarchy*. |
| 21 | 7 | "*Uniform Defamation Act 2005* (NSW)" | *Defamation Act 2005* (NSW) | No Act of that name. |
| 22 | 7 | "*Perkins and Talmax Pty Ltd v Telstra Corporation Ltd* [1996] QCA 412" | *Talmax Pty Ltd v Telstra Corporation Ltd* [1997] 2 Qd R 444 | Party name and authorised report. |
| 23 | 7 | "Australia does not have any right to privacy laws that prevent the unauthorised use of a person's image" | Retained, but updated to address the statutory tort and to explain that it does not assist a deceased person's estate | The statement was written before the June 2025 commencement of sch 2. |
| 24 | 10 | Penalties "$9.9 million (30,000 penalty points)" / "$49.5 million (150,000 penalty points)" | Cross-referenced to the figures already in `content.md` (150,000 penalty units, $54.6 million as at 1 July 2026) | Submitted figures were computed at the superseded $330 penalty unit; the repository already carries the corrected figure and cites s 63D. |
| 25 | 4 | "children under the age of 16 are unable to consent under the *Online Safety Act 2021* (Cth) s 21" | Removed; the section leads with the criminal law definitions and offences | The proposition as stated does not follow from s 21, and the consent framing is not how either the OSA or the criminal law approaches child abuse material. |
| 26 | 13 | "*Criminal Code 1995* (Cth)" | *Criminal Code Act 1995* (Cth) | Name of the Act, matching repository usage. |
| 27 | 11 | "Maslow is correct when he says ..." | Barlow | The passage discusses Barlow throughout. |
| 28 | 19 | *Google LLC v Defteros* [2022] HCA 27, "15" and "75" (page references) | Paragraph pinpoints | The document cites paragraphs in page form. |
| 29 | 15 | *Online News Act* SC 2023 c 19 (Canada) | SC 2023, c 23 | Chapter number. |
| 30 | 25 | *Criminal Code Amendment (Deepfake Sexual Material) **Bill** 2024* | ... *Act* 2024 (Cth) | The Bill was enacted. |

## Verified as submitted

- *Criminal Code Act 1995* (Cth) ss 474.17C (6 years) and 474.17D (7 years) — doxxing penalties.
- *Criminal Code Act 1995* (Cth) ss 474.22, 474.23 (15 years each) and s 474.27 (15 years).
- *Privacy Act 1988* (Cth) s 26GC and the 24-month deadline for the Children's Online Privacy Code.
- The three YouTube videos resolve and are publicly accessible (HTTP 200 with metadata via the
  YouTube oEmbed endpoint, checked at integration time).

## Not verified

Secondary sources (journal articles, law firm briefings, news reports) were checked for correct form
and, where a URL was given, that the URL was well-formed and pointed at the named publication. Their
contents were not independently re-read. Where a claim rests only on such a source and is material,
it is attributed in the text rather than stated as fact.
