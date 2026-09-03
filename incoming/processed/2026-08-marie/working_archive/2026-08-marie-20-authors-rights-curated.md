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
