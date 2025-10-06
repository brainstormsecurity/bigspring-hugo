---
title: "15% of any ransom payment if you give us access to your PC"
date: 2025-09-28T10:07:21+06:00
# post image
image: "images/blog/bbc.jpg"
# post type (regular/featured)
type: "regular"
# meta description
description: "Understanding and Mitigating Insider Threats in the Age of Ransomware - Are your employees being targetted?"
# post draft
draft: false

---
### The human firewall? 

Having spent decades on the front lines of law enforcement and now navigating the complex, high-stakes negotiations following major organisational breaches, I have witnessed firsthand how rapidly cybercrime tactics evolve. While perimeter defences, endpoint detection, and robust firewalls remain critical, the simplest and most effective vector for a major ransomware attack is often not a coding vulnerability, but the human element.

The most dangerous threat to an organisation today is the one operating behind the firewall: the insider. Better known as 'your employees'.

#### The New Calculus of Initial Access

Ransomware-as-a-Service (RaaS) groups, such as the notorious Medusa, have professionalised their criminal operations. They have shifted resources away from brute-force external attacks toward the tactical, precise exploitation of individuals with legitimate access. Initial Access Brokers (IABs) and ransomware affiliates now view an employee's login credentials as a highly valuable commodity, often the quickest path to a multi-million dollar payload.

The financial incentive structure they employ is staggering, specifically targeting employees who may be facing financial distress, dissatisfaction, or simply possess a willingness to compromise their ethical standards for massive personal gain.

![Ransomware hacker wearing gloves, using a laptop in dark room to negotiate](../../images/blog/hacker1.jpg)

This shift was chillingly demonstrated in the public eye recently, when a criminal gang directly propositioned a BBC reporter for access to the organization's network. As the reporter Joe Tidy detailed, the criminal operator, using the encrypted chat app Signal, initially offering **"15% of any ransom payment if you give us access to your PC."**

The negotiation rapidly escalated, illustrating the immense value criminals place on inside access. The operator soon upped the offer, claiming that a successful infiltration could lead to a multi-million poundr ransom, and assured the reporter: **"You wouldn't need to work ever again."**

This is not idle boasting; it is a calculated business model designed to turn trusted employees into unwitting, or witting, criminal partners.

![Top of a computerscreen showing the BBC news website relating to ransomware news](../../images/blog/bbc.jpg)

#### How Ransomware Gangs Target and Convert Insiders

Based on intelligence gathered from post-incident negotiations and criminal communications, the process of securing an insider threat generally follows a clear playbook:

**Identification:** Criminal groups scour public forums, professional networking sites, and dark web job boards to identify individuals in target organisations, particularly those in IT, finance, or executive support, who possess high levels of system access.

**The Approach:** Communication is initiated on encrypted platforms (like Signal or Tox) to bypass corporate security layers. The tone is often professional, focusing purely on the financial opportunity. The criminal acts as a "reach out manager," emphasising that this is a lucrative, low-risk business deal.

**The Offer and Enticement:** The offers are scaled to the potential ransom, often promising a 15% to 25% cut of the final payout—a sum that can easily dwarf an employee’s salary. The Medusa operator in the BBC example, for instance, offered a guarantee of a half-Bitcoin (£40,00 GBP at the time) deposit as a sign of their seriousness.

**The Delivery Method:** Once the insider agrees, the criminal requires one of three simple things:

**Login Credentials:** Handing over a username and password.

**Malicious Execution:** Being asked to execute a simple command or run a small piece of code on a work machine to gather network configuration data.

**MFA Bypass:** When the reporter stalled, the criminals escalated to MFA bombing, repeatedly spamming the employee’s phone with two-factor authentication requests until the victim, often frustrated, clicks 'Accept,' thereby granting the attacker entry.

#### Mitigation by building a Resilient Human Firewall

For any Chief Security Officer or executive responsible for organisational continuity, the focus must shift from merely detecting technology breaches to preventing human ones.

As a negotiator, my advice is clear: you cannot afford to wait until a six-figure ransom demand is on your screen. Proactive measures must be implemented to manage the insider threat.

**Cultivate a Culture of Trust and Reporting.** Employees are far less likely to be tempted by outside offers if they feel valued, secure, and understand the catastrophic real-world consequences (data theft, loss of livelihoods, reputational damage) of a successful ransomware attack. Crucially, they must know they can report suspicious contact, like the unsolicited messages received by the BBC reporter—without fear of professional penalty.

**Targeted Security Training:** Generic annual training is insufficient. Security awareness must address the modern criminal playbook. Employees need to see clear, real-world examples of the financial offers and the social engineering techniques used to pressure them, including the tactic of MFA bombing.

**Implement Principle of Least Privilege (PoLP).** This is non-negotiable. No employee, regardless of seniority, should have more system access than their role strictly requires. Limiting lateral movement is the single most effective technical defense against a compromised insider.

**Continuous Monitoring for Anomalous Behaviour.** Behavioral analysis tools that track unusual log-in times, excessive data downloads, or attempts to access systems outside of normal job functions are vital. A system must flag when a user is attempting unusual activities, even if they are using valid credentials.


The criminals are not just targeting your systems; they are targeting your people. In the ransomware era, the insider is the most efficient and alarming vulnerability. Protecting your organisation starts with ensuring that every employee understands the threat and is empowered to be the first and strongest line of defence.


If you are worried about how to protect your organisation from insider threats or would like to find out more, please get in touch with Brainstorm Security Ltd today. 

You can read the full chilling article on the BBC website of how Cyber correspondent Joe Tidy, was offered a deal by criminals to help hack the BBC.


 https://www.bbc.co.uk/news/articles/c3w5n903447o 