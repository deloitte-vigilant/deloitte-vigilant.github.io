---
layout: post
title: TRUST 
categories: [trust, phishing, security]
tags: [trust, phishing, security]
fullview: true
---

###Threat Reduction via Understanding Subjective Treatment

Information Systems are the norm when it comes to doing business in the 21st century, and it.s not going away. With that, the systems themselves are an enticing target to malicious actors that like to conduct their form of business, albeit illicit, on the Internet. In comes the TRUST, a model designed to classify trustworthy behavior for any data that would like to enter your business environment, the most common transmission being email.

Over the years it has become obvious that spam, phishing, and malware attachments are not going away, rather the evolution has caused a higher efficacy of successful penetration into business networks due to the increase in reconnaissance and precision (e.g. spear phishing) of such attacks. Yet we still apply the same basic technology such as bayesian spam filters and blacklists to prevent the human at the end of the keyboard from unintentionally letting these miscreants into our network and exfiltrating high value business information effortlessly and in plain sight?

Today.s solution is incident response, an after the fact reaction to discovering a breach, which in many cases is way too late, and the information is out the door and being sold in the shadows. Where did we go wrong? Why are these problems not solved? Is it a technology problem? Policy? Lack of training? Apparently not.

When spam and phishing was exploding around 2002-2003, the online internet security industry offered multiple solutions to this hard problem and to this day, with adoption of the few that remained (such as SPF, DKIM and DMARC), we find ourselves still behind the threat, rather than ahead. Do we have the right perspective on this? As machine learning and data science is becoming the new norm, I.m still not convinced that the applications will solve the problem until you ask the right question?

The question commonly today is - .How do we identify the lie?.

This has led us to anti-spam focusing on identifying spammy email, or phishy email based on content, and other tell-tale properties with a decent effect, but email servers are still getting slammed with spam processing. Unsolicited email (be it malware, phishing, or just viagra) is sent to millions, and usually poses as legitimate email so it can get to your inbox. We.ve seen this with brand-based phishing such as fake bank emails of well-known financial institutions, and we have seen spoofed email spams drop malware onto networks quite easily. In business, email is the most commonly used service and is a vital communications medium within today.s high-speed business culture.

What if the question was: .How do we identify the truth?..

In regards to human psychological behavior, whether cognitively or subconsciously, the brain can determine familiarity and routine as it learns from these experiences overtime for the person(s) to interact comfortably with these situations. Essentially a trust model is established around those experiences and people generally feel safe. On the other hand, introducing unfamiliar situations or experiences triggers a different response, causing heightened awareness, mistrust, defensiveness, fear, uncertainty, doubt and a plethora of cautious signals to the brain due to a significant deviation within the experience when compared to familiar, comfortable experiences. In the online world, brand spoofing such as fake bank sites distributed to a user.s inbox exploits this familiarity or trust model because the user only knows of the content and most users have no understanding of the technology delivering their email, and even if so, they are busy focusing on running a business.

Behind the scenes the email headers describe the lie, or to use an analogy, Alice offering a verbal promissory transaction to Bob but Alice.s fingers are secretly crossed behind her back. Bob only sees the promise, the familiar experience, but behind it is the lie which Bob will suffer from after it.s too late.

**Scratch a lie, find a thief...**

In information systems the IT/IS/Infosec department is tasked to minimize online risk to the infrastructure and to the business, and even with highly talented teams investing their day and night work efforts, futility exercises are still apparently present. 15 years of history alone in information security and the threats have only become more rampant. What are we missing?

**The truth!**

We react to the overwhelming threats i.e. the bad, the observables, the indicators, the adversary, the underground and a surplus of other threat research, and we forgot to think intuitively. Do we know ourselves? Do we know who we trust. When it comes to building threat models, it.s become overly complicated. But it shouldn.t be.

**Information**: What information are you dealing with, why, how, when, who and where is the information going?

**Secrets**: Where are your secrets, including data, passwords, key. How do you protect them?

**Actors**: Who are the actors involved. Bad and Good.

And yet... we forgot **good!**

*Know yourself, and you gain the upper hand against those who are looking to harm you.*

I propose building a trust model focused on what we know is good and familiar to the network and systems, and thus bad will be trivial to identify and discard. This model will offer a unique enhancement in how we protect information and will reduce the requirements that carry heavy cost to the business, both in processing, analyzing, and dissemination, as well as improvements in scale, and total cost of ownership. In application this model will reform online business reputation and eliminate deception from entering your network.

##Example use cases:

**Brand-based phishing**:

By analyzing a large sample set of headers of legitimate bank-originated emails, it will be apparent the similarities and you can train the model to identify the pattern of truth. By classifying information more effectively, such as classes of mail (personal - gmail, business class email - bankX.com) the deviation when compared to a phishing email of the bank.s brand will prove unfamiliar and illicit, due to a distinct deviation from the norm.

Additionally digital signatures (such as DKIM) would finally be effective for this model since the key can be partly derived from the properties of familiarity that the original bank has proven. Essentially any incongruent behavior will be rejected.

**File Attachment behavior within Emails**:

By classifying email types such as personal and business, as well as other features like .new event, never before seen email, and recipient types (HR Department will have different expectations and experiences) one could assist business email recipients in recognition of malicious attachments and discard them without much analysis.

An example question would be (non-HR department):

How often when one receives a first time email contact in the work place from a legitimate and reputable business class email will it contain attachments such as pdfs and docs on the initial introduction email?

By performing measurements of this type of activity, the behavior could be considered in the TRUST model.

How many personal gmail accounts should be sending email claiming they are an online legitimate bank?

How many non-government IP.s (or foreign, or personal) should be sending emails identifying themselves as the FBI (re: FBI nigerian scams)?

**File behavior analysis**:

Docs and PDF.s can be baselined using fuzzy hashing, temporal, frequency and entropy analysis to determine and establish legitimate human modified documents by sampling human-originated documents. Exploits and malware found in documents will exceed standard human baseline and deviates significantly from the established trusted information. This can be performed without invading privacy of the incoming documents, and can be handy in detection of malware attaching to documents in a shared environment.

**In conclusion**:

Let's pit unyielding truth against ever evasive deception to be ahead of threats, defend and maintain our gain while exploiting the opponent's unexpected loss. Our victory will force the threat actor to be behind us for a change - that is the ultimate goal.

