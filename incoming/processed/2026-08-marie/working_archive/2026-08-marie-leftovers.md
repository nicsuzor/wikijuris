# 2026-08-marie — leftovers not integrated

Material from the batch that was not carried into `content/`, with the reason. Nothing in this
batch was dropped silently.

## Doc 2 (Trolling) — proposed Online Safety Act amendment

**Not integrated.** The document's final third proposes an amendment to the *Online Safety Act 2021*
(Cth) requiring social media services to make users complete a "mandatory anti-trolling education
form" and a questionnaire before being granted access, with account suspension and a further form on
detection of derogatory terms. It is written as the author's own recommendation.

**Reason.** `docs/agents/INSTRUCTIONS.md` → *Core Principles*: "Neutral perspective: Remove
opinion/interpretation." Decision taken by N Suzor during integration: cut to leftovers and raise an
issue rather than reframe. The descriptive parts of the document (statistics, the Indy Clinton case
study) were integrated.

**Tracked as:** GitHub issue (see PR description).

## Doc 2 (Trolling) — prevalence statistics

**Not integrated.** "More than one in three Australians have experienced online trolling"; "44% had
at least one negative online experience"; "21% reported the online harassment" (sourced to an Edith
Cowan University marketing blog); "53% of young Australians have been cyberbullied" (sourced to
Srivastava (2024)).

**Reason.** *Quality Standards → Source Management* (hierarchy: primary > authoritative secondary >
general commentary). `content/cyberlaw/content.md` already carries equivalent figures from the
eSafety Commissioner's *Keeping Kids Safe Online* survey (n=3,454, nationally representative),
including the 53% cyberbullying figure from the primary source. Retaining the blog-sourced figures
would duplicate weaker versions of data already present.

## Doc 3 (Sharenting) — material duplicating the privacy chapter

**Not integrated.** The Wren Eleanor case study, the definition of "sharenting", the risk list, and
the discussion of France's Children's Image Rights Law.

**Reason.** `content/cyberlaw/privacy.md` § "Children's online privacy and sharenting" already
covers all of this, including the same Wren Eleanor case study. *Quality Standards → Verification*:
"Remove duplication: Check across and within chapters." The document's distinctive contribution —
the content-regulation analysis, algorithmic amplification, child-influencer commercialisation, and
the UK comparison — was integrated into that existing section.

**Placement deviation.** The mastersheet assigns this to `content.md` § 11(d). Integrated into
`privacy.md` instead, on N Suzor's decision during integration.

## Doc 7 (Digital afterlife) — material duplicating the privacy chapter

**Not integrated.** Digital assets/succession, memorialisation and legacy contacts, post-mortem
privacy, AI griefbots and the Digital Afterlife Industry.

**Reason.** `content/cyberlaw/privacy.md` § "The Digital Afterlife" already covers each of these at
greater length. The genuinely new material — the eSafety digital assets/digital presence
distinction, Chinese AI funeral recreation practice, and the defamation/consumer-law route to
controlling use of a person's image — was integrated into that section.

**Placement deviation.** The mastersheet assigns this to `content.md` § 11(d). Integrated into
`privacy.md` instead, on N Suzor's decision during integration.

**Also not integrated:** "91% of Baby Boomers and older are present on multiple social media sites
for up to 20 hours per week"; "the gap narrowing with younger generations to 27%"; "Only 33% of the
general population understood ... digital assets". No source is given for the first two, and the
third is attributed to Steen et al without a pinpoint. *Quality Standards → Verification*: "Flag
uncertainties".

## Doc 4 (Exploitation of children online) — advocacy and promotional material

**Not integrated.** The sections headed "Campaigns and foundations" and "Using the internet for
good", which recommend the Stop It Now! campaign and two podcasts, and argue that "Awareness and
education are the two key elements in preventing CAM".

**Reason.** *Core Principles*: neutral perspective; *Tone & Writing*: "Focus on legal gaps, not moral
panic". The enforcement statistics and the multi-agency structure were integrated.

**Placement note.** The mastersheet anchors this to `crime.md` § "Other crimes involving computers".
Integrated as a new section "Child Sexual Exploitation Online" co-located with Doc 13 (online
grooming), because the two documents cover the same subject matter and separating them would
duplicate the Online Safety Act discussion. Cross-reference stubs were added at the mastersheet's
anchor so the mastersheet's map still resolves.

## Doc 23 (AI copyright) — Australian subsistence analysis

**Not integrated in full.** The detailed treatment of s 32 "qualified person" and the originality
test.

**Reason.** `content/cyberlaw/intermediaries_copyright.md` § "AI and Copyright" already covers
subsistence, the qualified-person requirement and the *IceTV* originality test. Summarised and
cross-referenced instead. The document's distinctive material — voice cloning, the "Heart on My
Sleeve" case study, and the US/UK comparative analysis — was integrated in full.

## Doc 20 (AI) — chapter outline

**Not integrated.** The numbered outline at the head of the document, which is a plan for the page
rather than content.

**Reason.** Structural instruction, not textbook text. It was followed in placing the material.

## Doc 14 (Crypto) — market manipulation and monetary policy

**Removed from `content/cyberlaw/privacy.md` after first-pass integration.** The
"Market manipulation" and "Regulatory approaches" subsections of the cryptocurrency material:
pump-and-dump schemes and the *Corporations Act 2001* (Cth) market misconduct provisions, the
comparative US/China/Singapore/Switzerland/Australia survey of crypto-asset regulation, and
central bank digital currencies.

**Reason.** Out of scope for the privacy chapter. `docs/agents/INSTRUCTIONS.md` → *Structure*:
"Keep sections focused". The material is financial-market and monetary-policy regulation, not
privacy or surveillance; it does not bear on the anonymity/pseudonymity question that makes
cryptocurrency relevant to this chapter. It is also substantially covered already in
`content/cyberlaw/follow_the_money.md` § "Crypto assets", which sets out the ASIC financial-product
test, exchange-traded products, AUSTRAC registration and the token-mapping strategy at greater
length. *Quality Standards → Verification*: "Remove duplication: Check across and within chapters."

The anonymity and pseudonymity material from the same document was retained and moved to
`content/cyberlaw/privacy.md` § "Cryptocurrency and pseudonymity", alongside the Tor material under
*Privacy-enhancing technology*, where it belongs.

**Possible destination.** `content/cyberlaw/follow_the_money.md`, if an editor judges the
pump-and-dump research and the comparative survey to add something to what that chapter already
carries. Preserved verbatim below, with footnotes.

---

### Market manipulation

A 'pump and dump' scheme is a form of price manipulation in which an asset's price is inflated by coordinated buying and promotion before the promoters sell, leaving later purchasers holding a falling asset. In conventional securities markets, this conduct is prohibited by the market misconduct provisions of the _Corporations Act 2001_ (Cth) and is enforced by the Australian Securities and Investments Commission (ASIC).[^cry_asic]

Cryptocurrency markets present two structural difficulties. First, where a crypto asset is not a financial product, the market misconduct provisions may not apply to it, and the regulator's information-gathering powers are correspondingly limited. Second, the timescale is very short: research on manipulation in crypto markets finds that a typical scheme lasts only several minutes, producing a sharp increase in price, volume and volatility followed by a quick reversal, which makes detection and enforcement after the fact considerably harder.[^cry_li]

There is some evidence that exchange-level rules affect the incidence of manipulation. Exploiting two natural experiments in which exchanges altered their pump-and-dump policies, the same study found evidence that pump-and-dump activity contributes to reduced liquidity and lower prices for the assets affected.[^cry_li2] This suggests that venue rules and listing standards may be a more responsive regulatory lever than after-the-fact enforcement.

### Regulatory approaches

**United States.** The Securities and Exchange Commission for a long period declined to approve proposed cryptocurrency exchange-traded products, citing concerns about market surveillance and susceptibility to manipulation in the underlying spot markets.

**China.** Chinese authorities have prohibited domestic cryptocurrency trading and mining outright.

**Singapore and Switzerland.** Both jurisdictions took an early approach of bringing cryptocurrency-related businesses within existing financial regulatory frameworks rather than creating a separate regime.

**Australia.** Australia has broadly followed the latter approach. Where a crypto asset falls within the existing definition of a 'financial product', the licensing, disclosure and market misconduct provisions of the _Corporations Act 2001_ (Cth) apply, and ASIC regulates it accordingly.[^cry_asicinfo] Where it does not, the position is less settled, and reform in this area is ongoing.

Proposals for central bank digital currencies have been advanced as one response, on the basis that a state-issued digital currency would combine the settlement advantages of the technology with an identifiable issuer. Central banks have raised countervailing concerns about the effect on monetary policy transmission and on the availability of economic statistics.[^cry_cbdc]

{: .note }
> Regulation of crypto assets in Australia is developing. This section describes the position as it stands at the time of writing and should be checked against current ASIC guidance and any subsequent legislation.

[^cry_asic]: _Corporations Act 2001_ (Cth) pt 7.10.

[^cry_li]: Tao Li, Donghwa Shin and Baolian Wang, 'Cryptocurrency Pump-and-Dump Schemes' (2025) 60(8) _Journal of Financial and Quantitative Analysis_ 3622 <https://doi.org/10.1017/S0022109025000201>. On the duration of a typical scheme, see also the authors' own summary: Tao Li, Baolian Wang and Donghwa Shin, 'Cryptocurrency Pump-and-Dump Schemes', _CLS Blue Sky Blog_ (Blog Post, 7 January 2019) <https://clsbluesky.law.columbia.edu/2019/01/07/cryptocurrency-pump-and-dump-schemes/> ('a typical cryptocurrency P&D lasts for only several minutes').

[^cry_li2]: Ibid.

[^cry_asicinfo]: Australian Securities and Investments Commission, _Digital Assets: Financial Products and Services_ (Information Sheet 225) <https://asic.gov.au/regulatory-resources/digital-transformation/crypto-assets/>.

[^cry_cbdc]: Monia Milutinović, 'Cryptocurrency' (2018) 64(1) _Ekonomika_ 105, 109–10.
