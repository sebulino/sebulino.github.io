---
layout: post
current: post
cover:  assets/images/PriceOfAnarchy.jpg
navigation: True
title: Price of Anarchy - cool like a banana
date: 2022-06-28 21:00:00
tags: [lightning-network]
class: post-template
subclass: 'post'
author: sebastian
---
Whenever I read about PoA, I am immediately transported back to the circle of fellow adventurers who gather around a camping stove on a moist and overcast afternoon, watching chicken broth boil, and we all await our recovery after arriving at Barranco Camp, south of Kibo. 

Our guide casually asks if everybody is fine, and he usually receives back the familiar „Poa, kichisi kama ndizi“. Which loosely translates to „crazy cool like a banana“. But this is not about "Poa..." today. 
What it really is about, though, is the Price of Anarchy, abbreviated as PoA. To keep things short and as that slight nod to the knowledgable and initiated. Which clearly I wasn’t, until a short while ago. And what for sure I was not, while I was sighing and surrendering to my fate of the punctured inflatable (not anymore) mattress on one of the first days on my way to Uhuru Peak.

### So what is it, PoA? 

Whenever we as informed and rational people take decisions we weigh our options. And while assuming we are not driven by any altruistic, emotional or otherwise irrational motives, we usually tend to go for those decisions that maximize our utility. We look for the biggest bang for the buck. If there are shortcuts, we tend to take them - unless of course we associate risks or foregone experiences from the usual path that seem too large, so that we decide otherwise. We optimize. We are particularly happy, when we have a dominant strategy, this a series of decisions or answers to situations, that lead to the best possible outcome for us. 
This rational behavior leads to a result, that we as an individual highly appreciate. However, when leaving Robinson Island, thinks can be different. If we observe the application of the same - individually optimal - strategy by a group of people, the result can be surprising, because a coordinated strategy might lead to a higher benefit for everybody. If there was, for example, an omniscient observer that coordinates, then pursuing a different strategy can increase utility for the everybody. The most prominent example of game theory might be the prisoners dilemma. The individually optimal strategy is to betray the other. But if they were to behave coordinately, the outcome or welfare for both would be way higher. This example shows, that there is a difference between the coordinated and the selfish behavior, which is measurable. This metric is called the Price of Anarchy. Or from now on PoA for you, the now initiated.

Now, modern game theory has been the thing for a while, actually approximately since a hundred years ago. Its renaissance dates back to John von Neumann. The same guy who brought us the von Neumann architecture, by the way. Von Neumann architecture is the „layout“ of how most modern computers process programs and data today. This surprised me, actually. I mention this, because I find myself at the intersection of computer science and game theory. 

### game theory and bitcoin
With a growing interest in Bitcoin, the number of nodes has tripled over the last seven years. The increased demand for transactions in bitcoin and the fact that bitcoin is structurally a peer to peer network brings up challenges, because of adverse to network effects. One negative network effects is for example the latency when it comes to propagation of transactions across the nodes. The time for each node to know all transactions increases. Another problems comes from the fixed maximum amount of data that is processed. The bitcoin blockchain grows by one block approximately every 10 minutes. This puts a restriction on the possible amount of bitcoin transactions per unit of time. Bitcoin is designed to be a digital currency, but lacks the amount of throughput that is currently achieved by credit card companies on a daily basis. Thus the bitcoin blockchain alone would not be a suitable surrogate currency. 

This is why the Lightning Network plays an important role in addition to the bitcoin blockchain. The Lightning Network is a peer to peer payment network that is built on top of the bitcoin blockchain. The Lightning Network is a graph of bilateral payment channels, where money can be sent from one sender to a receiver across a series of nodes. However, as opposed to for example a hawala system, the Lightning Network does not depend on trust. Opening a channel with a peer requires a commitment transaction registered in the bitcoin blockchain, so that the channels - or even the network - is not built on the promise to pay, but it is actually anchored in the bitcoin blockchain. As a consequence, no trust is needed to send or receive money on the Lightning Network. Given its character as a network of bilateral channels with no trust needed, the number of transactions is potentially limitless, for as long as the channels carry enough satoshi (100 mio satoshi is 1 bitcoin). 

When a payments is sent through the Lightning Network, a flow needs to be decided, along which nodes the payer’s money is sent. This path between payer and payee is found by solving an optimization problem in the sender’s own best interests according to her or his goals. 
However, this strategy can lead to network congestion and might decrease the reliability of the Lightning Network, because it leads to the depletion of channels, so that no money can be sent between the connecting nodes. This strategy is called a selfish routing strategy. And similar to the example above, there is most likely a cost to the network as a whole. Which means that there most likely exists a Price of Anarchy for this selfish routing. 
The loss of welfare caused by selfish, uncoordinated behavior in networks has been observed and researched extensively by Tim Roughgarden.  The question is, if and how this translates to the Lightning Network. 

And this is what our project in the Sommer of Bitcoin 2022 is about. 

It might be as challenging and the same amount of endurance might be needed, as for climbing Mount Kilimanjaro. But at least for the time being I can say, that it is very exciting and I learn a lot. 

So far I’m fine - poa, kichisi kama ndizi.


