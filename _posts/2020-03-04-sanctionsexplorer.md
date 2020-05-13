---
title:  "SanctionsExplorer"
excerpt: "A search tool centralizing information pertaining to internationally sanctioned entities."
layout: posts
header:
  teaser: "https://raw.githubusercontent.com/mefrem/mefrem.github.io/master/assets/images/sanctionsexplorer.png"
date:   2020-03-04
canonical_url: "https://maxefremov.com/interviews/sanctionsexplorer"
---

![SanctionsExplorer Homepage](/assets/images/sanctionsexplorer.png "SanctionsExplorer Homepage")

I just completed the alpha version of a web-scraping, natural language processing web application that provides information pertaining to internationally sanctioned entities. Before I describe its technical details, it's important to know the motivation for the project.

## Sergei Magnitsky

In October 2007, Sergei Magnitsky—a Russian tax accountant—was assigned to investigate a peculiar case. Hermitage Capital, a client of his law firm, had been accused of tax evasion to the tune of hundreds of millions of dollars.

Hermitage’s owner and chief investor Bill Browder was bewildered and furious. He had provided Magnitsky's law firm official Russian documents that revealed that not only had Hermitage paid its taxes, it had in fact *overpaid*. Magnitsky tirelessly investigated the case and by 2008 had come to discover something astonishing: that police had raided Hermitage’s offices, stolen company documents, and claimed a tax refund on behalf of Hermitage, effectively stealing the tax payment. More astonishing was that the sophistication of the fraud and the involvement of various government officials meant that the Russian government was complicit in the theft from the Russian people.

For his work, Sergei Magnitsky was jailed, interrogated, and tortured. He spent 11 months in jail without trial and on November 16, 2009, just eight days before he would have to be released, he died in captivity.

In response, the United States passed the **Magnitsky Act**, also known as the **Russia and Moldova Jackson–Vanik Repeal and Sergei Magnitsky Rule of Law Accountability Act of 2012**. It imposed travel restrictions, froze assets, and sanctioned the Russian officials responsible for the death of Sergei Magnitsky. Anyone found to be transacting or trading with the persons or entities on that list would face stiff penalties. The act also empowered the United States Treasury Department’s Office of Foreign Asset Control (US OFAC) to maintain the Magnitsky Act's lists of sanctions and make determinations about who to include as part of American foreign policy.

## SanctionsExplorer

Sanctions are a tool at governments’ disposal to influence the behavior of other nations, organizations, and individuals, typically as a matter of national security or to protect international law. The United States pursues many sanctions programs, mostly administered by OFAC and at the discretion of the President, but Congress also imposes economic sanctions. And the United States is just one such authority—in fact, any country can impose penalties for transacting or trading with a sanctioned entity, as well as the intergovernmental organizations like United Nations and European Union.

There now exist hundreds of international sanctions programs, each with lists, databases, accompanying documentation and reports. It is increasingly difficult to keep up.

I just completed work on a web-scraping search tool providing centralized access to information pertaining to internationally sanctioned entities. Not just the entities listed in the Magnitsky Act, but individuals from North Korea, the Taliban, pirate vessels and designated terrorist organizations.

In just six weeks of development, the entirety of the US OFAC databases are searchable, as well as all of the United Nations sanctions programs’ Panel of Expert reports. These PoE reports provide critically useful information regarding not just sanctioned entities but also known co-conspirators that law-abiding citizens and organizations would do well to avoid. However, with hundreds of these reports, each hundreds of pages long and no centralized way to search them, they languish in obscurity.

No longer. My team—three data scientists,  four web developers and a UX designer—collected and rendered them searchable, with accompanying links to direct United Nations sanctions programs, sources, and documentation.

Now journalists, academics, risk and compliance officers at financial institutions can more easily exercise due diligence and investigate individuals that may be sanctioned or known to associate with sanctioned entities.

Thanks to the [Center for Advanced Defense Studies](https://c4ads.org/) for sponsoring such important work.

(This article was cross-posted to [LinkedIn](https://www.linkedin.com/pulse/sanctionsexplorer-max-efremov))
