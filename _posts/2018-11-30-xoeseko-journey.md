---
#layout: post
title:  "Xoeseko enters sdg-market"
date:   2018-11-30 15:22:34 +0100
categories: jekyll update
author: Xoeseko
---
# Xoeseko's journey into sdg-market
## Open Science SDG project report by Xoeseko Nyomi

### Introduction :
My involvement in the project started this October when Thomas came to talk to our class about open contributions with structures such as Github and Wikipedia. I personally already knew a little about open source and had without a shadow of a doubt benefitted from it both privately and professionally. I had however never actually contributed personally to an open source project. So I warmly welcomed the idea when Thomas suggested Sofia and me could get involved with the sdg-market he was developing. The aim of the sdg-market is essentially to provide an open and decentralized platform, a market, where projects which work towards sustainable development goals can be "remunerated" through tokens and thus galvanized be it through the gamification where developers receive  tokens for contributions or through financing where investors can purchase tokens of projects they find interesting. A [prototype](https://sdg-market.oniabsis.com/) of the project was already running. Our tasks were thus multiple, we first had to read the [whitepaper](/whitepaper) to understand the goal. We then tested the platform to see if any bugged slipped in during development. We could then get involved in the open collaboration process. As testers we were essentially reviewing the project and as contributors we could work directly at issues we found relevant to address.

### Testing :
We first started by registering on the prototype to see what was possible. It was pretty straight forward since the prototype is essentially a proof of concept relying on Github and that I already had a Github account. That part went down smoothly we then went on to try various transactions and remarked a few UI issues. We notified the developers through their Github repository since the code is openly available. We weren't able to directly address those but did create an issues to notify them. We discovered further issues after testing the interface by trying to use the API to access the data that is supposed to be open. We created an issue for that too and the response was quite prompt within a day the developers commented on the issue and tried to address it although it is still not resolved.

### Contributing :
As contributors, we looked at everything we could do... After applying a checks and balances review process to the prototype we identified areas where we could add something. Those areas were:
 - Documenting the platform to make it easier to access
 - Building data visualization tools so that users of the platform could easily view the evolution of tokens they owned or projects they were interested in. Similar to how financial platforms do.
  - Implementing a blockchain mechanism for storing transactions in a decentralized manner and governing project auditing.

For the documentation part we chose pretty early on to take advantage of open resources available and deploy a Github pages documentation site which hopefully can be integrated to the project at the end of the day. It was an interesting learning curve but truth be told extremely easy to learn considering I am really not used to web development. The result is something we can be proud of. It was also interesting to see the wealth of open templates developed by other users. Maybe one day we can also contribute one. The most interesting aspect is probably learning that Github  actually provides a way to host websites totally free of charge and through relatively simple or at least well documented steps.

### Data visualizations :
The data visualizations were what I initially thought would be most interesting. Applying what we learn in programming to an actual concrete goal. In all reality it was a pretty straightforward process that didn't require too much thought. It was however interesting to think with Sofia about the best ways to visualize what we wanted to leading us to the results you see on this page. It also led us to discover other bugs within the API with the data retrieval which I suspect really helped the developers because it would have taken a really long time before anyone thought about testing those features if it wasn't for the concrete use case we had.


### Recursive development :

Everything that we developed we also made openly available through a Github repository that was itself on the sdg-market. Leading us to study first hand the token generation process. We also identified an issue through that which we were able to notify the team of. Essentially, tokens were only generated for the first few projects but not for any of the new ones added. We notified them of that and they are still working on it.

### Conclusions and further developments :
Out of the different goals we set off with, we were able to address almost all except one potential contribution. We tested the platform extensively, generated visualizations and added documentation to the platform. We learned a lot through the process but we couldn't implement a blockchain recording system. Of course it would have been extremely over ambitious to think we could do everything in the short span of three weeks with everything else we had going on. It can however be left as a potential further development and if we think within the open contribution spirit and the sdg-market spirit which remunerates recommendations. I remembered that I knew a guy who had implemented blockchain solutions before. Leading to one further development where I could learn about blockchain and contribute by getting this person involved demonstrating simultaneously the power and virality of open contributions. A more closed system might have led me to think more selfishly about this development and made me have to learn on my own. Finally, a few development questions I would have are ?
 - An sdg-market is much bigger than only open source software contributions. How does the project move forward by allowing different types of projects to be traded on the platform ? Hardware has a potential since Open hardware repositories exist. But how do more human projects get involved ?
 - Similarly a market based on Github could be a welcome aid to an open source market in dire need of financing opportunities. Is there a way for the platform to open up to all sorts of open source projects while still prioritizing sdg projects ?
 - Are the mechanisms for remunerating sufficient ?
 - Currently the source code for the project is openly accessible. That still doesn't make the project in the sense that free and open source entails. For that we would need to explicitly grant at least some rights through the use of a license. What might be most adapted ? Perhaps some kind of SSPL like MongoDB uses or less controversial an AGPL ?
 - How can I keep further involvement with such a project ?
