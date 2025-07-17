---
layout: default
title: How is the Internet Regulated?
nav_order: 10
has_children: false
parent: Governing the Internet
---

[Edit this page](https://github.com/nicsuzor/wikijuris/blob/master/cyberlaw/regulation.markdown){: .btn .btn-outline }

# How is the Internet Regulated?
{: .no_toc }

1. Table of Contents
{:toc}


This Chapter provides an overview of how the internet and its users are regulable. It starts by explaining how the internet technically operates, including the different layers of the internet, and how the internet is a decentralised network of networks. The Chapter then explains how early internet enthusiasts, like John Perry Barlow, heralded the internet as a new frontier free from regulation. However, Lawrence Lessig challenged this idealised conception of the internet by pointing out that "code is law "[^AUTOREPLACEDLawrenceLessigCode202006pp12126httpcodev2ccdownloadremixLessigCodev2pdfAUTOREPLACED], or that the rules of software can be as powerful as the laws of nation states that regulate the behaviour of citizens. This Chapter concludes by outlining some the challenges of enforcing law in the decentralised online environment, some of which we will explore in later Chapters.

[^AUTOREPLACEDLawrenceLessigCode202006pp12126httpcodev2ccdownloadremixLessigCodev2pdfAUTOREPLACED]: Lawrence Lessig, Code 2.0 (2006), pp 121–26 http://codev2.cc/download+remix/Lessig-Codev2.pdf


# Different Ways of Understanding the Layers of the Internet


**Video Overview by Nic Suzor: [Code, infrastructure, and content: layers of the Internet](https://www.youtube.com/watch?v=mqhXMmQOOXU)**

In order to understand how the internet operates, and how regulation can operate in this context, it is important to understand the different layers of the internet. Network engineers generally conceptualise up to seven layers of the internet and distinguish between the physical pipes, network infrastructure and other components of the network. However, for the purposes of this unit, we will conceptualise the internet in terms of three main layers: infrastructure, code and content.  

The first layer of the internet is the 'infrastructure' layer (network cables, routers and protocols). This layer is designed around the principle of a 'neutral' network (['end-to-end' principle](https://en.wikipedia.org/wiki/End-to-end_principle)): the responsibility for determining the content of communications rests with smart servers and users at the ends of the network, and the intermediaries are only responsible for passing messages along the chain. Intermediaries are not expected to examine or interfere with content, in any substantive way, as it passes through their networks. The design principle that intermediaries are merely conduits for passing messages enables innovation at the infrastructure level. As the network itself is open, there is a real separation between the infrastructure (the pipes) and content (the data that flows over those pipes), which means that anyone is free to 'plug-in' to the internet and start providing services over the IP protocol and the hardware that connects all users together. Service providers can design new systems that can operate on top of standardised protocols.

The second layer can be thought of as the 'code' layer - that is, the software that operates at the ends of the network to interact with users. The webserver that sends users the webpages that they requeste, which is customised and tailored for that particular user, is an example of a software program running on a server or farm of servers. The applications ('apps') that connect people to others, that allow users to chat, like, comment on and swipe content created by others, are pieces of software running on mobile devices and personal computers that communicate with software running on the servers somewhere in 'the cloud'. These programs, including their design, the input they accept, the algorithms they use to respond to requests, are responsible for determining who we can communicate with and how.

The third layer of the internet is content, or the material that is transmitted over the network infrastructure, selected and presented by code. For many of us, the information that users express and receive over the internet and the visible components of its networks are some of the first things that come to mind when we think of "the internet". The history of internet regulation is mostly a history of attempts by various parties to regulate content, including offensive communications and pornography, private and confidential information, defamatory statements and copyright content. This is because governments and private actors often have reasons to want to limit the flow of certain information online. Increasingly, however, attempts to regulate content involve struggles at the code and infrastructure layers as pressure mounts on those who provide network infrastructure or services to build certain rules into their systems. The most prominent struggles over internet governance are principally concerned with who gets to decide how networks are structured and how code operates.

# Infrastructure: The Internet Is a Series of Tubes

**Video Overview by Nic Suzor: [Internet Infrastructure](https://www.youtube.com/watch?v=kwLTm1kJh3w)**

The resilience of the internet is often framed in John Gilmore's famous words: "The Net interprets censorship as damage and routes around it."[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED] To understand this claim, we have to understand some principles about how the internet technically works. As noted above, the internet is often defined as a network of networks. Wikipedia has [a useful definition](https://en.wikipedia.org/wiki/Internet):

[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED]: Philip Elmer-Dewitt, ‘First Nation in Cyberspace’ (1994) 49 TIME International http://www.chemie.fu-berlin.de/outerspace/internet-article.html.

>The Internet is a global system of interconnected computer networks that use the standard Internet protocol suite (TCP/IP) to link several billion devices worldwide. It is a network of networks that consists of millions of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies.

The Internet as we know it is built on [technologies funded by the US Department of Defence](https://en.wikipedia.org/wiki/DARPA), large public investments in infrastructure by academic and other institutions and, from the 1990s, large-scale private investments in the deployment of new commercial and private connections around the world. From its very beginnings, the internet was designed to be _resilient_. One of its key features is that it relies on an inter-connected web of computers to route information from any point to any other point on the internet. Take, for example, a user in Australia that sends a message via Facebook. Once that user writes a message on their home computer or mobile device, the message is then transmitted along an ISP's network a few times before hitting a major backbone or undersea cable. The message is then passed along the chain by several other networked routers before finally reaching its destination at a webserver in the United States (US). The process of sending a Facebook message could take anywhere from 10 to 20 different 'hops' along this chain. Facebook's webserver in the US will receive that request and send the content back to the user along a similar, but not necessarily the same, path.

The fact that content, including messages, can take any path between the two end points is a foremost reasons why the internet is hard to regulate. Internet infrastructure is designed to resist control and automatically re-route around problems, such as broken links, when and where they might occur. For instance, individual messages are broken down into much smaller 'packets', and the 'internet protocol' provides the standard for communication that enables all connected systems to talk to each other and pass data along the chain. This illustrates Gilmore's argument that,[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED] if a particular path is blocked or censored, the internet protocol allows computers to find alternative routes to send content to its destination.

[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED]: Philip Elmer-Dewitt, ‘First Nation in Cyberspace’ (1994) 49 TIME International http://www.chemie.fu-berlin.de/outerspace/internet-article.html.


Some networks are easier to regulate than others. More decentralised networks, such as 'peer-to-peer' (P2P) file sharing technologies, are more difficult to regulate in part because of the sheer number of largely anonymous end-users who might be sharing content. As we will discuss in the Liability of Intermediaries chapter, parties alleging some kind of infringement often chose to sue intermediaries, rather than end-users. Targeting an intermediary, such as an ISP, can be very effective because of the 'customer/server' nature of their networks (i.e. the ISP, or server, largely contractually agrees to provide internet access to end-users, or its customers).

One way of avoiding regulation online is through the use of a Virtual Private Network **[('VPN')](https://www.youtube.com/watch?v=prhQKAJG8nA)**. A VPN creates an encrypted 'tunnel' from an entry point in one jurisdiction to an exit point in another. By using a VPN, a user can appear to be located in another jurisdiction. This means a user can potentially avoid jurisdiction-based filtering or blocking, such as geo-blocking of online content, and attempt to better conceal their real location and other personal information.


Watch: **[Mitch Huges](https://www.youtube.com/watch?v=rk0aeKMCRFs)** explains how, before Netflix was available in Australia, many Australians used VPNs to access overseas Netflix content and ultimately bypass industry agreements that require geographic market segmentation of content.




# The Dawn of the Internet: A Declaration of the Independence of Cyberspace

In 1996, John Perry Barlow released a famous provocation about the limits of state power in regulating the internet. The Declaration, which we encourage you to **[read](https://projects.eff.org/~barlow/Declaration-Final.html)** or **[watch](https://www.youtube.com/watch?v=3WS9DhSIWR0)** in full, begins:

>Governments of the Industrial World, you weary giants of flesh and steel, I come from Cyberspace, the new home of Mind. On behalf of the future, I ask you of the past to leave us alone. You are not welcome among us. You have no sovereignty where we gather.
>... I declare the global social space we are building to be naturally independent of the tyrannies you seek to impose on us. You have no moral right to rule us nor do you possess any methods of enforcement we have true reason to fear.

Barlow's Declaration has played an pivotal role in shaping how we think about online regulation. In this extract, he makes two main claims about online regulation, which we will examine in more detail below. The first is that the internet is inherently unregulable by territorial governments. The second is that state regulation of the internet is illegitimate, or governments should defer to the self-rule of cyberspace.

## Barlow's First Claim: The Internet is Unregulable

**Overview by Nic Suzor: [Governing the Internet](https://www.youtube.com/watch?v=ybNGDquKVTc)**

>"You have no moral right to rule us nor do you possess any methods of enforcement we have true reason to fear."

Barlow's first claim that territorial states do not have the power to regulate the internet is largely descriptive. This claim is based on a number of factors, including the decentralised nature of the internet, which is a network of networks that spans the globe without any real concern for jurisdictional boundaries. The internet enables billions of people to communicate largely anonymously across the globe, and the sheer quantity of content that is transmitted over the network each day is almost incomprehensibly large. All of these factors mean that, for the most part, any explicit interventions by governments can be trivially circumvented. If a website is shut down in one jurisdiction, it can be back up the next day somewhere else in the world. If a document is removed from one site, it will often quickly be reposted on a dozen more (see, for example, the '[streisand effect](https://en.wikipedia.org/wiki/Streisand_effect)').

However, it turns out that regulating the internet isn't quite impossible, just often very difficult. Fundamentally, the internet is not a separate place because the people who use it are real people, in real locations, subject to the very real power of their jurisdictions. The pipes that people use to communicate are cables and wireless links which also have physical presence. Where a Government can target the speakers, recipients or intermediaries involved in a communication, it can have a real effect on what information is transmitted via the internet. Figure 1 below, for example, illustrates the network traffic in Egypt over the period of the January 2011 revolution. You can clearly see the point at which the Egyptian Government had shut down the five major Egyptian internet service providers. Control over internet infrastructure is extremely powerful.

The challenge of regulating the internet is finding an effective way to either identify and regulate the potentially anonymous creators of information, the billions of potential recipients, or finding a way to regulate the networks along the chain of communication.

**Figure 1: Who Controls the Pipes, Controls the Universe - Traffic to and from Egypt on 27-28 January 2011, from Arbor Networks**

![Graph of traffic to and from Egypt on January 27-28 2011, from Arbor Networks - Who Controls the Pipes, Controls the Universe](http://www.wired.com/images_blogs/threatlevel/2011/01/arbor_egypt-660x359.jpg)
(Image (c) Arbor Networks via [Wired](http://www.wired.com/2011/01/egypt-isp-shutdown/))

### A Case Study: Newzbin

**[Overview of Newzbin by Nic Suzor](https://www.youtube.com/watch?v=z8Ph8eO26q4)**

While the internet is not unregulable, there are unique challenges facing regulators. The case of Newzbin, which was a popular Usenet indexing site, is one example from the fight against copyright infringement. Dubbed 'the Google of usenet' by the Motion Picture Association of America (MPAA), copyright owner groups sought to shut down the service that allowed others to easily find copyright films and other works. In a 2010 Decision, the High Court in the United Kingdom (UK) found Newzbin liable for copyright infringement, and the company was wound up and their website shut down.[^AUTOREPLACEDTwentiethCenturyFoxFilmCorporationvNewzbinLimited2010EWHC608ChhttpwwwbailiiorgewcasesEWHCCh2010608htmlAUTOREPLACED]


[^AUTOREPLACEDTwentiethCenturyFoxFilmCorporationvNewzbinLimited2010EWHC608ChhttpwwwbailiiorgewcasesEWHCCh2010608htmlAUTOREPLACED]: [Twentieth Century Fox Film Corporation v Newzbin Limited [2010] EWHC 608 (Ch)](http://www.bailii.org/ew/cases/EWHC/Ch/2010/608.html
Two weeks later, Newzbin2 rose from the ashes. Someone had copied the entire codebase of the old site and brought it back online on a server in the Seychelles, an archipelago of islands outside of UK jurisdiction. The MPAA went back to court, this time seeking an injunction that would require UK-based ISPs to block access to the website. The Court granted this order, marking an expansion of laws that were originally designed to block websites that hosted child sexual abuse material: [Twentieth Century Fox Film Corporation v British Telecommunications PLC](http://www.bailii.org/ew/cases/EWHC/Ch/2011/1981.html) [2011] EWHC 1981 (Ch).

The system for blocking websites is not wholly effective. It turned out to be easy to bypass if users encrypted their connections or used a virtual private network to avoid the block. Shortly after the injunction, Newzbin2 released a user-friendly application to 'utterly defeat' the filter, [explaining that its app](http://torrentfreak.com/newzbin2-release-encrypted-client-to-defeat-website-blocking-110914/) could "break any updated web censorship methods or anti-freedom countermeasures". Ultimately, however, Newzbin2 closed down in 2012. It had lost the trust of its users, who were not sufficiently willing to pay to support the new service. Importantly, copyright owners had also started to target the payment intermediaries that channeled funds to the organisation - intermediaries like Mastercard, Visa, Paypal, and smaller payment processors that use these networks.

The Newzbin case study illustrates how regulating online content and behaviour can be an extremely difficult task. By cutting off the flow of money, the rightsholder groups were eventually successful in shutting down Newzbin. However, this took a lot of time and effort, and there is a good chance that many users of the service simply moved to newer, better hidden infringement networks. Overall, the copyright industry has had some succes in tackling large copyright infringers, but this is an ongoing arms race, as infringers continue to find ways around the regulations.

## Barlow's Second Claim: State Regulation of the Internet is Illegitimate

**Overview by Nic Suzor [The Legitimacy of Online Regulation](https://www.youtube.com/watch?v=A0m_GZC4x2w)**

The second claim that Barlow makes in his Declaration is that state governments _should_ defer to cyberspace self-rule, or what we call 'private ordering'. Barlow explains that:

>"We believe that from ethics, enlightened self-interest, and the commonweal, our governance will emerge."

Barlow's argument is that the rules and social norms created by online communities to govern themselves will be better than anything imposed by territorial states. This was expressed by Johnson and Post in a famous 1995 article as a general principle that there is “no geographically localized set of constituents with a strong and more legitimate claim to regulate [online activities]” than the members of the communities themselves.[^johsonpost1375] In addition to arguing that online communities should be able to govern for themselves, Barlow and Johnson and Post asserted that if territorial governments try to impose their own laws on a borderless internet, users will never be able to work out what set of rules they are subject to. The consequence of governments attempting to prevent online communities from regulating themselves, according to Post, would be:


> “... the chaotic nonsense of Jurisdictional Whack-a-Mole".[^johsonpost913]

[^johsonpost1375]: David Johnson and David Post, ‘Law and Borders--The Rise of Law in Cyberspace’ (1995) 48 Stanford Law Review 1367, 1375

[^johnsonpost913]: Post, 'Governing Cyberspace: Law' (2008) http://www.academia.edu/2720975/Governing_Cyberspace_Law


As we will see in the [Jurisdiction chapter](jurisdiction), the legitimacy of any one nation claiming jurisdiction over transnational communications is still a vexed issue. As the Australian High Court noted in the _Dow Jones v Gutnick_[^gutnick] case, nation states purport to have a responsibility to protect their citizens' interests online, and certainly a desire to regulate online content and behaviour.

[^gutnick]: _Dow Jones and Company Inc v Gutnick_ [2002] HCA 56 http://www.austlii.edu.au/cgi-bin/sinodisp/au/cases/cth/HCA/2002/56.html?stem=0&synonyms=0&query=title(dow%20jones%20and%20gutnick%20)&nocontext=1

# Lessig's Modalities of Regulation: Law, Architecture, Norms and the Market

**Video Overviews by Nic Suzor: [Code is Law](https://www.youtube.com/watch?v=d__FV81ccz0)** and **[Different Types of Regulation](https://www.youtube.com/watch?v=0Bwu5YO_1FI)**

As law students, we are familiar with thinking of regulation primarily as law. The law generally threatens those who misbehave, or fail to abide by legal rules, with punishment. As Grimmelmann explains, the law 'encourages individuals to choose the "right" course of action by associating sufficient sanctions with the "wrong" one to make it comparatively unattractive".[^grimm] We have different bodies of law, causes of action and remedies for resolving disputes between "right" and "wrong" courses of action. The law, however, is not the only form of regulation in everyday life. In his famous book, **[Code, and Other Laws of Cyberspace](https://harvardmagazine.com/2000/01/code-is-law-html)**, Lawrence Lessig explains that there are four key **["modalities of regulation"](https://www.youtube.com/watch?v=EXOv1doHp88)** that attempt to limit or restrain people's behaviour. These modalities are **(1) law, (2) architecture, (3) norms and (4) the market.**

It is useful here to explain Lessig's conception of the other modalities of regulation. First, architecture refers to physical reality, or "the human built environment".[^grimm] Speed humps are an everyday example of regulation as physical architecture. Speed humps have speed control elements that, in conjunction with drivers taking note of warning signs, attempt to reduce the speed of a vehicle in line with target speed limits. Architects and town planners, among others, regularly design and deploy a wide variety of physical restraints, like speed humps, in line with regulatory agendas. Second, even in the absence of black letter law, social norms constrain some forms of behaviour. Take, for instance, norms of everyday conduct that many of us are socially conditioned to adhere to: 'Don't talk to strangers', 'follow instructions given by authority figures', 'respect your elders' and so forth. Norms are informal yet pervasive codes of conduct. Finally, the marketplace can regulate behaviour by putting a price tag on certain behaviours. Examples of market-based regulation include raising the price to petrol to combat speeding, pollution permits for certain industries, and accreditation, licensing and membership certifications. The market can efficiently regulate some scare resources and, like architecture and norms, improve regulation carried out my laws.  


[^grimm]: James Grimmelmann, 'Regulation by Software' (2005) 1725 https://www.yalelawjournal.org/pdf/209_jbwrex6h.pdf


## Code is Law

Shortly after early cyber-libertarians like Barlow declared the internet to be free from regulation, Lawrence Lessig's famous phrase "code is law" fundamentally changed debates about internet governance and regulation.[^code] Lessig argues that code is a form of physical architecture that can control online communication, or behaviours, just as effectively as the legal rules of nation states. The hidden ways in which code regulates online behaviours often goes unnoticed, but in every piece of software, in every algorithm, there are hidden assumptions about how the world works or should work. Sometimes this is accidental - for example, many websites are inaccessible to people with print disabilities because they are not designed with this user group in mind. It takes a lot of vigilance to ensure that technologies are developed in a way that does not unintentionally exclude or limit the access of certain groups of people. Other times, though, code acts in a much more sinister way. We have no real understanding of the algorithms that Facebook or Google use to determine which content is visible to us. The news items that popup in our feeds, or the results of our searches, are all determined according to a set of algorithms that are ultimately designed to further the interests of private corporations. These are powerful algorithms -- powerful mechanisms of regulation that we really do not understand, and certainly do not know whether or how we should regulate their design or use.

[^code]: Lawrence Lessig, Code 2.0 (2006), pp 121–26 http://codev2.cc/download+remix/Lessig-Codev2.pdf



Lessig outlines how code, the physical architecture of the internet, as well as the other modalities of regulation work together in the online environment. For example:

  * **Law:** Laws such as copyright, defamation and obscenity threaten ex-post sanction for violation of legal rights;
  * **Architecture:** Software and hardware that make cyberspace what it is constrain how you can behave online, by requiring passwords, producing traces that link transactions to you, encryption and code;
  * **Norms:** What users can say on particular websites is influenced by the nature of that site; and
  * **Markets:** Price structures or busy signals constrain access, areas of the web charge for access, advertisers reward popular sites, online services drop low-population forums.

We can apply these four modalities to different regulatory issues about internet content. Imagine, for instance, that we are concerned about the amount of offensive content on the web. We could create a law against offensive material, but it would be really hard to enforce. In fact, we already have several such laws, including common law obscenity offences as well as a content classification scheme that allows people to make complaints about content online. These laws, however, are all practically useless where content is hosted in foreign jurisdictions. Lessig's other modalities of regulation offer other potential solutions:

 * A code-based approach to regulating offensive content might be to introduce mandatory filtering at the ISP level;

 * A market-based approach might include subsidising voluntary filters that parents can install on their home internet connections; or

 * We might investigate how to develop social norms around acceptable behaviour. This might be a bit harder to articulate, but we see this happening a lot in our society. Imagine the moral outrage, in all of the papers, including outraged quotes from the Prime Minister's office when someone defaces a memorial page on Facebook. This is the work that creates a shared social norm about what content or behaviour is permissible and what is not.

Importantly, Lessig's modalities are never really independent, as they all interact in interested ways. In the context of offensive online content, social media platforms like Facebook, YouTube, and Twitter are modifying their code to allow people to report or flag offensive content, and the market is starting to **[respond](http://fortune.com/2018/04/07/social-media-content-restrictions/)** to concerns about offensive content. This market-based initiative, noting that platforms, like Facebook, are private corporations, leverages code and social norms to regulate the massive amounts of material that are posted to these networks every day.

## Case Study: YouTube's ContentID System

Copyright infringement is another example of the interplay between the different modalities of regulation. In the late 1990s, the copyright industries' answer to the problem P2P file sharing network Napster posed was to turn to the courts. The courts eventually held that Napster was liable for copyright infringement, and the service was shut down. When that did not stop filesharing, the industries turned to marketing to try to create strong social norms against copying -- **[you wouldn't steal a car, right?](https://www.youtube.com/watch?v=HmZm8vNHBSU)** Over the last decade, working with YouTube and others, rightsholders have been able to develop new technologies to detect potential copyright infringement and deal with it automatically. YouTube's ContentID, for example, automatically detects when a person uses copyright music in their video, and copyright owners are presented with an easy choice to block access to the video, remove the soundtrack, leave it alone, or run ads alongside it. This has been a massively important tool for rightsholders. Finally, there have been some market innovations over the last few decades as well. Eventually, iTunes emerged to satisfy some of the demand music fans had to be able to get access to digital downloads in a cheap and easy way. Spotify and now Apple Music have gone further - providing fans with all-you-can-eat subscription so that they can enjoy the abundance that Napster brought, legally.

If you define 'regulation' as a concerted effort to influence or control the way another person behaves, there are many different ways of achieving that goal. **Lessig's point is not that governments and state-based law do not matter in the internet age, rather that law is only one of the ways to regulate.** This means that when we are thinking about internet regulation, we need to be aware of the ways in which behaviour can be altered, and the limits of any given modality.

## Enforcing Law Online

**Overview Videos by Will McLay on [Online Anonymity](https://www.youtube.com/watch?v=CTZYP6jZS_U)** and **Rica Ehlers on [4chan](https://www.youtube.com/watch?v=OgYf932GFQo)**

There are a number of challenges to enforcing law on the internet. The first is the decentralised nature of the internet, in stark contrast to the traditional, centralised conception of government, enables users to communicate across jurisdictional boundaries.[^kerr] It is possible for users to redirect their online activities through any number of jurisdictions that might be remote, require inter-governmental cooperation, or lengthily and/or costly legal proceedings. The ability of users to communicate largely anonymously via the internet is another challenge for law enforcement. Anonymity makes it difficult for law enforcement agencies to do a number of things, including obtain personal information and identify a person's physical location, especially when a user might be using a VPN or other de-identifying software. The sheer quantity of content that users transmit over the web also creates practical challenges. It is immensely difficult for law enforcement agencies, and other societal actors like online platforms that are increasingly undertaking policy work at the behest of regulators,[^whyb] to effectively review and make determinations about every piece of content. These factors, among others, can raise complex legal questions about choice of law/applicable law, choice of forum, and the recognition of foreign judgments, which we will consider in my more detail in the following Chapter. Lessig's modalities of regulation provide a useful framework for us to attempt to identify and evaluate different solutions to regulatory problems, like law enforcement, in the digital age.  

[^kerr]: Note that this does not necessarily mean that the internet is borderless: See Orin S. Kerr 'Enforcing Law Online, Reviewed Work(s): Who Controls the Internet?: Illusions of a Borderless  World by Jack Goldsmith and Tim Wu (2007) https://www.jstor.org/stable/pdf/4495619.pdf



[^whyb]: Electronic Frontier Foundation, 'Who Has Your Back? Censorship Edition 2018 https://www.eff.org/who-has-your-back-2018



### Example: Cloudflare's decision to drop hosting for the Daily Stormer neo-Nazi site

**Overview video by Hazza: [The Downfall of the Daily Stormer](https://www.youtube.com/watch?v=vf-INXgNpwM)**

The neo-Nazi website, Daily Stormer, is a good example of how online content can be regulated by Internet intermediaries. Cloudflare, a content delivery network, provides many advantages to websites on their servers. One of Cloudflare's main selling points is its security capabilities against online attacks, especially against a Distributed Denial of Service attack. It is for this very reason that so many websites seek protection from the company, including the Daily Stormer, one of the largest neo-Nazi websites. After the administrators of the Daily Stormer made hateful comments regarding a woman's murder in the Charlottesville rally in 2017, Cloudflare terminated protection of the website after significant criticism from the public. It was a decision that Matthew Prince, Cloudflare’s CEO, struggled to make, being a firm believer in freedom of speech on the Internet. The tipping point for the decision was the team behind the website claiming that Cloudflare were secretly supporters of the site's hateful ideology, which was something the company could not stand for. The Daily Stormer has suffered dramatic losses in traffic and membership, and shows how Internet intermediaries can regulate online content, even if that regulation is only imperfect.


## Decentralised Networks and Internet Governance

The internet was initially decentralised to facilitate an equal and transparent interchange of information. However, recently there has been a concentration of power in the hands of a small number of large corporations. This raises concerns around accountability because centralised networks concentrate data ownership, meaning there is a greater chance of widespread data breaches and privacy violations. In response, decentralised networks are gaining popularity once more, highlighting new opportunities for regulation outside (or complementary to) the formal law.

### What is a Decentralised Network?

A decentralised network distributes information processing across multiple machines. Each computing device acts as a separate processor that interacts with all the other devices in the network. This contrasts with a centralised network, which is a single computer that handles all computing for a network. A decentralised structure enhances security, reduces the risk of systemic failures, and promotes transparency.

Computing devices today have significant computing power. Decentralised networks take advantage of this computing capability and pair it with networking technology that can help devices quickly interact with each other and coordinate activity. Some decentralised networks may still rely on a central computing infrastructure for things like data storage. However, a fully distributed and decentralised network has no singular computing unit controlling any process.

### Governance of Decentralised Networks

#### Decentralised Autonomous Organizations (DAOs)

DAOs are a prime example of decentralised governance. They use blockchain technology and smart contracts to automate decision-making processes, allowing for democratic participation without the need for a central authority. Members of a DAO can vote on proposals and changes, ensuring that governance is transparent and community-driven based in the geographical location. This enhances compliance with local laws.

#### Collaborative and Regulatory Decision-Making

In decentralised networks, decisions are made collaboratively by the network participants. This can involve voting mechanisms, consensus algorithms, or other methods that ensure that the voices of a wide variety of stakeholders are heard.

#### Modularity

Decentralised governance often involves modular structures, where different parts of the network can operate semi-independently by smaller groups or individuals. This allows for flexibility and adaptability in governance, and enhanced oversight.
