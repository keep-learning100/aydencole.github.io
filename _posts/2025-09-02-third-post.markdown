---
layout: post
title:  A Little Sales Pitch for Offline AI - Part 1
description: The Security Problems with Traditional AI
date:   2025-09-02 10:15:08 -0700
image:  '/images/06-1.jpg'
tags:   [study, personal]
---
I first heard about AI from my dad a few years ago, when he brought up this new thing called Chat GPT. I made an an account and started playing around with ChatGPT. I was awestruck with its ability to write goofy but technically brilliant poems on command, so I appreciated its comedic value but I didn't see much more use for it, and left it by the wayside for a couple years. But about 6 months ago, I had a chat with a coworker who was using AI to build SaaS using a mix of vibe coding and his own rich IT experience to keep a human-in-the-loop. That conversation inspired me to revisit the world of AI, and start experimenting with newer models like Grok 4 and ChatGPT 5. I discovered that it's not only incredibly useful for everyday tasks, it can (with proper caution) be implemented into cybersecurity in some intriguing ways. But most people may not be aware there are more interesting ways to engage with AI for cybersecurity beyond the traditional cloud-based models, and it's those types of alternatives that I'd like to discuss today.

The traditional AI models that you access online (e.g. Gemini, Grok, etc.) have some major OpSec flaws. These flaws begin with the log in process. In order to use the service, you have to provide a bunch of personally identifiable information (PII), like your name and email. Then when you start to interact with the AI, everything you say goes directly to the owner. I suspect this is more of a problem than simple Google searching, because talking with an AI assistant feels like talking with a real person, so people are more comfortable sharing parts of their life that they would never enter into a Google search field. 

> Users feel like they're chatting with a friend, so they might be lured in with a false sense of security to share things they would never enter into a Google search.

Imagine a scenario where a doctor is researching a patient's medical problem with Google (more common than you might think, lol). Now imagine they are doing the same thing with AI. I suspect they would be far more likely to slip up and enter HIPPA protected information about their patient when they're talking with a chatbot than when they're trying to enter the shortest Google search they can think of. 

That may not be a big problem when AI assistants are behaving how they are supposed to. But if they were to be hacked and someone with a knack for social engineering were to take control, users could be prompted to enter a lot of sensitive information, ranging from medical info down to banking information.

My last critique is that even when AI models are safeguarded from malicious hackers, you have to consider that the company's and individuals that own these models may not have your best interests in mind. Those AI models that you depend on have to be accessed via the cloud. What happens when the companies start charging subscriptions for the services you've grown to depend on and you've built too much context into your account to let go? What happens when they have a political change of heart, and decide to lobotomize their AI to match their every whim? (Looking at you, Elon.) Or even if it's not that overt, at the very least you know those companies are using your data to train their models and advance their scummy business practices that involve everything from copyright infringment to silencing whistleblowers. 

Proprietary AI models are developing at lightning speed, and there is certainly use for them. But if you want to incorporate AI into your cybersecurity model, you have to do some honest reflection about the risks and vulnerabilities inherent in vesting so much of your data in the hands of a cloud based company. Which will lead us to Part 2 - an alternative. 