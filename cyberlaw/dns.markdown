---
layout: default
title: Regulating the Domain Name System
parent: Governing the Internet
nav_order: 80
---

# Regulating the Domain Name System

## Domain Names

DNS stands for Domain Name System ("DNS"). The DNS translates a domain name, which is the text that you type into a web browser to get to the website of your choice such as facebook.com, google.com or qut.edu.au, to its corresponding IP address, which is the unique series of numbers assigned to each device on the Internet. For example, one of facebook.com's IP address is '173.252.120.6'. Since domain name are relatively simple and comprise largely easy-to-remember words, the Domain Name System plays an important role in making the internet more accessible to users.

### The Domain Name Structure

Domain names, like _qut.edu.au_, have three main levels:
  * Top level domain (TLD) - e.g. '.au'
  * Second level domain (2LD) - e.g. '.edu'
  * Third level domain (3LD) - e.g. 'qut'

### Types of Domain Names

At the top of the DNS hierarchy is the root zone file, edited by Internet Assigned Numbers Authority (IANA), under the control of an agency of the US Department of Commerce. The root zone file contains a list of the names and numeric IP addresses of the authoritative DNS root name servers for all the top level domains published to the internet by 13 root name servers at more than 80 locations in 34 countries, maintained by a variety of organisations. Root name servers contain information about the name servers of all the top level domains (TLDs) and country code top level domains (ccTLDs), redirecting internet traffic to the name server for the relevant TLD or ccTLD as indicated in the domain name. Verisign Global Registry Services maintains the primary root server, called “a.root-servers.net” and copies of its central database, the root zone file, are stored on each of the 12 additional root servers.

The root name servers are computers that maintain the authoritative list of top level domain names and which contain pointers to other computers containing directories of domains at the second, third and subsequent levels of the hierarchy. The root name servers answer queries from other parts of the DNS but no internet traffic passes through them.  If a name server receives a query for which it does not have any information, it forwards the query to a root name server which then answers with a referral to the authoritative servers for the appropriate TLD or with an indication that no such TLD exists.  

TLDs can be either generic (gTLD) or country codes (ccTLD). Generally, ccTLDs can only be used by companies that are established in that location or individuals located there. Examples of gTLDs are '.edu', '.com', '.org' and '.net'. ccTLDs include '.au', '.uk' and '.de'.

TLDs can be open, restricted or sponsored. Open TLDS (e.g. '.com' and '.net') can be used by anybody. In contrast, to register a restricted domain name (e.g. '.edu' and '.gov'), eligibility criteria must be met. Finally, sponsored domain names (e.g. '.museum', '.jobs') are only available to particular stakeholders. An organition who sponsors the domain name is able to set rules about how these domains may be used.

### Registering A Domain Name In The .au ccTLDs

**Darren Brown Explains [Domain Name Registration in Australia](https://www.youtube.com/watch?time_continue=1&v=w5LSJMFaSsM)**

There are general rules that apply to all open 2LD domain names within the  .au namespace. A .au domain name licence may only be allocated to a Registrant who is an “Australian”. Each domain name is required to: consist of from 2 to 63 characters; contain only letters (a – z), numbers (0 – 9), hyphens ( - ) or a combination of these; start and end with a letter or number, not a hypen; not contain a hyphen in the third or fourth positions, eg ab-cd.com.au. Eligibility criteria differ among the .au 2LDs. For example, eligibility for .com.au and .net.au domain names is now based on the following indicators:

* an Australian registered company
* trading under an Australian registered business name; in any Australian State or Territory
* an Australian partnership or sole trader
* a foreign company licensed to trade in Australia
* an owner of an Australian registered trade mark or a trade mark application
* an association incorporated in any Australian State or Territory
* an Australian commercial statutory body

**Allocation Rules**

A Registrant can obtain a domain name in the .com.au, .net.au, .org.au and .asn.au open 2LDs if it:

* Exactly matches the name of the Registrant’s company or trading name, organization or association name or trade mark;
* Is an or acronym or abbreviation of the Registrant’s company or trading name, organization or association name or trade mark; or
* is otherwise closely and substantially connected to the Registrant.

**“Close and Substantial Connection”**

A Registrant may obtain a domain name licence for a name that has a close and substantial connection with the Registrant.((See Clause 10 of Guidelines for Accredited Registrars on the Interpretation of Policy Rules for Open 2LDs (2008-06) at http://www.auda.org.au/policies/auda-2008-06/)) This requirement was introduced in 2002. For .com.au and .net.au domain names, a “close and substantial connection” with the Registrant may be established where the name refers to:

* a product that the Registrant manufactures or sells;
* a service the Registrant provides;
* an event the Registrant sponsors or organizes;
* an activity the Registrant facilitates, teaches or trains;
* a venue operated by the Registrant; or
* a profession practised by the Registrant’s employees.

### Care and Control

The Domain Name System comes under the exclusive control of the Internet Corporation for Assigned Names and Numbers, [https://en.wikipedia.org/wiki/ICANN](ICANN), which is  an American company registered and based in California.  ICANN determines whether or not a domain can be registered, or if the translation to your IP address will be performed, and is a '[http://techland.time.com/2010/12/03/wikileaks-domain-name-killed-and-why-it-wont-kill-wikileaks/](choke point)' for regulation. The Australian Domain Administration (AuDA) is authorised by ICANN to administer the '.au' TLD. AuDA has licenced AusRegistry Pty Ltd to operate the '.au' domain name register. There are 34 registrars of open 2LDs in this domain space, with over 3000 resellers of Australian domain names.

### Registering and Transferring Domain Names

Domain names are registered on a first-come, first-served basis. There is no general prohibition on registering domain names if a similar trade mark exists and trade marks owners have no general right to own corresponding domain names. Further, there is no obligation on the Registrar to consider whether the requested domain name infringes the rights of any third party. These factors mean that anybody can apply to register an available domain name by entering a contract with the relevant domain name agency.

The registration of a domain name is valid for two years, with the option of renewal in perpetuity. Once a domain name expires, it immediately becomes available to the public. There are no limits on the number of domain names that a person can register.

Initially, the transfer of domain names was prohbited, in an attempt to stop people from deliberately registering domain names in order to profit from selling it. However, this restriction was removed in 2002. Today, a domain name can be sold and transferred provided that six months have passed since registration of a domain name.

## Domain Name Disputes

There is an apparent need for more straightforward, inexpensive procedures for resolving disputes between domain name Registrants and third parties about entitlement to register and use domain names. A WIPO report in 1999 entitled //The Management of Internet Names and Addresses: Intellectual Property Issues//  recommended the introduction of mandatory and uniform procedures for resolving disputes about names registered in the gTLDs. Acceptance of this recommendation led to development of the Uniform Domain Name Dispute Resolution Policy (UDRP). This policy was approved by ICANN in October 1999 and entered into force on 1 January 2000.

Following its introduction in 2000, the UDRP rapidly became the international standard for resolving domain name disputes. The UDRP establishes procedures for dealing with disputes between a domain name Registrant and a third party complainant (ie, a party other than the Registrar) in cases where the DN is identical or confusingly similar to the complainant’s trade mark and it is alleged that the domain name has been registered and is being used in bad faith.

The UDRP applies to disputes in the .com, .org, .net, .biz, .info and .name gTLDs. The UDRP is binding on all ICANN-accredited Registrars for these TLDs, through inclusion of the UDRP in their Registrar Agreements with ICANN. The UDRP is designed to protect existing trade marks by discouraging, and resolving disputes about the abusive registration of trade marks as domain names. Where a domain name has been registered in bad faith, it can be cancelled or transferred to the trade mark owner.

The UDRP acknowledges that other avenues are available for resolution of trade mark-based domain name disputes between a Registrant and third party complainant. For example, disputes can be resolved by mutual agreement between the parties, arbitration, or proceedings in a court of competent jurisdiction.

### Types of Disputes

Disputes over who should have the rights to use a domain name can arise in many different ways, including:

* __Competing Claims__: between trade mark owners with competing claims. So, for example, we might imagine a dispute between Apple Corps (the Beatles' record company) and Apple Computer.

* __Cybersquatting__: involves the bad faith, abusive registration and use of the distinctive trade marks of others as domain names, with the intention to profit from the goodwill associated with those trade marks, typically by offering the domain name for sale at a substantial profit (e.g. qant.as (registered in Western Samoa) and westp.ac (Ascension Islands)).

* __Typosquatting__: involves the registration of a deliberate misspelling of a popular domain name in order to divert trade or traffic – micrsoft.com

* __Criticism Sites__: domain name is registered with the aim of criticising or defaming another person or company

* __Reverse Domain Name Hijacking__: involves a complaint brought in bad faith by a third party against a domain name Registrant, in an attempt to deprive the Registrant of the domain name it has registered

### Elements of a Dispute

Under the UDRP and auDRP clause (4)(a), three requirements must be met for a domain name to be cancelled or transferred to the trade mark owner:
  * Must be identical or confusingly similar with a trade mark of the complainant;
  * The registrant has no right or legitimate interest in the domain name;
  * THe domain name must be registered and used in bad faith.

#### Legitimate Interest

Clause 4(c) provides the definition of a legitimate interest:
  * Bona fide offering of goods or services under the name;
  * The registrant has been commonly known by the domain name; or
  * A legitimate, non-commercial or fair use of the domain name, without intent for commercial gain to misleadingly divert consumers or to tarnish the trade mark or service mark at issue.

#### Bad Faith

**Watch an [overview of the UDRP and the meaning of 'bad faith'](https://youtu.be/WFdUt9urNhs) by Josephine Hungerford**

The UDRP does not provide an explicit definition of ‘bad faith’, but both the UDRP and AuDRP enumerate circumstances amounting to bad faith in clause 4(b):
  * Domain name registered primarily for the purpose of selling, renting or otherwise transferring the domain name registration to the owner of the trade mark or service mark or their competitor;
  * Domain name registered in order to prevent the owner of the trade mark or service mark from reflecting the mark in a corresponding domain name;
  * Domain name registered primarily for the purpose of disrupting business of a competitor; or
  * By using the domain name, the registrant has intentionally attempted to attract, for commercial gain, internet users to the website, by creating a likelihood of confusion with the complainant's mark.

Where the second registrant can establish a right and legitimate interest in the domain name under paragraph 4(c) of the UDPR, it is likely that the domain name has not been registered in bad faith. Circumstances which indicate that the domain name has not been registered in bad faith include the honest use of the domain name in connection with an offering of goods or services, the registrant of the second domain name being commonly known by the domain name or the legitimate and non-commercial use of the domain name without the intent to divert the consumer or tarnish the name or trademark in question.

### Domain Name Disputes in Australia

Administrative dispute resolution procedures based on the UDRP have been adopted by the administrators of many ccTLDs, including the .au ccTLD. The .au Domain Administration (AuDA) board((Current auDRP proceedings are available at http://www.auda.org.au/audrp/current-proceedings/. Archived proceedings can be accessed at http://www.auda.org.au/audrp/proceedings-archive/.
)) approved the //Dispute Resolution Working Party Report// (June 2001) recommendations for a dispute resolution policy. It adopted the AuDRP, which is based on the UDRP, and applies to all .au subdomains. The auDRP commenced on 1 August 2002.((http://www.auda.org.au/policy/audrp)) The AuDRP provides for cheaper, faster alternatives to litigation for resolution of disputes between a registrant and another party who claims to have rights to the domain name. Complaints are submitted to any auDA-approved dispute resolution providers and are heard by a panel of either 1 or 3 providers. Providers, each who have their own rules, include:
  * Leading Edge ADR (LEADR)
  * Chartered Institute of Arbitrators (CIArb)
  * Institute of Arbitrators & Mediators Aust (IAMA)
  * WIPO

### Domain Name Disputes in the United States

In the United States, the inadequacies of the existing laws in dealing with cybersquatting led Congress to enact the //Anticybersquatting Consumer Protection Act 1999// ("ACPA") which amended the //US Trademark Act 1946// (the Lanham Act)
ACPA creates civil liability for registration, trafficking in or use of a domain name that is identical or confusingly similar to a distinctive trade mark or which dilutes a famous trade mark. It applies to personal names as well as distinctive trade marks and famous trade marks where the registration, trafficking in or use of the domain name is done with a bad faith intent to profit from the mark

The ACPA sets out a non-exhaustive list of factors to be applied in determining, on a case-by-case basis, whether a domain name holder is acting in bad faith. Remedies under the ACPA include injunctions, forfeiture, cancellation or transfer of the domain name, recovery of profits and actual damages or, at the election of the trade mark owner, statutory damages of $1,000 to $100,000 per domain name.

### Examples of Domain Name Disputes

**The "sucks" cases - Wal-Mart Stores, Inc. v. wallmartcanadasucks.com and Kenneth J. Harvey (Case No. D2000-1104)**

A domain name was registered as 'wallmartcanadasucks.com'. It was held that this was free speech, and there was public interest in parodic expression. Therefore, no cyber-squatting occurred. C/f the earlier case of Wal-Mart Stores, Inc. v. Walmartsucks and Walmarket Puerto Rico (Case No. D2000- 0477).

**Celebrity Names**

In the case involving the domain name 'brucespringsteen.com', the panel stated that “the Internet is an instrument for purveying information, comment and opinion… and any attempt to curtail its use should be strongly discouraged” & thus, there is no cybersquatting c/f older cases such as 'celinedion.com' and 'juliaroberts.com'. The law remains unclear in this area.

**Facebook Inc. v. Callverse Pty Ltd (Case No. DAU2008-0007)**

The complainant was Facebook Inc and the respondent Callverse Pty ltd (from Australia). The disputed domain name 'facebook.com.au' was registered by the respondent with NetRegistry Pty Ltd. Facebook owned numerous trade marks for the FACEBOOK word that were registered in many countries worldwide. It had five registered trade marks for the FACEBOOK word in Australia, two of which were registered prior to commencement of the proceedings. The disputed domain name was first registered by Cocktail King Australia Pty Ltd in 2005 and was transferred to Callverse in October 2007. Callverse was the proprietor of a business in New South Wales called "Face Book".

It was held that registration of a domain name before a complainant acquires trade mark rights in a name does not prevent a finding of identity or confusing similarity, as no specific reference to the date of acquisition is made in the AuDRP. If registration of the disputed domain name predates the acquisition of the trade mark, that fact may be relevant to the assessment of whether or not a respondent has rights or a legitimate interest in the domain name or whether the registration was in bad faith. The trade mark, however, was inherently distinctive, and therefore the disputed domain name incorporated a distinctive mark in its entirety and was thus confusingly similar to the trade mark.

Further, it was held to be highly likely that a significant number of internet users would beleive that the disputed domain name would lead to Facebook's website. Cocktail King, who originally registered the domain name, had no connection with Facebook. Callverse never offered any products or services of its own under the name FACEBOOK, there is no evidence that Callverse is commonly known by the name FACEBOOK and there are no White Pages or Yellow Pages listings for Callverse under this name. Since Callverse provided essentially no evidence for its contention that it had established a click to call service or had made considerable financial investment in business, there was no legitimate interest. The registration was in bad faith.

### Domain Names and IP

The DNS was never intended to give rise to any proprietary rights in the names which were registered under the system. As there are few limitations on who can register a domain name, particularly at the .com level, domain names are allocated on a "first come, first served" basis. (In Australia, eligibility and allocation criteria for .au 2LDs have always been more strict than for the gTLDs).

This causes potential problems, since domain names are an important asset of any business with an internet presence. They may not be intellectual property, but they can be very valuable. A domain name is a contractual right, held under licence from the Registrar.

In April 2001, a US Federal Court awarded $US65 million to the owners of the domain name sex.com: _Kremen v Cohen_. The defendant fraudulently obtained the domain name by means of a forged letter to the domain name Registrar and had illegally operated the site from 1995 onwards. The award comprised an estimate of the illegal profits earned by the defendant as well as damages incurred by the owners.

Domain names are generally not treated as IP but there are exceptions:

* //Hoath v Connect Internet Services// (2006) 229 ALR 566 (see p 369 – course book) – obiter – assumed that domain name was a form of property
* US – //the Anticybersquatting Consumer Protection Act 1999// – domain names treated as a form of intangible property in order to establish in rem jurisdiction
* //Network Solutions Inc v Umbro International Inc// 259 Va 759 at 770 domain name was a contract for services rather than property
* //Kremen v Cohen// F 3d 1024 – action for conversion where the underlying property was a domain name – Court held that domain names are a form of intangible property that can support a claim of conversion

## Trade Marks

Australian trade marks are usually protected through registration under the Commonwealth _Trade Marks Act_ 1995 (Cth). It has become increasingly common for businesses to register domain names as trademarks, in order to gain more protection for them. Trade marks ("TM"), generally speaking, are those ''signs'' (traditionally, names, words and logos) that businesses use to identify themselves and the goods and services they provide. Because of the vital commercial role that trade marks play, no business enterprise can function without TMs. A TM is a sign used in trade or commerce to indicate source of goods or services, and distinguish them from those of other traders. TMs are extremely important for businesses as they are an essential part of branding of goods and services. TMs can be a very valuable commercial asset (e.g. Coca Cola, Microsoft).

In Australia, TMs can be either registered or unregistered (common law); registration is not compulsory for protection of business reputation. However, registration confers considerable advantages, so should be done where possible. In particular, registered trade marks are easier and cheaper to enforce. Obtaining a trade mark registration under the //Trade Marks Act 1995// (Cth) may be seen as taking out a form of insurance. If registered owners of trade marks consider that their TMs have been infringed, they have a comparatively cheap and expeditious way of taking action against the infringer. In many cases, a letter of demand to the infringer providing details of the owner's registration will enable the matter to be settled out of court.

TMs are registered in respect to particular classes of goods and services. Generally, a TM can only be registered in relation to the particular types of goods or services it is used in relation to. If a TM is registered in classes in which the goods or services are not sold, the TM is vulnerable to cancellation. Thus, the TM system cannot be used to secure rights in a name against all other uses of that name.

The registration of business, company, or domain names does not confer property rights or rights to use the name as a TM. It is a common misconception that a company name or registered business or domain name gives exclusive rights to the name, and that it is not possible for anyone else to adopt a similar name.

Company names and registered business names are often permitted to co-exist. This is because, unlike the registered TM system, the systems of registering company and business names are not intended to give exclusivity over names. The position in relation to domain names is similar, though the registration procedure will provide additional security. It follows that the best way of securing exclusive rights to a company or business name or domain name is through registration of the name as a trade mark.

### Trade Mark Infringement

A trade mark is infringed under s 120(1) of the //Trade Marks Act 1995// (Cth)by another person's use of the name  if:
  * The sign used by the potential infringer is substantially identical with or deceptively similar to the trade mark;
  * The sign is used in relation to the same or similar goods or services; and
  * The sign is used as a trade mark.

Trade mark infringement is problematic online, especially due to territorial problems. There is potential that the same trade mark can be owned by different companies in different jurisdictions - with no intention of either owner trading off each other's reputation. This means that the rights of a trade mark owner in one jurisdiction may be infringed by an overseas website being accessible within the jurisdiction.

In //Ward Group Pty Ltd v Brodie & Stone Plc// [2005] FCA 471, the Federal Court held that for an overseas website to constitute trade mark infringement in Australia, the website must specifically target users located in Australia. THe World Intellectual Property Organisation ("WIPO") similarly recommended that a trade mark cannot be seen to have commercial effect in a particular jurisdiction unless the website that uses that trade mark is targeted at that place.

Issues also arise in online trade mark infringement cases, as some websites may not be engaging in trade or commerce at all, or may be selling goods and services different to those claimed within the registration. If this occurs, trade mark infringement proceedings will not be successful.

## Domain Names and Trade Marks in Australia

**Robert Tranent Explains [Cybersquatting and Applicable Remedies Under the auDRP](https://www.youtube.com/watch?v=YHcpQpF2LVc)**

In Australia the mere registration of a domain name does not constitute use (and therefore infringement) of a trade mark. There are no reported Australian cases in which a domain name has been held to have infringed a registered trade mark under s 120 of the Trade Marks Act 1995. It is at least theoretically possible for a .au domain name to infringe a registered trade mark((see CSR Ltd v Resource Capital Australia Pty Ltd [2003] FCA 279)). The Advisory Council on Intellectual Property (ACIP) commented in its 2004 issues paper, //A review of the relationship between trade marks and business names, company names and domain names //

>"Registered trade mark infringement may occur where a domain name is registered in good faith, where the words in the domain name are identical with, substantially identical with or deceptively similar to a registered trade mark, and where the domain name is connected with a website concerned with trading in the same goods or services, or goods or services of the same description as those in relation to which the trade mark is registered."

To establish trade mark infringement, the Trade Marks Act requires that a defendant has used a mark as a trade mark – this is difficult to establish in relation to the mere registration of a domain name.

In //CSR Limited v Resource Capital Australia Pty Ltd// (2003) 128 FCR 408 RCA, a cybersquatter, registered csrsugar.com and csrsugar.com.au and offered to sell them to CSR. RCA did nothing with the domain names except to offer this sale. Hill J observed that:

>“for the purposes of s 120 of the Trade Marks Act 1995 (Cth) … RCA or Mr Boland at no time used or intended to use the domain names as trade marks in relation to either goods or services”

Three Federal Court decisions shed some light on when use of a domain name constitutes use of that name as a trade mark.

### Buchanan Group Pty Ltd v Sorgetti [2002] FCA 1646

The applicants owned the registered TM "BRAND POWER". The respondents obtained the domain name 'brandpower.com' and developed a website at that address. Heery J did not reach a conclusion, but expressed the view that it was at least arguable that the respondents have infringed the applicant's TM and issued an interlocutory injunction restraining the use of the words "BRAND POWER" in the course of trade and the domain name 'brandpower.com'.

### Sports Warehouse, Inc v Fry Consulting Pty Ltd [2010] FCA 664 (Sports Warehouse)

Sports Warehouse (SW) was a retailer of tennis apparel and gear. Since 1995, it marketed its goods via 'www.tennis-warehouse.com'. In 2005, it filed for an Australian trade mark TENNIS WAREHOUSE in respect of class 35 (online retail services featuring tennis clothes etc.).  The trade mark application was opposed by Fry Consulting, who were selling similar products at 'www.tenniswarehouse.com.au'. Fry was successful in opposing the trade mark application as its website had commenced in Australia after SW's.

The appeal turned on whether SW had used the mark TENNIS WAREHOUSE to a sufficient extent to establish that the mark was capable of distinguishing online retailing services at the filing date. The court held that the words were not capable of distinguishing the goods and services, and evidence of use between 1998 and 2002 didn't lead to sufficient capability to distinguish.

The court relied on the decision in Architects (Aust) Pty Ltd t/a Architects Australia v Witty Consultants Pty Ltd [2002] QSC 139 which held that the domain name 'www.architectsaustralia.com.au' was substantially identical to the mark ARCHITECTS AUSTRALIA. Taking this decision into account, Kenny J observed that
>“in the context of online services, the public is likely to understand a domain name consisting of a trade mark… as a sign for the online services identified by the trade mark as available at the webpage to which it carries the Internet user”

The court concluded that the use of the domain name 'www.tennis-warehouse.com' constituted use of the mark TENNIS WAREHOUSE with additions or alterations that did not substantially affect the identity of the mark.

### Mantra Group Pty Ltd v Tailly Pty Ltd (No 2) ("Mantra")

Mantra was the exclusive on-site letting agent of about a third of the apartments in a residential apartment complex called, CIRCLE ON CAVILL, located at Surfers Paradise. Mantra owned three registered TMs incorporating the words, CIRCLE ON CAVILL, covering various property management and accomodation services.

Tailly was the off-site letting agent for approximately 39 apartments in the CIRCLE ON CAVILL complex. Tailly used the words CIRCLE ON CAVILL in 10 domain names and websites. Tailly also used the words CIRCLE ON CAVILL as metatags in its websites' source code. Tailly achieved rankings for its websites as high as number 4. Mantra alleged that Tailly had infringed the CIRCLE ON CAVILL trade marks and had engaged in misleading and deceptive conduct.

Tailly argued that CIRCLE ON CAVILL described the location and the name of the apartment complex, not the origin on Mantra's goods and services. Further, it argued that the words CIRCLE ON CAVILL were used in good faith to indicate the geographical origin of its accomodation (a defence to infringement (sub-section 122 (1)(b)(i) Trade Marks Act)).

Reeves J rejected both of Tailly's arguments.  Although Tailly’s websites did contain descriptive uses of the words CIRCLE ON CAVILL, the court held "this descriptive use pales into insignificance” when compared to the use Tailly made of those words to denote Tailly as the origin of the off-site letting services. The phrase "geographic origin… of… services" in the TMA refers to the name of a country, region, city, town, and not to a privately-owned building.

Good faith was not made out because the words CIRCLE ON CAVILL had been used over 250 times as metatages in the source code for each website, and the words were used repeatedly on the websites for search engine optimisation purposes.

Tailly was ordered to transfer to Mantra registration of the domain names incorporating the CIRCLE ON CAVILL words. Futher, an injunction was ordered restraining Tailly from using CIRCLE ON CAVILL or similar words as trade marks. Finally, Tailly was ordered to pay Mantra its profits derived from bookings sourced via the infringing websites.

### Summary of Case Law

The mere registration of a domain name does not constitute use of a sign as a trade mark (but may still constitute passing off at common law or misleading or deceptive conduct). A domain name may be used as a trade mark when it can be shown to be a sign used in trade to distinguish goods and/or services from those of other traders in addition to operating to indicate the location of a website. Under the Trade Marks Act it is not permissible to use another's registered trade mark as part of a domain name if the domain name links to a website which uses the registered mark to advertise or market goods or services in respect of which the trade mark is registered.

Including another's trade marks excessively in metatags on a website – you may have difficulty relying on good faith defence under the Trade Marks Act. Court can order injunction to restrain the use of domain names, metatags and search engine keywords that contain registered trade marks and the transfer of the domain name, an award of legal costs and damages or an account of profits.

"www.", ".com" or hyphens within a domain name do not substantially affect the identity of the trade mark contained in the domain name.

## Australian Consumer Law contraventions and Passing Off

In several decisions, the use of domain names has been held to contravene ss 52 (misleading and deceptive conduct) and/or 53 (misrepresentations of the //Trade Practices Act 1974// (Cth) ("TPA")  - now ss 18 and 29 of the Australian Consumer Law (//Competition and Consumer Act 2010// (Cth) Schedule 2) respectively). In these cases, courts have made orders requiring all necessary steps to be taken to transfer, cancel or de-register the disputed domain name.

* //Macquarie Bank Ltd v Seagle// [2008] FCA 1417 – registrant breached TPA s 52 in registering domain names related to Macquarie Bank  in .com, .net and .us domains

* //The Architects (Australia) Pty Ltd v Witty Consultants// [2002] QSC 139 – Witty registered the website 'architectsaustralia.com.au' and extensively advertised it. AA succeeded in action for misleading and deceptive conduct.

* //CSR Ltd v Resource Capital Australia Pty Ltd// [2003] FCA 279 – RCA (cybersquatter) registered 'csrsugar.com' and 'csrsugar.com.au', amounting to misleading and decptive conduct

* //Kailash Center for Personal Development Inc v Yoga Magik Pty Ltd// [2003] FCA 536 - the use of “mumford” in yoga web site metatags.

* //Mark Foys Pty Ltd v TVSN (Pacific) Ltd// [2000] FCA 1626 - Markfoys.com.au

* //Sydney Markets Limited v Sydney Flower Market Pty Ltd// [2002] FCA 124 - sydneyflowermarket.com.au (respondent), sydneyflowermarket.com, sydneyflowermarket.net and sydneyflowermarket.net.au (applicant)

Prior to 1999, there was no specific dispute resolution mechanism for disputes involving TLDs (2002 for .au 2LDs). Instead, dispute resolution required court action for infringement of a registered trade mark, contravention of the TPA or passing off.
