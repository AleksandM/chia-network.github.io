---
lang: en
layout: post
title:  "Bram's thoughts on responsible fintech"
date:   2022-06-03
author: "[Bram Cohen](https://twitter.com/bramcohen)"
---
_(The following is a [Twitter Thread by Bram](https://twitter.com/bramcohen/status/1532083147877167104) on June 1st, 2022. It’s being re-shared here as we feel it’s of notable interest to both the Chia community and Crypto community at large. The text has been minorly edited for readability and flow, but otherwise preserved in it’s twitter format.)_

<p align="center"><img src="/assets/blog/6-3-22-blog.png" width="75%"></p>

[A letter from some crypto skeptics](https://concerned.tech/) is going around today, and I have a nuanced take on this I'd like to share.
 
Here is the main point which is technically wrong: "Financial technologies that serve the public must always have mechanisms for fraud mitigation and allow a human-in-the-loop to reverse transactions; blockchain permits neither."  
 
By technically wrong, I mean I've been building exactly what they're talking about. Programmable blockchains allow you to have exactly the business logic you want around moving around money.
 
Banks provide these services in a way which has very little transparency or end user control (and often implicitly enables a lot of fraud in the process). On a blockchain you can, in principle, make it follow any process you want with complete transparency and end user control.
 
Working on proper custody solutions is terrifying, not because there's anything wrong with what you're building, but because you realize that properly defining very basic processes is generic to money management, not just blockchains, and is never done ever.
 
So blockchains _can_ do this better than traditional banking. But the crypto industry writ large isn't off the hook here, because they _don't_. All they use is multisig.
 
I've been ranting about this for _years_. Bitcoin feels like carrying around suitcases full of cash, but it should be possible to do even better than banking. However, people don't get excited about real security… They get excited about Ponzi schemes.
 
The new custody stuff I'm working on is something we're going to dogfood soon, and productize after that.
 
Also finality is not the bogeyman they make it out to be. Finality is absolutely _critical_ in certain places, like Fedwire. There's no law saying that banks have to use fed wire, they do it because that's the only way to get finality.
 
The problem with a bank providing finality is that law enforcement can come in and say that a certain transaction was fraudulent, the money has to be sent back, and the intermediary would _have_ to enforce it.
Fedwire is run by the government, so if anyone tries to sue them saying they had to reverse a transaction, they can tell them to pound sand. If you want to reverse a wire you have to go to the recipient and ask for the money back
 
Banks keep using this system because to them, finality is a _good_ thing. Interbank transfers have to truly settle at some point or you'd never know who had what.
 
The other points in that article are minor and have simple rebuttals. Properly backed stablecoins, used properly, keep the volatility from being a problem. Case in point, we've got the climate emissions problem figured out.
 
I'm ranting about it because the main thrust of the letter is simply wrong. However, the crypto industry has been doing an extremely poor job of demonstrating its _real_ potential, so it's hardly surprising that these misperceptions are still so widespread.

