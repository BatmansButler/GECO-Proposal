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
Alfred is a digital asset inheritance solution that helps people transfer their assets to their loved ones after they die or become incapacitated. The dApp ensures that the inheritance process for digital assets doesn't have to be entrusted to a third party by facilitating inheritance when the user fails to check-in using our customizable **dead man’s switch**. 

Our goal is to develop tools that help prevent the loss of digital assets due to the loss of control over a particular set of keys.

We will use this grant to complete the implementation of the Alfred Estate Smart Contract and dApp, have the software audited, and build a plugin that enables its use by a Gnosis Safe wallet.

### Why did you decide to build it 
Helping people safely maintain custody of their digital assets remains one of the largest hurdles to the adoption of decentralized technologies. The value of lost cryptocurrency (sent to non-existent addresses or held in unreachable wallets) exceeds that of stolen cryptocurrency by a significant proportion (approximately 4x, according to our estimate).

Facilitating the inheritance of digital assets upon incapacitation or death represents a critical gap in decentralized key management.
Typically, there are two strategies for crypto inheritance:

1) Write down your keys with instructions on how to recover the assets.
2) Do nothing.

Writing down keys and instruction introduces a severe OpSec vulnerability. Wherever the keys are recorded, they are vulnerable to being found and used by untrusted third parties. Even when a trusted party is used, there is a risk that they will misbehave or handle the keys carelessly. 

Elaborate schemes can be used to overcome these vulnerabilities but the vulnerabilities are never completely mitigated and often these schemes introduce new vulnerabilities. The option to do nothing is the default option. It is probably the one used by most people who own a moderate amount of digital assets. In these cases, the assets are lost when the holder passes away.

=======

### How long will it take 
We will launch our unaudited beta of Alfred August 1 with a full release and Gnosis Safe integration targeted for October 1.

### How much funding are you requesting  
$17,500

### How did you hear about the GECO
Twitter

## Your Proposal 
### Project description
We began exploring these ideas at ETHDenver 2020 and continued our work through the MetaCartel Dragon Quest, securing bounties from Kyber and Gnosis along the way.

We've developed a minimalistic protocol for digital wallet recovery that can increase the likelihood a digital wallet holder will be able to recover their assets in the event they lose access to their primary wallet by forcing them to prove their ability to access their primary wallet at regular intervals.

Alfred is a proof-of-concept we've developed for using this protocol. Our goals are to promote adoption of this protocol and develop services that leverage the protocol to accommodate the needs of individuals and organizations maintaining custody of cryptocurrency and digital assets for various purposes. Some of these services may include:

- Helping individuals and organizations prevent the loss of digital wallets
- Helping individuals and organizations prepare for the death or incapacitation of loved ones or colleagues.
- Helping individuals and organizations share funds under various circumstances
- Helping fund managers design robust systems for maintaining custody of their own assets or advising clients on non-custodial management of their own assets.
- Helping businesses and non-profit organizations accept payments or donations of cryptocurrency.

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

### Team description
- Aaron Anderson brings dApps to market as a dApp engineer and cofounder of Web3Devs and Ching!
- Ken Hodler is a senior engineer, formerly CEO and an early contributor at Keepkey (exited to ShapeShift).
- Morgan Sherwood is a dApp engineer with 25+ year career as a Python developer and algorithmic trader skilled in smart contract security analysis.
- Seth Goldfarb is a marketing professional who helps companies tell better stories about the development of blockchain and its applications.

### Timeline, Milestones and Deliverables

**Phase I**

**Deliverables**
- Complete smart contracts and front-end
- Launch (unaudited) beta version for testing

**1 Month - $5000**	

**Phase II**

**Deliverables**
- Audit smart contract
- Consult legal counsel
- Interview users

**1 Months - $10000**

**Phase III**

**Deliverables**
- Iterate on UI
- Address concerns revealed in audit

**1 Month - $2500**
