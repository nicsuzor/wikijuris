#### The Tor network

Tor — originally 'the onion router' — is one of the most widely used anonymity tools. It conceals a user's IP address by relaying traffic through a series of volunteer-run nodes, encrypting each hop so that no single relay can see both the original source and the destination.[^tor_asd] The network distinguishes several node types:

- the **guard node**, which is the point of entry into the network;
- **middle nodes**, which sit between the guard and exit nodes, and through which a message may pass more than once;
- the **exit node**, through which traffic passes before returning to the open internet; and
- **bridge nodes**, a form of guard node that is not publicly listed.

Development began in the mid-1990s at the United States Naval Research Laboratory, with the aim of protecting government communications. Restricting the network to government and law enforcement users would have defeated its purpose: if every connection originated from an official, the anonymity set would be trivially small. The network was opened to the public in 2002 for that reason.[^tor_davis] It is now maintained by the non-profit Tor Project, and is used both for anonymous browsing and for hosting anonymous services.[^tor_moore]

##### Tor and Australian law

Tor engages Australian privacy and surveillance law in a number of ways. APP 2 provides that individuals must have the option of dealing with an APP entity anonymously or under a pseudonym, where lawful and practicable.[^tor_app2] APP 11.2 requires entities to take reasonable steps to destroy or de-identify personal information that is no longer needed.[^tor_app11]

Those principles sit alongside obligations that run the other way. Part 5-1A of the _Telecommunications (Interception and Access) Act 1979_ (Cth) requires carriers and carriage service providers to retain specified telecommunications data for two years.[^tor_retention] The _Telecommunications and Other Legislation Amendment (Assistance and Access) Act 2018_ (Cth) empowers agencies to issue technical assistance and technical capability notices to communications providers, a scheme discussed at [Law enforcement powers](#law-enforcement-powers) above.[^tor_tola] Tools such as Tor operate outside these schemes: they shift control over identification back to the user, which is the source of both their value to at-risk users and their attractiveness to offenders.

As at the time of writing, there is no Australian legislation prohibiting the use of anonymity tools such as Tor. Some jurisdictions, including China and Russia, have taken steps to block access to the network.[^tor_blocking]

##### Tor and the dark web

Tor is one of the principal means of accessing services that are not reachable through the open web, including sites using the `.onion` top-level domain.

Research on Tor usage indicates that the majority of users are motivated by a desire for privacy rather than by any intention to offend.[^tor_ghazi] Journalists, whistleblowers, human rights workers and people living under censorship regimes use the network to communicate and report without exposing their identity or location.[^tor_moore2]

The same properties are also used to conceal serious offending, including the distribution of child sexual abuse material and trafficking in illicit goods. Australian courts have dealt with the network in several recent matters:

{: .example }
> **_Director of Public Prosecutions (Cth) v XYZ (A Pseudonym)_ [2024] VCC 1188** — the offender used Tor to access and download child abuse material; investigators were able to recover the relevant browsing history from the seized device.
>
> **_Aitken (A Pseudonym) v The King_ [2025] SASC 120** — a matter involving blackmail and threats to a school, in which forensic examination extended to the applicant's VPN and Tor usage.
>
> **_Attorney-General (Qld) v GFA_ [2025] QSC 19** — in making a supervision order in relation to an offender who had accessed child abuse material, the court imposed conditions restricting the use of anonymising software.

These cases illustrate a recurring point: anonymity technologies do not place users beyond the reach of investigation, because evidence is frequently recovered from the endpoint device rather than from the network itself.

[^tor_asd]: Australian Signals Directorate, _Defending against the Malicious Use of the Tor Network_ (Advisory, 2020).

[^tor_davis]: Shelby Davis and Bruce Arrigo, 'The Dark Web and Anonymising Technologies: Legal Pitfalls, Ethical Prospects, and Policy Directions from Radical Criminology' (2021) 76(4) _Crime, Law and Social Change_ 367.

[^tor_moore]: Daniel Moore and Thomas Rid, 'Cryptopolitik and the Darknet' (2016) 58(1) _Survival_ 7, 15.

[^tor_app2]: _Privacy Act 1988_ (Cth) sch 1 (APP 2).

[^tor_app11]: _Privacy Act 1988_ (Cth) sch 1 (APP 11.2).

[^tor_retention]: _Telecommunications (Interception and Access) Act 1979_ (Cth) pt 5-1A, s 187C (two-year retention period). See [Data Retention](#data-retention) above.

[^tor_tola]: _Telecommunications and Other Legislation Amendment (Assistance and Access) Act 2018_ (Cth), inserting _Telecommunications Act 1997_ (Cth) pt 15.

[^tor_blocking]: Davis and Arrigo (above) 378.

[^tor_ghazi]: Adam Ghazi-Tehrani, 'Mapping Real-World Use of the Onion Router' (2023) 39(2) _Journal of Contemporary Criminal Justice_ 241, 250.

[^tor_moore2]: Moore and Rid (above) 17.
