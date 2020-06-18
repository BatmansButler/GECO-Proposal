# Alfred Proposal

## Project Overview

### Project name
> Alfred

### Team members 
- Aaron Anderson
- Ken Hodler
- Morgan Sherwood
- Seth Goldfarb

### What project are you building 
Alfred is a digital asset inheritance solution that helps people transfer their assets to their loved ones after they die or become incapacitated.

We offer a decentralized solution that facilitates inheritance when the user fails to check-in using our customizable **dead man’s switch**. We are also building an oracle that monitors traditional data sources for death information. When it detects the death of a wallet user, it notifies the wallet. As a safety precaution, the user can notify the wallet that they are not deceased by sending a signed message. This halts the automatic distribution of the assets. We call this the **live man's switch**.

Both solutions enable users to determine when death may have occurred and provide processes for confirming and contesting the death.

We will use this grant to complete the implementation of the Alfred Estate Smart Contract, dApp, and oracle service, then build a plugin that enables its use by a Gnosis Safe wallet.

### Why did you decide to build it 
The moment we die, the financial obligations related to our assets get passed along to loved ones. In order to maintain the asset, the financial obligation must be maintained. For example, loan payments and property taxes must continue to be paid to avoid having the underlying asset seized. Benefits from inheritance and insurance generally take several months to arrive and the beneficiaries are unable to maintain the obligations attached to the assets. Using Alfred, users can ensure that the funds to maintain their estate are available.

Additionally, it ensures that the inheritance process for digital assets doesn't have to be entrusted to a third party. Typically, there are two strategies for crypto inheritance:

1) Write down your keys with instructions on how to recover the assets.
2) Do nothing.

Writing down keys and instruction introduces a severe OpSec vulnerability. Wherever the keys are recorded, they are vulnerable to being found and used by untrusted third parties. Even when a trusted party is used, there is a risk that they will misbehave or handle the keys carelessly. There are other more elaborate schemes that can be used to overcome these vulnerabilities, but the vulnerabilities are never completely mitigated and often these schemes introduce new vulnerabilities.

The option to do nothing is the default option. It is probably the one used by most people who own a moderate amount of digital assets. In these cases, the assets are lost when the holder passes away.

We are also motivated by the situations associated with corporate governance of cryptocurrency assets. If a signer dies, it can often be difficult, and in some cases, impossible to recover the assets protected by the key of that signer.

We also envision Alfred's use for informal fund sharing by individuals. For example, when two friends are saving for a long vacation together or shared car, if one of them should die, the other person can access the funds.

People have a plethora of tools for supercharging their day-to-day productivity but when it comes to the pivotal moments in our lives, from birth through graduation, marriage, children, and death, we still generally rely on expensive, archaic solutions to manage our affairs. Alfred offers a way to manage these events more effectively using smart contract technology.

Automating the inheritance of digital assets can help people help their loved ones during some of the most difficult moments in their lives. 

=======

### How long will it take 
We will launch our unaudited beta of Alfred August 1 with a full release and Gnosis Safe integration targeted for October 1.

### How much funding are you requesting  
$20,000

### How did you hear about the GECO
Twitter

## Your Proposal 
### Project description
Our goal is to enable people to monitor the passage of the most important events of their lives and help people help each other by automating the delivery of services following their occurrence.

Facilitating the inheritance of digital assets upon incapacitation or death represents a critical gap in decentralized key management. We believe giving people access to data on such a pivotal event can be used to deliver a number of services not limited to cryptocurrency inheritance, including simple notifications and fiat inheritance. 

### Features
- Digital Estate Inheritance

Estate owners designate how their assets will be divided among their chosen beneficiaries when the time comes.  An executor may be added to assist beneficiaries with the distribution process and to help in settling any outstanding loans.  The Alfred Estate dApp makes the process of inheritance distribution simple.

- Create or Sync Wallet

Create Wallet allows the user to make a Gnosis Safe that is automatically connected to and protected by their Alfred Estate. Sync Wallet allows users to connect an existing Gnosis Safe with their estate.  By connecting a Gnosis Safe Wallet to an Alfred Estate any assets stored in the wallet are protected.

- Wallet/Estate Recovery

The Alfred Estate smart contract is a Gnosis Safe Recovery Module. If access to a wallet is lost while the owner is alive, the Gnosis Safe can be recovered using the Alfred Estate.  Recovery involves the assistance of beneficiaries and optionally the executor of the estate according to the owners prior specifications.

- Dashboard

  - Set/Edit Beneficiaries
  - Set Executor (if desired)
  - Distribute/Claim Funds

Hey do we to reference anything else?

### Team description
- Aaron Anderson brings dApps to market as a dApp engineer and cofounder of Web3Devs and Ching!
- Ken Hodler is a senior engineer, formerly CEO and an early contributor at Keepkey (exited to ShapeShift).
- Morgan Sherwood is a dApp engineer with 25+ year career as a Python developer and algorithmic trader skilled in smart contract security analysis.
- Seth Goldfarb is a marketing professional who helps companies tell better stories about the development of blockchain and its applications.

### Timeline, Milestones and Deliverables

**Phase I Beta Launch**

**Deliverables**
- Free, decentralized cryptocurrency inheritance solution using customizable dead man's switch
- Automated cryptocurrency inheritance solution using our oracle (U.S.-only)

**1 Month - $5000**	

**Phase II Full Release**

**Deliverables**
- Audit smart contract
- Consult legal counsel
- Interview users; iterate on UI

**2 Months - $15000**

### Others	 
Anything else we want to share?
