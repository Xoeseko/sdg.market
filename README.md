# sdg.market

**A Decentralized Market for Sharing Knowledge and Expertise for the SDGs** 

### Introduction

The 17 United Nations Sustainable Development Goals (SDGs) have set an agenda to make the world more sustainable by 2030. The SDGs follow the Millenium Goals, which were set for the period 2000 until 2015.

Here, we believe that sharing and exchanging valuable open knowledge as well as expertise associated with concrete projects aimed the SDGs, is a way to go that empowers all people willing to contribute.

We also believe that market mechanisms can help bring enough incentives and motivation for people to share knowledge and contribute collectively to the concrete achievement of projects aimed at addressing outstanding issues associated with the SDGs. 

We further believe that if such SDG Market should exist, it should be transparent, decentralized. It should as much as possible avoid intermediaries. However, we keep in mind that there is no one-size-fits-all solution to efficiently sharing knowledge. The  SDG Market Project borrows from past and ongoing & experiences on fast and efficient knowledge sharing.

We aim to establish a common scalable platform to share knowledge for SDGs. 

This draft White Paper has come out discussions held at the iSDG Assembly 2017 in Shenzhen, which gathered high-school students from Beijing with their teachers, university students attending Summer School programs at Tsinghua University, University of Geneva, EPFL, Centre pour la Recherche Interdisciplinaire (CRI) and Harvard University.


### Background
* markets as a driver for trust : people make contracts
* Adam Smith

* crypto currencies
* the devil lies in details : full transparency of the market design in this white paper

### Motivations
* build a community
* fast exchange of knowledge
* scaling 
* excite curiosity

### What people should share :
- where they come from
- their skills
- what they aim to achieve
- how they value knowledge produced by themselves and others

### Requirements :
* fully open innovation
* transparency 
* respect individual and collective strategies
* maximize opportunity for contributors
* peer review with consensus building

### Governance/Institution :
Foundation

(see Ethereum institutional mechanism)


### Initial Funding & Initial Coin Offering (ICO) : 
The initial funders of the Foundation (min. 50k CHF) share 10% of SDGcoins issued during the ICO, in proportion of their respective contributions.

ICO : one SDGcoin = $5

After ICO : SDGcoins are issued in function of the number of transactions. Every 1000 (+ \epsilon e.g., 10%, to be further determined) transactions, one SDGcoin is issued and sold at market price by the Foundation.

Verification of transactions also bring coin rewards (tbd, but rather a power law decreasing function that flattens, instead of exponential decay which brings problems as for bitcoin).


### License :

* only one license: share - attribute - commercial reuse

### Content and Share Attribution :


#### Two Possibilities for share attribution :
- one share per contribution [scaled to project value] (preferred)
- one share per 1000 bytes produced [scaled to project value]


#### Incentives to share early and to produce small iterative steps

If use bytes as measure of quantity : 10% penalty following a negative linear function with \alpha = - 0.1 per byte [e.g., 2000 bytes contributed => 2000 x (1-\alpha) = 1800 bytes => 1.8 shares at nominal value (instead of 2)]


### Proposed Mechanisms :
* market :
* arbitrages possibilities: 
- contribute
- buy/sell stocks
- short selling (liability up to wallet and shareholdings, i.e. a short seller may lose everything if the traded project gets very successful)
* slow market : one transaction per minute per user.
* increment : 0.1
* transaction costs : 0.005 ? Where these fees go ? => Association/Foundation


##### Reuse & Fork:
One should be incentivized to reuse parts of existing projects, or even fork projects following the sharing requirement.

##### Reuse :
Reuse is free but incumbent content producers should be rewarded for their past work.
When content is reused from one project to another, the stockholders of the incumbent projects get shares from the reusing project. 

100% of the shares of the latter project and distributed to the individual having performed the reuse. The shares are spread across the shareholders of the incumbent project in proportion of their respective holding in the incumbent project.

##### Fork :
In case of fork, the initial stock of shares in the latter project is set arbitrarily to 200. The incumbent shareholders share immediately 100 shares of the latter project and the individual having fork gets the other 100.

Valuation starts at 1 and initial capital is 200.

Fork of intermediate versions is possible. Distribution of bonus shares to incumbents is made according the contribution and stock values states at the time of the version.

Fork may for instance allow rebooting a project, which has experienced a governance failure.

Expected behavior : a fork is pure replication of content, which brings no additional information. Therefore, if the project does not bring expectation that it will distinguish itself from the parent project, it should lose traction and thus value fairly quickly. Another more annoying but possibility would be that it reaches the same value as the incumbent project (since they both contain the same information). However, this is unlikely because the value of a project entails its capacity to grow and adapt. For that community building is almost required. If the forked project strives with another community, then the fork is a success and the project gets its own value.

##### Merge of two projects:

Not clear how we can have a merge happen besides reusing parts of one project to another, and abandoning the former project by selling stocks until project value gets residual.

(I would not advocate for a negotiation based bargain/deal)

#### Invitations & Recommendation / Pull Requests / Merge :
One way to share resources and effort is to recommend/invite contributors to help for a project.

If an invitee to a project makes a contribution, the recommender get half of the shares. If the invitation is carried on further, each recommender get half of the shares of her invitee. For example an invitation is carried on 3 steps and the final invitee has contributed and has received 10 shares. The person who has invited her gets 5 shares, the recommender who invited the person who has found the contributor gets 2.5 shares, and so on recursively. This mechanism offers strong incentives to reach out for targeted help, and to further build the community (It was used for the DARPA Grand Balloon Challenge).

It's all about invitation to contribute (c.f., recommendation above), or a spontaneous request to make a contribution. A request to make a change to a GIST shall be made to the owner or the main contributor of the GIST (to be clarified in details). This request may be presented as an outline of the fostered change, or in the style of a pull request, with a diff already integrated in the request.

If the GIST is part of a project, the contributor which contribution has been accepted shall receive some shares of the project (according to the market value rules, c.f. above). If the accepted contribution follows an invitation, the inviter gets a bonus. If it's a spontaneous contribution accepted, the contributor gets the same bonus for herself.

If the GIST is not part yet of a project, "foster shares" are counted and registered but they cannot be traded until the project is incorporated with this GIST (and perhaps other GISTs altogether).


Practical Issues : 
* an invitee new to the system should create an account (equiv. a wallet)
=> one way is to create immediately a wallet per email address. The account can be confirmed later (different emails can be confirmed and consolidated in one account)
* an anti-spam mechanism might be needed, based on peer-review, or by providing a button in the email sent for the invitee to report spam. To deter spam, each invitation may a cost a very small fee (0.05). Similarly, a request to contribute shall cost a very small fee (0.05), reimbursed when the contribution is accepted.

#### Project Membership :
To become a core member of a project, one may achieve a number *n* of accepted pull requests on GIST by *P* different project members.*n* and *p* may be set by default to *p=min(#members,3)* and *n=5* or they can be customized by project. Larger *p* and *n* reflects more extreme vetting.

### How does this translate into real money ?
As long as there is no transaction, the project has no value. It needs a least one transaction to get a first valuation. For that a shareholder, who has acquired shares through contributions, must sell some shares to someone ready to pay cash for them.

### What happens if a project needs cash to continue ?
At some point, a project may need cash to continue its development. Usually, raising money involves creation of new shares. It's money printing. Is there a way to avoid this ? 

#### Tobin tax ?
One could introduce a fee per transaction, which would go to a "project wallet", which is owned by project owners at the pro-rata of shareholdings. The Tobin tax amount shall not be negligible, perhaps 1-10% of the transaction, with a min and a max defined.

#### How to spend the money ?
To make an expenditure, it's like internal crowdfunding. A proposition for expenditure is made. Then project owners shall contribute their "project cash" (earned from the Tobin tax). If the amount is reached, along with a quorum of contributors (to avoid freeloading), then the purchase is performed.


### Blockchain mechanisms
* hashgraph
* GitHub Gist or/and IPFS

### Overview of Practical Implementation Strategies :

* Platform developed by Bodo
* PoC contribution management with GitHub as a backend
* PoC blockchain market
* PoC contribution management with IPFS


### Next steps :
* review and improvement period for this document (until 31/12/2017)
* presentation at Davos
* European H2020 Grant Application (April) ?
* June 2018 : first working version (with GitHub as backend)
* August 2018 : sdg.market meeting at iSDG Assembly Shenzhen


### Apendices 

#### [future implementation] Delegation of Governance to projects

We start simple enough, but in the future, some rules may be set for each project by the project creator (e.g., share awards for contributions and recommendations. These rules may be changed only with a fork of a project.

#### Alternative Measures of Contribution

* commits instead of bytes : incentivizes many commits of less quantity (in bytes).
