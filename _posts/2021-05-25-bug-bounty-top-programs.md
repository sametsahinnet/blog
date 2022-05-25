---
title: "Recommendations to programs from a hunter's perspective"
date: 2022-05-25
permalink: /posts/bug-bounty-top-programs/
tags:
  - bug bounty
  - best bug bounty programs
  - bug hunter
  - recommendations
excerpt: "Bug Bounty Ecosystem - Recommendations to bug bounty programs from a bug hunter's perspective."
---

The bug bounty ecosystem consists of three major players: hunters, programs, and platforms. The previous blog post mentions some recommendations for bug hunters. Now, this is time for the other major player: programs. 

The main goal of a bug bounty program is to find skilled hunters to assess their applications, systems, and other types of digital assets. Both to reach their goal and due to their different resources, programs set different policies. Whereas some programs get the hunters' like with their good policies, some fail and have to end their programs. Here are some key points for becoming a more successful program from a hunter's perspective:

- Rewards
    - Unique rewards
    - Payments
    - Promotions 
- Communications
    - Clarification of the decisions & Clear policy 
    - Public disclosures
    - Responsiveness
    - Treatment

# Rewards  
It is not a surprise for rewards to be the most eye-catching thing in an ecosystem, which includes bounty in its name. According to [HackerOne](https://www.hackerone.com/resources/reporting/the-2021-hacker-report) and [Bugcrowd](https://www.bugcrowd.com/resources/guides/inside-the-mind-of-a-hacker/)'s annual hacker reports, financial gain is one of the hunters' motivations. Bug bounty programs should set their reward policies consequently.

  **Unique Rewards**  
  Sometimes, regular cash prizes may not be as attractive as the unique rewards. Such rewards as t-shirts, coins, and the company's own goods may be more interesting for hunters and cost-effective for the programs. Here is a recent example: [Red Bull](https://app.intigriti.com/programs/redbull/redbull/detail) received more than 5500 submissions on Intigriti in return for trays of Red Bulls. The more unique rewards a program offers, the more interest the hunters have (usually)!

  **Payments**  
  It is worth recalling that bounty hunting is a freelance job. Most hunters do bug bounties for a living and to pay their bills. Due to the nature of the freelance jobs, their income is inconsistent, and sometimes that inconsistency becomes a problem for the hunters. To not put them in difficult situations and not waste time dealing with the "Where is my bounty, sir?" messages, the programs should pay when the bug is triaged, which is called "Pay at triage". 

  Programs should determine an initial bounty to apply that policy, usually three digits or a fixed percentage of the estimated amount. When the report is triaged, the initial payment should be sent. After the mitigation steps are taken, and the report is resolved, the remaining bounty should be sent to the hunter.

  **Promotions**  
  An excellent way to get the hunters' attraction in a short period is to run a promotion with increasing rewards. This policy helps programs to receive better and targeted reports. Some programs run promotions on specific types of vulnerabilities to test their recently updated assets, new releases, and recent zero-days. [Yahoo's promotion](https://twitter.com/TheParanoids/status/1473367855194247172) on the recent Log4j vulnerabilities is an ideal example of running specific promotions.

  When it is not beneficial to run promotions on specific vulnerabilities, running a general promotion may be a better option. [Meta's Hacker Plus Programme](https://www.facebook.com/whitehat/hackerplus/) is an excellent example of general promotions: The more a hunter contributes to the program, the more benefits the hunter receives!

# Communications
Although the rewards are essential for hunters to choose a program to hack, it is not the only condition. Ineffective communication between the programs and the hunters usually causes unwanted results. Therefore, programs should be straightforward in communication and easy to collaborate with. The below key points may help the programs be the favorite of the hunters, even if their rewards are not the best in the market.

  **Clarification of the decisions & Clear Policy**  
  Imagine a hunter finds a P1 severity vulnerability and reports it immediately with the dream of the bounty in mind. While the hunter is waiting for at least five digits from the program, they decrease the severity to P4 and offer $250 for some uncertain or unacceptable reasons. After some arguments and counterarguments, both parties will be unhappy with the result. Such situations occur primarily because of the programs' unclear policies and decisions and some hunters' unprofessional behaviors. Although both parties may be faulty, this blog post is for only the programs, so their role in the issue is examined.

  A program's policy must include "Dos and Don'ts" very clearly. The policy should also include the reward criteria and clarification of the report's decisions. A clear policy helps both parties to share their objections and reasons for the report. [Shopify's bounty calculator](https://shopify.github.io/appsec/cvss_calculator/) is an excellent example of this topic. Shopify lets the hunter know the rationale behind the bounty and clarifies every criterion that played a role in the decision. 

  Another important field to be careful in the policy is the rules to follow in the hacking process. Suppose a program aims to test only the specific part of their assets or wants to have the hunters follow some restrictions such as VPN usage, some limitations on testing, and the post-exploitation period. In that case, the policy should be set accordingly. As hunters usually do not read the whole policy, putting the important notes under the rewards table may be a good option. [Yahoo's program](https://hackerone.com/yahoo) is an excellent example of having a clear policy.

  **Public disclosures**  
  Disclosing reports is a good way to interact with the global hacking community, as it takes place in the hunters' feed. Publicly disclosed reports help the inexperienced hunters gain knowledge from a successful hack. Concurrently, they are also beneficial as they create an opportunity for already known contributors to collaborate with the other hunters. HackerOne's own program is an ideal example as they have a company value named [Default to disclosure!](https://twitter.com/hacker0x01/status/1072173331896516608).

  **Responsiveness**  
  Bugcrowd's latest hacker report shows that a responsive team is the most important thing that makes a program attractive. Therefore, the programs should be patient and responsive even though they receive many unnecessary messages about the status of the bounty or the report. 
  
  Bug bounty programs may pay at triage to decrease the number of unnecessary messages and therefore save time and focus on the more critical reports. Another method for saving time is to use the platforms' triage services. It is especially beneficial for big security teams, as they receive many inapplicable reports. 

  **Treatment**  
  Bug hunting is not easy since the hunters compete with the other hunters, black-hat hackers, and the internal security teams. When they find some vulnerabilities after that competition, they contribute to companies' security in a unique way as they see what is overlooked. Due to the importance of the bug hunters' contribution, the bug bounty programs should treat the hunters with respect. Public testimonials, job offers, and invitations to the company events are some ways to show the value of the hunter. 

# Conclusion
This blog post series aims to have a better bug bounty ecosystem. The bug bounty programs are playing a critical role in that ecosystem. The points mentioned above may help programs have a more successful experience. Even if some topics may not suit every program, I believe the programs will see the benefits of applying most of them! 





<hr>

**Thanks for their support on this blog post**  
[Berk Cem Göksel](https://twitter.com/berkcgoksel)  

