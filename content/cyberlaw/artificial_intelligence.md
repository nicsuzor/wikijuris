---
layout: default
title: Artificial Intelligence
nav_order: 105
parent: Governing the Internet
---


# Artificial Intelligence
{: .no_toc }

1. Table of Contents
{:toc}

This chapter explores the interaction between artificial intelligence (AI) and the internet, with a focus on the current growth in AI, the regulation of AI and associated challenges, and how AI can be used as a regulatory tool.


Artificial intelligence is a type of technology that simulates human
behaviour and creativity to perform tasks, mimicking human intelligence.
Most systems described as artificial intelligence today are built on machine learning. Deep learning is a subset of machine learning, and generative AI is an application built on top of both:

| Term | What it does | Example |
|------|--------------|---------|
| Machine learning | The broad technique: a system improves the accuracy of its decisions by analysing large datasets, often relying on human input to label or correct the data. | Facial recognition in smartphone technology |
| Deep learning | A subset of machine learning that uses layered neural networks to analyse data and draw inferences without human input at each step. | Chatbots and virtual assistants |
| Generative AI | An application built on machine learning and deep learning: it analyses patterns in existing data in order to create new material. | ChatGPT and Microsoft Copilot |

Generative AI has changed how people find information, producing answers to complex questions in seconds. These systems are trained on large datasets drawn substantially from the open internet. They rarely identify the sources underlying a given response, and where they do attribute, the attribution is not always correct. That creates a problem for the people whose work forms the training data: their material may be used without attribution, compensation, or any means of objecting. Whether Australia's existing legal framework adequately addresses this is the subject of active policy debate, discussed at [Authors' rights and remedies](#authors-rights-and-remedies) below.

## Regulation

Due to its rapid growth and development, regulatory mechanisms have struggled to keep up. However, the implementation of AI regulations has seen a sharp rise in recent years.[^5]

### Australia

Australian lawmakers have started to regulate the use of AI. The *Online Safety (Basic Online Safety Expectations) Determination 2022*,[^6] made under section 45 of the *Online Safety Act 2021* (Cth),[^7] is an attempt to ensure the safety of internet users and reduce the risk of misuse of AI-generated content online, including deepfakes. The Determination requires that internet service providers take reasonable steps to ensure that their delivery of AI to the consumer base has safety at the forefront of its design implementation and maintenance. Reasonable steps include undertaking safety assessments, providing educational tools for users, monitoring the data used as training material for the AI systems, and implementing ways of detecting harmful content. The Determination also requires that providers are proactive in their approaches to reducing the risk of their AI being used to create harmful content.[^8]

Other Australian state and national legislation such as the *Privacy Act,*[^9] the *Privacy and Personal Information Protection Act 1998* (NSW)[^10] and the Privacy Legislation Amendment (Enforcement and Other Measures) Act 2022[^11] can assist in regulating certain elements of AI use on the internet, but there is not yet any specific legislation that directly regulates the use of AI online. However, the Australian government is currently engaged in consultation around the safe use of AI in Australia and other policy activity. Notably:

- June 2023: a Discussion paper was released on the safe use of AI for public comment.[^12] Topics include the opportunities and challenges of AI, and strategies for managing the risks posed by AI.

- September 2023: the [AI in Government Taskforce](https://www.dta.gov.au/blogs/ai-government-taskforce-examining-use-and-governance-ai-aps) was set up

- January 2024: commentary was released by the government acknowledging the challenges presented by AI and detailing the potential mechanisms which may be required for the use of AI.[^13]

- February 2024: the [Artificial Intelligence Expert Group](https://www.industry.gov.au/science-technology-and-innovation/technology/artificial-intelligence#meet-the-ai-advisory-expert-group-4) was set up.

- June 2024: "The National framework for the assurance of artificial intelligence in government" was released. This framework deals with the government's use of AI.

- September 2024: the [Voluntary AI Safety Standard](https://www.industry.gov.au/publications/voluntary-ai-safety-standard) was released, and the [Policy for the responsible use of AI in government](https://www.digital.gov.au/policy/ai/policy) took effect.

- November 2024: the [Senate Select Committee on Adopting Artificial Intelligence](https://www.aph.gov.au/Parliamentary_Business/Committees/Senate/Adopting_Artificial_Intelligence_AI/AdoptingAI/Report) published its final report, which made 13 recommendations on the use of AI.


## Authors' rights and remedies

### The policy debate

Australian authors have called for dedicated legislation addressing the use of copyright works to train AI systems. Copyright income is a significant source of earnings for Australian writers, and survey research reports that 79% of Australian authors would not permit their existing work to be used to train AI models even if they were paid for it.[^ar_macquarie]

In November 2024 the Senate Select Committee on Adopting Artificial Intelligence recommended that AI developers be required to disclose the use of copyright material in training datasets, and that such use be licensed and paid for.[^ar_senate]

In August 2025 the Productivity Commission's interim report _Harnessing Data and Digital Technology_ proposed a text and data mining exception to the _Copyright Act 1968_ (Cth), operating either as a new fair dealing provision or as a broader exception, permitting the use of copyright works to train AI systems on specified conditions. The Commission estimated substantial economic benefits from the reform.[^ar_pc] The proposal was opposed by authors and publishers, on the basis that it would remove the licensing market that the Senate Committee had proposed to create.

The two proposals point in opposite directions: one would require payment for training use, the other would permit it without payment. Neither has been enacted.

### The existing framework

The _Copyright Act 1968_ (Cth) gives the owner of copyright exclusive rights including reproduction, communication to the public, and adaptation. 'Reproduction' is defined broadly and extends to digital conversion and to temporary copies.[^ar_s21] On its face, the reproduction right is engaged by the copying involved in assembling a training corpus.

Three features of the Act nonetheless limit its practical application here.

**Subsistence requires a human author.** Copyright subsists in original works made by a qualified person, which excludes works generated autonomously by a machine. The point is developed at [Generative AI and copyright in popular culture](#generative-ai-and-copyright-in-popular-culture) below and in the [Intermediary Liability for Copyright](../intermediaries_copyright/#ai-and-copyright) chapter.

**Proof.** Where a model is trained on a work but does not reproduce it in its outputs, an owner may be unable to demonstrate what was copied, when, or from which source, without disclosure from the developer. This is the practical reason the Senate Committee's transparency recommendation matters: without it, the reproduction right is difficult to enforce even if it is engaged.

**No Australian authority.** No Australian case has yet considered the application of the Act to AI training. In the United States, a court has held that wholesale copying of a competitor's material for the purpose of training a legal research tool was not fair use, which suggests one direction the analysis may take, though it turned on the competitive relationship between the parties.[^ar_reuters]

### Available causes of action

Where an owner does establish infringement, the remedies in the Act are available: injunctions, damages, and an account of profits.[^ar_remedies]

**Authorisation.** Sections 36(1) and 101(1) provide that a person infringes copyright by authorising an infringing act. _University of New South Wales v Moorhouse_ established that providing facilities that enable infringement, without taking reasonable steps to prevent it, may amount to authorisation.[^ar_moorhouse] Whether that reasoning extends to the supply of a generative model is untested.

**Safe harbours.** Section 116AC defines a Category A activity as providing facilities or services for transmitting, routing or providing connections for copyright material, or for its intermediate and transient storage in the course of transmission.[^ar_116ac] The safe harbour scheme was designed for carriage service providers. Whether an AI service that transmits or temporarily stores copyright material falls within it is an open question, and would depend on the function performed rather than on how the service describes itself.

**Contract.** Platform terms of service commonly prohibit scraping. Where a developer has accepted those terms and breached them, the platform — not the author — has the contractual claim, and the remedy is damages or an injunction.

**Breach of confidence.** Where a developer uses material that is not publicly available, such as a subscription database or a proprietary dataset, an action in breach of confidence may lie. The information must have the necessary quality of confidence, have been imparted in circumstances importing an obligation of confidence, and have been used without authority to the detriment of the confider.[^ar_coco] Material already available on the open internet will not satisfy the first requirement.

**Moral rights.** Authors have rights of attribution and against false attribution. Where an AI system reproduces or adapts a work without attribution, or attributes material to an author who did not create it, a moral rights claim is arguable. It is untested in this context.

{: .note }
> Claims in negligence for the economic loss authors suffer from unlicensed training use face substantial doctrinal obstacles in Australian law, which is restrictive of recovery for pure economic loss and reluctant to recognise a duty of care in these circumstances. No such claim has succeeded.

[^ar_macquarie]: Shujie Liang et al, _Australian Authors' Sentiment on Generative AI_ (Report, Macquarie University Business School, May 2025) 7 <https://doi.org/10.25949/T4CB-ZY56>.

[^ar_senate]: Senate Select Committee on Adopting Artificial Intelligence, Parliament of Australia, _Final Report_ (November 2024).

[^ar_pc]: Productivity Commission, _Harnessing Data and Digital Technology_ (Interim Report, August 2025).

[^ar_s21]: _Copyright Act 1968_ (Cth) s 21.

[^ar_reuters]: _Thomson Reuters Enterprise Centre GmbH v Ross Intelligence Inc_, No 1:20-cv-613-SB (D Del, 11 February 2025).

[^ar_remedies]: _Copyright Act 1968_ (Cth) s 115.

[^ar_moorhouse]: _University of New South Wales v Moorhouse_ (1975) 133 CLR 1. The decision is discussed in the [Intermediary Liability for Copyright](../intermediaries_copyright/) chapter.

[^ar_116ac]: _[Copyright Act 1968](https://www.legislation.gov.au/C1968A00063/latest/text)_ (Cth) s 116AC.

[^ar_coco]: _Coco v A N Clark (Engineers) Ltd_ [1969] RPC 41.

## AI as a Regulatory Tool

AI may be used to assist in regulating the internet. There are many examples of this, including

1. Fraud detection. For example, banks will use AI in real time to assess patterns of behaviour to determine whether fraudulent activity is taking place.[^19]

2. Spam filtering. For example AI will use learned algorithms to analyse massive amounts of data to identify characteristics, patterns and anomalies which may indicate spam.[^20]

3. Behavioural Patterns. For example, PayPal uses AI to monitor behavioural patterns of its users to identify potential fraudulent behaviour. If changes in spending patterns such as a large or out of character transaction is made, the transaction can be frozen pending authorisation.[^21]

4. Content regulation is another area.

### Case study: Algorithmic moderation as content regulation

"Algorithmic moderation" refers to the use of automated systems, typically powered by machine learning algorithms and artificial intelligence (**AI**) to monitor, evaluate and manage online content. These systems are designed to detect and take action against content that violates platform policies, such as hate speech, misinformation, or explicit material. Unlike human moderators, algorithmic moderation can process vast amounts of content in real-time, making it an essential tool for large-scale platforms like social media networks.

The concerns surrounding algorithmic moderation stem from its potential for errors and biases, which can result in the wrongful removal of legitimate content or the failure to detect harmful material. The implications of these errors are amplified by the vast reach of the internet, where decisions made by algorithms can impact millions of users in real time.

Whilst algorithmic moderation as a form of content moderation may be effective in removing illegal content, it has systemically struggled in removing harmful content, particularly where messages are communicated using rhetoric and nuance.[^alg_mod] Like with human moderation, it can be difficult to differentiate between what is "harmful" and what is merely a non-mainstream opinion.

## Generative AI and copyright in popular culture

Generative AI systems produce material — images, text, audio — by identifying and reproducing patterns in the data on which they were trained.[^gac_feuerriegel] Outputs may appear original while being shaped by that data, and may closely resemble particular works or the recognisable style of a particular creator. That raises two distinct questions: whether an output infringes copyright in an existing work, and whether the output attracts copyright at all.

### Voice cloning in music

Artificial intelligence has long been used in music production to supply instrumentation a musician cannot play, or to generate sounds that would be laborious to produce by hand. Voice cloning is a different proposition: it produces a synthetic voice that sings or speaks in the likeness of an identifiable performer.[^gac_wells] Where a tool is used not to assist expression but to replicate a particular person's, the boundary between human authorship and machine generation becomes difficult to locate.[^gac_cooper]

{: .example }
> **'Heart on My Sleeve' (2023)**
>
> In April 2023 a track titled 'Heart on My Sleeve', released by an anonymous creator using the name @ghostwriter, circulated widely on streaming services. It appeared to feature vocals by Drake and The Weeknd. Neither performed on it: the vocals were generated using voice cloning, without the involvement or consent of either artist.[^gac_snapes]
>
> Universal Music Group sought and obtained removal of the track from streaming services, characterising it as infringing and as a breach of its contractual and legal rights.[^gac_reed]
>
> The case is analytically awkward. The recorded performances used to train the model are protected, but the output reproduces no particular recording. What it appropriates is the performer's voice and identity — which Australian copyright law does not protect as such. The claim rests more comfortably on the reproduction involved in training, on contract, or on passing off and the consumer protection provisions dealing with misleading conduct, than on infringement by the output.

### Authorship

Copyright has historically protected original works created by human authors through the exercise of skill and judgement. Systems that generate content without human creative input in that sense sit awkwardly within the framework, and jurisdictions have diverged in how they respond.

**Australia.** The _Copyright Act 1968_ (Cth) requires that copyright subsist in an original work authored by a qualified person — an Australian citizen, resident or protected person.[^gac_s32] A work generated autonomously by a system has no author for the purposes of the Act, and so attracts no copyright, whatever its commercial or cultural value. Where a person uses a generative tool as an aid, the question becomes whether that person contributed sufficient independent intellectual effort to be an author. This analysis, and the originality test in _IceTV_, is set out in the [Intermediary Liability for Copyright](../intermediaries_copyright/#ai-and-copyright) chapter.

**United States.** The Copyright Office has maintained that protection is limited to works created by natural persons, and has declined to register works generated entirely by AI systems without sufficient human input. In _Thaler v Perlmutter_ a federal district court upheld that position, and the Court of Appeals for the DC Circuit affirmed in 2025, holding that the Copyright Act requires eligible work to be authored in the first instance by a human being.[^gac_thaler]

**United Kingdom.** Section 9(3) of the _Copyright, Designs and Patents Act 1988_ (UK) provides that, for a computer-generated literary, dramatic, musical or artistic work, the author is taken to be the person by whom the arrangements necessary for the creation of the work are undertaken.[^gac_cdpa] The United Kingdom therefore permits copyright to subsist where no human author can be identified, attributing it on the basis of who made the arrangements rather than who exercised creative judgement. The provision was enacted when computer-generated output was rule-based and limited, and its application to modern generative systems has not been tested.[^gac_cooper2]

### The absence of an international position

The Berne Convention does not define 'author', which leaves the question to national law.[^gac_berne] The result is that the same output may attract copyright in the United Kingdom, none in Australia or the United States, and something else again elsewhere — with no reliable way for a creator, user or rights holder to know in advance which applies to a work distributed globally.

Proposals for reform include extending the definition of authorship, creating a separate category of right for machine-generated output, and leaving such output unprotected on the view that copyright's incentive rationale does not apply to it. None has been adopted in Australia.

[^gac_feuerriegel]: Stefan Feuerriegel et al, 'Generative AI' (2024) 66(1) _Business and Information Systems Engineering_ 111.

[^gac_wells]: Bryn Wells-Edwards, 'What's in a Voice? The Legal Implications of Voice Cloning' (2022) 64(4) _Arizona Law Review_ 1215.

[^gac_cooper]: Zachary Cooper, 'The AI Authorship Distraction: Why Copyright Should Not Be Dichotomised Based on Generative AI Use' (Research Paper, Vrije Universiteit Amsterdam, 2024).

[^gac_snapes]: Laura Snapes, 'AI Song Featuring Fake Drake and Weeknd Vocals Pulled from Streaming Services', _The Guardian_ (online, 18 April 2023).

[^gac_reed]: Rachel Reed, 'AI Created a Song Mimicking the Work of Drake and The Weeknd. What Does That Mean for Copyright Law?', _Harvard Law Today_ (online, 2 May 2023).

[^gac_s32]: _Copyright Act 1968_ (Cth) s 32.

[^gac_thaler]: _Thaler v Perlmutter_, No 1:22-cv-01564-BAH (D DC, 18 August 2023), affirmed _Thaler v Perlmutter_ (DC Cir, 2025).

[^gac_cdpa]: _Copyright, Designs and Patents Act 1988_ (UK) s 9(3).

[^gac_cooper2]: Cooper (above).

[^gac_berne]: _Berne Convention for the Protection of Literary and Artistic Works_, opened for signature 9 September 1886, 1161 UNTS 3 (as revised).

[^5]: Stanford University, *Artificial Intelligence Index Report 2024* (2024).

[^6]: *Online Safety (Basic Online Safety Expectations) Determination 2022* (Cth) ("the Determination").

[^7]: *Online Safety Act 2021* (Cth).

[^8]: *Online Safety (Basic Online Safety Expectations) Determination 2022* (Cth).

[^9]: *Privacy Act 1988* (Cth).

[^10]: *Privacy and Personal Information Protection Act 1998* (NSW).

[^11]: *Privacy Legislation Amendment (Enforcement and Other Measures) Act 2022* (Cth).

[^12]: Australian Government Department of Industry, Science and Resources, *Safe and Responsible AI in Australia* (Discussion Paper, June 2023) \<https://storage.googleapis.com/converlens-au-industry/industry/p/prj2452c8e24d7a400c72429/public_assets/Safe-and-responsible-AI-in-Australia-discussion-paper.pdf\>.

[^13]: Julian Lincoln, Susannah Wilkinson and Alex Lundie, "Australia Government announces mandatory regulations for high-risk AI' (Article, Insight Australia, 18 January 2024).

[^19]: Ravi Sandepudi, 'The Banker's Guide: Using AI for Fraud Detection (Effective, 11 March 2024).

[^20]: David Emelianocm, 'Advanced Spam Filtering AI, *Trimbox* (Blog Post, 21 November 2023).

[^21]: Ashtynn Baltimore, 'Is AI changing customer expectations?' (2024) *PayPal Braintree Product Team.*

[^alg_mod]: Dayei Oh and John Downey, ['Does Algorithmic Content Moderation Promote Democratic Discourse? Radical Democratic Critique of Toxic Language AI'](https://doi.org/10.1080/1369118X.2024.2346531) (2025) 28(7) *Information, Communication & Society* 1157.
