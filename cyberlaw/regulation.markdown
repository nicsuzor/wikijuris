---
layout: default
title: How is the Internet Regulated?
nav_order: 10
has_children: true
parent: Governing the Internet
---

[Edit this page](https://github.com/nicsuzor/wikijuris/blob/master/cyberlaw/regulation.markdown){: .btn .btn-outline }
This Chapter provides an overview of how the internet and its users are regulable. It starts by explaining how the internet technically operates, including the different layers of the internet, and how the internet is a decentralised network of networks. The Chapter then explains how early internet enthusiasts, like John Perry Barlow, heralded the internet as a new frontier free from regulation. However, Lawrence Lessig challenged this idealised conception of the internet by pointing out that "code is law "[^AUTOREPLACEDLawrenceLessigCode202006pp12126httpcodev2ccdownloadremixLessigCodev2pdfAUTOREPLACED], or that the rules of software can be as powerful as the laws of nation states that regulate the behaviour of citizens. This Chapter concludes by outlining some the challenges of enforcing law in the decentralised online environment, some of which we will explore in later Chapters.

[^AUTOREPLACEDLawrenceLessigCode202006pp12126httpcodev2ccdownloadremixLessigCodev2pdfAUTOREPLACED]: Lawrence Lessig, Code 2.0 (2006), pp 121–26 http://codev2.cc/download+remix/Lessig-Codev2.pdf


# Different Ways of Understanding the Layers of the Internet
{: .no_toc }

1. Table of Contents
{:toc}

**Video Overview by Nic Suzor:[Code, infrastructure, and content: layers of the Internet](https://www.youtube.com/watch?v=mqhXMmQOOXU)**

In order to understand how the internet operates, and how regulation can operate in this context, it is important to understand the different layers of the internet. Network engineers generally conceptualise up to seven layers of the internet and distinguish between the physical pipes, network infrastructure and other components of the network. However, for the purposes of this unit, we will conceptualise the internet in terms of three main layers: infrastructure, code and content.  

The first layer of the internet is the 'infrastructure' layer (network cables, routers and protocols). This layer is designed around the principle of a 'neutral' network (['end-to-end' principle](https://en.wikipedia.org/wiki/End-to-end_principle)): the responsibility for determining the content of communications rests with smart servers and users at the ends of the network, and the intermediaries are only responsible for passing messages along the chain. Intermediaries are not expected to examine or interfere with content, in any substantive way, as it passes through their networks. The design principle that intermediaries are merely conduits for passing messages enables innovation at the infrastructure level. As the network itself is open, there is a real separation between the infrastructure (the pipes) and content (the data that flows over those pipes), which means that anyone is free to 'plug-in' to the internet and start providing services over the IP protocol and the hardware that connects all users together. Service providers can design new systems that can operate on top of standardised protocols.

The second layer can be thought of as the 'code' layer - that is, the software that operates at the ends of the network to interact with users. The webserver that sends users the webpages that they requeste, which is customised and tailored for that particular user, is an example of a software program running on a server or farm of servers. The applications ('apps') that connect people to others, that allow users to chat, like, comment on and swipe content created by others, are pieces of software running on mobile devices and personal computers that communicate with software running on the servers somewhere in 'the cloud'. These programs, including their design, the input they accept, the algorithms they use to respond to requests, are responsible for determining who we can communicate with and how.

The third layer of the internet is content, or the material that is transmitted over the network infrastructure, selected and presented by code. For many of us, the information that users express and receive over the internet and the visible components of its networks are some of the first things that come to mind when we think of "the internet". The history of internet regulation is mostly a history of attempts by various parties to regulate content, including offensive communications and pornography, private and confidential information, defamatory statements and copyright content. This is because governments and private actors often have reasons to want to limit the flow of certain information online. Increasingly, however, attempts to regulate content involve struggles at the code and infrastructure layers as pressure mounts on those who provide network infrastructure or services to build certain rules into their systems. The most prominent struggles over internet governance are principally concerned with who gets to decide how networks are structured and how code operates.

## Infrastructure: The Internet Is a Series of Tubes

**Video Overview by Nic Suzor:[Internet Infrastructure](https://www.youtube.com/watch?v=kwLTm1kJh3w)**

The resilience of the internet is often framed in John Gilmore's famous words: "The Net interprets censorship as damage and routes around it."[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED] To understand this claim, we have to understand some principles about how the internet technically works. As noted above, the internet is often defined as a network of networks. Wikipedia has [a useful definition](https://en.wikipedia.org/wiki/Internet):

[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED]: Philip Elmer-Dewitt, ‘First Nation in Cyberspace’ (1994) 49 TIME International http://www.chemie.fu-berlin.de/outerspace/internet-article.html.

>The Internet is a global system of interconnected computer networks that use the standard Internet protocol suite (TCP/IP) to link several billion devices worldwide. It is a network of networks that consists of millions of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies.

The Internet as we know it is built on [technologies funded by the US Department of Defence](https://en.wikipedia.org/wiki/DARPA), large public investments in infrastructure by academic and other institutions and, from the 1990s, large-scale private investments in the deployment of new commercial and private connections around the world. From its very beginnings, the internet was designed to be _resilient_. One of its key features is that it relies on an inter-connected web of computers to route information from any point to any other point on the internet. Take, for example, a user in Australia that sends a message via Facebook. Once that user writes a message on their home computer or mobile device, the message is then transmitted along an ISP's network a few times before hitting a major backbone or undersea cable. The message is then passed along the chain by several other networked routers before finally reaching its destination at a webserver in the United States (US). The process of sending a Facebook message could take anywhere from 10 to 20 different 'hops' along this chain. Facebook's webserver in the US will receive that request and send the content back to the user along a similar, but not necessarily the same, path.

The fact that content, including messages, can take any path between the two end points is a foremost reasons why the internet is hard to regulate. Internet infrastructure is designed to resist control and automatically re-route around problems, such as broken links, when and where they might occur. For instance, individual messages are broken down into much smaller 'packets', and the 'internet protocol' provides the standard for communication that enables all connected systems to talk to each other and pass data along the chain. This illustrates Gilmore's argument that,[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED] if a particular path is blocked or censored, the internet protocol allows computers to find alternative routes to send content to its destination.

[^AUTOREPLACEDPhilipElmerDewittFirstNationinCyberspace199449TIMEInternationalhttpwwwchemiefuberlindeouterspaceinternetarticlehtmlAUTOREPLACED]: Philip Elmer-Dewitt, ‘First Nation in Cyberspace’ (1994) 49 TIME International http://www.chemie.fu-berlin.de/outerspace/internet-article.html.


Some networks are easier to regulate than others. More decentralised networks, such as 'peer-to-peer' (P2P) file sharing technologies, are more difficult to regulate in part because of the sheer number of largely anonymous end-users who might be sharing content. As we will discuss in the Liability of Intermediaries chapter, parties alleging some kind of infringement often chose to due intermediaries, rather than end-users. Targeting an intermediary, such as an ISP, can be very effective because of the 'customer/server' nature of their networks (i.e. the ISP, or server, largely contractually agrees to provide internet access to end-users, or its customers).

One way of avoiding regulation online is through the use of a Virtual Private Network **[('VPN')](https://www.youtube.com/watch?v=prhQKAJG8nA)**. A VPN creates an encrypted 'tunnel' from an entry point in one jurisdiction to an exit point in another. By using a VPN, a user can appear to be located in another jurisdiction. This means a user can potentially avoid jurisdiction-based filtering or blocking, such as geo-blocking of online content, and attempt to better conceal their real location and other personal information.

<WRAP center round tip 60%>
Watch: **[Mitch Huges](https://www.youtube.com/watch?v=rk0aeKMCRFs)** explains how, before Netflix was available in Australia, many Australians used VPNs to access overseas Netflix content and ultimately bypass industry agreements that require geographic market segmentation of content.
</WRAP>
