---
order: 9
---

<!-- markdown-link-check-disable -->
# State of Cosmos Governance 2021

> Governance and decision-making processes within the Cosmos ecosystem as of August 2021. This particular document serves as a snapshot of the process at this moment in time and parts of it may be out of date or deprecated in the future.

## Cosmos View of Governance

The Cosmos ecosystem emphasizes governance mechanisms in order to achieve the vision of an ecosystem of interoperable blockchains supported by interchain infrastructure and services on the Cosmos Hub and beyond. The intent is that Cosmos Hub is operated by the community of code development teams supported by the Interchain Foundation, validators and ATOM token holders as a form of distributed organization.

Cosmos Hub has a [Governance (x/gov) module](https://docs.cosmos.network/main/modules/gov/) for coordinating various changes to the blockchain through parameters, upgrades and proposals (the [white paper](https://v1.cosmos.network/resources/whitepaper) refers to text amendments to the "human-readable constitution" setting out Cosmos Hub policies). However, the ecosystem also has additional on- and off- chain processes that exist to set technical direction and inculcate social norms.

Reviewing existing governance documentation and discussion, a few key themes surfaced:

### Emphasis on Self-governance and Sovereignty

On-chain governance standardizes forms of coordination but leaves many governance decisions to each application-specific blockchain or zone. Sunny Aggarwal [uses the analogy](https://blog.cosmos.network/deep-dive-how-will-ibc-create-value-for-the-cosmos-hub-eedefb83c7a0) that IBC as a form of standardization allows for "economic integration without political integration." Sunny also [talks about](https://www.youtube.com/watch?v=LApEkXJR_0M) how governance controlled by a community that shares culture and trust can "achieve greater security than economic incentives alone." For example, the Regen Network has a [governance model](https://medium.com/regen-network/community-stake-governance-model-b949bcb1eca3) that identifies multiple constituencies that require representation in governance. This allows diverse chains to exchange value while retaining the ability to self-govern. 

### Flexibility through On-chain Parameters

Each blockchain in the Cosmos ecosystem can be tailored to a specific application or use case, as opposed to building everything on top of a general purpose chain (and as a result without a Turing complete virtual machine like Ethereum's, for example). This approach provides flexibility through allowing stakeholders to vote on live parameter changes. In addition, Cosmos ecosystem teams are working on smart contract functionality. For example, the CosmWasm team have explored [permissioned smart contracts](https://medium.com/cosmwasm/cosmwasm-launches-its-permissioned-testnet-gaiaflex-e32635232026), where on-chain governance is required to approve instantiation of smart contracts.

### Development of Governance Processes Over Time

The existing [governance module](https://docs.cosmos.network/main/modules/gov/)  is described as a minimum viable product for the governance module, with [ideas for future improvement](https://docs.cosmos.network/main/modules/gov/05_future_improvements.html) . For example an active product team is currently aligning [groups and governance functionality](https://docs.google.com/document/d/1w-fwa8i8kkgirbn9DOFklHwcu9xO_IdbMN910ASr2oQ/edit#)  will change current governance practices and open up new avenues to explore and support through on- and off- chain processes


## On- and off-chain Governance Structure

### Communication

Governance practices and decisions are communicated through different types of documents and design artefacts:

- On-chain governance [proposals](https://cosmoscan.net/governance-stats)
- Decision records 
  - Cosmos Improvement Proposals ([CIPs](https://cips.cosmos.network/))
  - Cosmos SDK's [ADRs](https://docs.cosmos.network/main/architecture/)
  - Tendermint's [ADRs](https://github.com/tendermint/tendermint/tree/master/docs/architecture)
- Technical standards / specifications
  - Interchain Standard ([ICS](https://github.com/cosmos/ibc))
  - [RFCs](https://github.com/tendermint/spec/blob/master/rfc/README.md)
- [Opinion pieces](https://blog.cosmos.network/the-cosmos-hub-is-a-port-city-5b7f2d28debf)
- [Light papers](https://github.com/cosmos/gaia/issues/659)

### Decision-making and Discussion Venues

Venues involve community members to different degrees and individuals often perform multiple roles in the Cosmos ecosystem (e.g., Validator and member of Core Development Team). Because technical direction setting and development is almost always happening in the open, involvement from members in the extended community occurs organically.

[Working group](https://github.com/cosmos/cosmos-sdk/wiki/Architecture-Design-Process#working-groups) meetings and coordinating Cosmos stakeholders occurs in semi-/open online spaces:

- **[All in Bits Cosmos Forum](http://forum.cosmos.network/)**
  - For long form discussion. Cosmos core developers have an active presence (e.g., Ethan, Zaki, Sunny)
  - Cosmos Hub governance topics and proposals have a governance tag and usually get the most activity and substantive feedback, especially from validators (e.g., [direct conversations](https://forum.cosmos.network/t/proposal-are-validators-charging-0-commission-harmful-to-the-success-of-the-cosmos-hub/2505/8), ones that [spin out](https://forum.cosmos.network/t/on-the-interrelationship-between-the-security-budget-and-the-business-prospects-of-the-cosmos-network/2547) of proposals, and [meta discussions on process](https://forum.cosmos.network/t/streamline-the-gov-process/3997))
  - Developing and sharing of opinion pieces, light papers, hot takes etc., also happens on the forum (e.g., [Where I see the Cosmos at Present](https://forum.cosmos.network/t/where-i-see-cosmos-at-present/5022)) 
  - [Chinese language discussion](https://forum.cosmos.network/c/chinese/9) is one of the largest categories with 269 posts
  - There are still some old links to [Matrix chat](https://riot.im/app/#/room/#cosmos_validators:matrix.org), which has been deprecated 
- **[/r/cosmonetwork Subreddit](http://reddit.com/r/cosmosnetwork)**
  - Venue primarily for ATOM holders to discuss ATOM and other ecosystem coins
  - Discussion topics mostly about investing in the ecosystem and include: [investment theses](https://www.reddit.com/r/cosmosnetwork/comments/o38psh/i_think_atom_is_undervalued/), where to buy tokens, wallets to use, how to stake, and more recently, how to get involved with DeFi in the ecosystem (e.g., with Osmosis) 
  - Community managers use it for announcements (e.g., catdotfish)
- **[Cosmos Community Discord](https://discord.gg/W8trcGV)**
  - For ecosystem cross-pollination with an active developer presence. Older Riot chats have moved here. 
  - `#validator-verified` channel for example discussing proposals, upgrades etc.  
  - Major ecosystem chains all have a presence here, cross-validator convo, artefacts like: [Citadel.one Validator Constitution](https://drive.google.com/file/d/1wDTqro208y_1q3zF6rt39QjwYkcvVd7P/view) 
- **Cosmos Hub Discord (semi-private)**
  - For [core development teams](https://cosmos.network/learn/faq/who-is-building-cosmos/) to have multi-team discussions that are mature
  - Internal org channels (e.g., Interchain Slack) and slack-connect (private)
  - For internal team coordinating, 1-1s between specific core development teams, multi-team discussions that are early stage, have private or strategic team info too early to share out
- **[Telegram (Governance Working Group)](https://t.me/hubgov)**
  - For coordinating a working group that: "develops decentralized community governance efforts alongside the Hub's governance development."
  - Working Group came out of [a community pool proposal](https://www.figment.io/resources/introducing-the-cosmos-governance-working-group). 
  - Some interest in deprecating but remains actives
- **GitHub repositories** for governance processes ([Cosmos governance](https://github.com/cosmos/governance), [Cosmos cips](https://github.com/cosmos/cips), [Cosmos ibc](https://github.com/cosmos/ibc))
  - For discussing meta aspects of governance processes, discussion and development of specific off-chain design records and technical specs, and repository for on-chain proposals
  - The Cosmos governance repo is officially deprecated as of October 2021.
- **Bi-weekly Cosmos Gaia / ATOM sync call**
  - For cross-team discussion on the [Gaia roadmap](https://github.com/cosmos/gaia/projects/9)
- (Informal) **Google Docs for early feedback**
  - For individuals and collaborators to develop and iterative on governance ideas before proposing them formally
- **[Matrix chat](https://riot.im/app/#/room/#cosmos_validators:matrix.org)** (deprecated)

### Roles and Stakeholders

As mentioned above, stakeholders often perform multiple roles in the Cosmos ecosystem (e.g., both a Validator and member of the Core Development Team). As a result, visualizing the roles each stakeholder can take up in current governance can fail to reflex the overlapping roles. Within the ecosystem,  decision-making power and process "ownership" has been decentralized to an extent, reflecting system goals.

What roles can each stakeholder take up in current governance?

**Viewer (V)** - Able to easily review previous governance decisions, see current state of governance
**Active Participant (P)** - Regularly providing input or helping to move governance decisions forward, but does not drive them or necessarily initiate
**Governance Proposer (I)** - Initiates a proposal for updating Cosmos Hub governance
**Decision Maker (DM)** - Can vote or be part of the final governance decision
**Process Owner (PO)** - Owns the creation, refinement, and execution of the governance mechanism 

| **Role** | **Cosmos Hub <br /> On-chain** | **CIPs** | **Cosmos SDK <br /> ADRs** | **Tendermint <br /> RFCs** | **ICSs** |
|---|:-:|:-:|:-:|:-:|:-:|
| ATOM holders (retail and <br /> professional) | V |  |  |  |  |  |
| Hub Delegators  | DM |  |  |  |  |  |
| Hub Validators  | DM |  |  |  |  |  |
| Interchain Foundation team  | DM |  |  |  |  |  |
| Cosmos Core Development <br /> teams | PO | PO | DM | P | PO |
| Cosmos SDK Core Team    | DM  | DM  | PO  | P | DM  |
| Tendermint Developers   | DM  | DM  | DM  | PO | DM  |
| Cosmos Integrators (wallets, <br /> exchanges, services) | DM | P | ?  | ? | ? |
| Other zones and hubs members   | DM  | P?  | P?  | P?  | P?  |


#### Role Ability to Govern

What aspects of the Cosmos ecosystem does each role have the ability to govern? 

| **Role** | **Cosmos Hub  <br />  Blockchain  <br />  (through on-chain proposals)** | **Cosmos Hub  <br />  Community Pool (treasury)** | **Cosmos Hub On-chain  <br /> governance processes** | **Cosmos  <br /> Ecosystem Tech Decision Records, Specs, Standards Development** | **Cosmos Ecosystem  <br /> Off-chain governance processes** |
|---|:-:|:-:|:-:|:-:|:-:|
| ATOM holders (retail and  <br />  professional) | Must delegate ATOMs | Must delegate ATOMs | Must delegate ATOMs |  |  |
| Hub Delegators | ✔ | ✔ | ✔ |  |  |
| Hub Validators | ✔ | ✔ | ✔ |  |  |
| Interchain Foundation team |  | ✔ | ✔ |  | ✔ |
| Cosmos Core Development  <br />  teams |  |  | ✔ | ✔ | ✔ |
| Cosmos SDK Core Team |  |  |  | ✔ | ✔ |
| Tendermint Developers |  |  |  | ✔ | ✔ |
| Cosmos Integrators (wallets, <br />  exchanges, services) |  |  |  | ✔ |  |
| Other zones and hubs members |  |  | ✔ | ✔ | ✔ |

---

## Review of Governance processes

### Cosmos Hub on-chain governance

The Cosmos Hub has an on-chain governance mechanism, which allow ATOM token holders to:

#### Change module parameters

The Cosmos Hub is implemented modularly using the Cosmos SDK, where each module brings a different set of functions. Some modules have "governable" parameters, i.e., parameters that are alterable through on-chain "parameter change" governance proposals. Parameter change proposals allows token-holders to adjust the Cosmos Hub's functionality live on the blockchain, without the need for a new software release. It's interesting to note that parameters related to the governance module, i.e., x/gov module in the Cosmos SDK which implements the technical functionality of on-chain governance, is itself governable through parameter change proposals.

Example:  [Proposal 47](https://hubble.figment.io/cosmos/chains/cosmoshub-4/governance/proposals/47) asked to lower the minimum proposal deposit amount from 512 ATOMs to 64 ATOMs.

#### Pass text proposals

Text proposals are used by delegators to agree to a certain strategy, plan, commitment, future upgrade, or any other statement in the form of text. Aside from having a record of the proposal outcome on the Cosmos Hub chain, a text proposal has no direct effect on the change Cosmos Hub.

Example:  [Proposal 12](https://hubble.figment.io/cosmos/chains/cosmoshub-4/governance/proposals/12) asked if the Cosmos Hub community of validators charging 0% commission was harmful to the success of the Cosmos Hub?

#### Spend funds from the community pool

Cosmos Hub has a pool of ATOMs that can be spent through governance proposals. As of July 2nd, 2021 there are 645,961.01 ATOM in the community pool [according to cosmoscan](https://cosmoscan.net/).

Example: [Proposal 45](https://hubble.figment.io/cosmos/chains/cosmoshub-4/governance/proposals/45) asked to allow the spending of 5,000 ATOMS for the Gravity DEX Incentivized Testnet (Trading Competition) from the community pool.

#### Pass software upgrade proposals

A software upgrade proposal, when passed, will halt the chain until the node operator upgrades their software. If passed, the expectation is validators will update their software in accordance wi

Example: [Proposal 51](https://hubble.figment.io/cosmos/chains/cosmoshub-4/governance/proposals/51) asked to adopt the Gravity DEX protocol on Cosmos Hub.

### User Story: Chain-Wide Governance

_Reproduced from [Gov Use Cases](https://docs.google.com/document/d/1GJTTVlRU1qDzIbiwhRo-RVFq7pQ-BOjABgVpDdrpAAM/edit#heading=h.84b4lthf6mm)_

A community member, Alice, wants to submit an on-chain proposal to change a parameter, the average number of blocks per year, which is used to calculate the inflation rate for the chain. To do this Alice first asks in a chat forum discord for instance whether this is a good idea and something the community would like to see happen. There is some initial discussion to confirm that this is in fact something the community wants. Another community member, Bob, also offers to collaborate on the proposal.

Alice and Bob have a zoom call and start working in a google doc to draft the proposal synchronously, after which Alice finishes the draft and Bob reviews her work. Alice then opens a pull request on the governance repo that includes the text document as well as the json message required to make the parameter proposal on chain.

Alice solicits community feedback on the PR, sharing it to the Discord and among validators, and is asked to make some minor changes, which are completed before the PR is finalized and merged by the governance repo owner.

Once the proposal has been finalized an IPFS hash of the README.md is added to the json.

The proposal is then submitted on chain through the CLI and a Cosmos forum post is made to notify the community that the proposal has been submitted. Links to the forum post are then shared in various community channels and on twitter. The merits of the proposal are discussed in these respective channels and validators / ATOM holders vote.

| **Venues** | **1 <br /> Problem Identification** | **2 <br /> Problem validation and proposal development** | **3 <br /> Review, debating pros and cons** | **4 <br /> Incorporating feedback** | **5 <br /> Initiate process** | **6 <br /> Decision finalization and adoption** |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| Cosmos Hub Discord |   | ✔ |   |   | ✔ |   |
| Gaia call |   |   |   |   |   |   |
| Cosmos Gov GitHub Repo |   |   | ✔ | ✔ |   |   |
| Cosmos Hub Gov WG Telegram |   |   |   |   |   |   |
| Discourse forum |   |   | ✔ |   | ✔ |   |
| On chain vote |   |   |   |   |   | ✔ |
| Community Discord |   |   |   |   | ✔ |   |
| Twitter |   |   |   |   | ✔ |   |
| Other unofficial chat channels |   |   |   |   | ✔ |   |
| Subreddit |   |   |   |   | ✔ |   |

### Process overview

![Diagram of process for on-chain governance proposals](https://lh6.googleusercontent.com/FPQ176gx_-0jR5zbpImJtWx3iTnL-JJPc41hT4NUsNIYj5FziO6bsFWFn_CWV2ARr4vxm-HJi_3Fn4zowN1d2JuXB_CW2mTzJwn8L45mIPY0W_8sfjz3w3jeFr2q1NCcFVeRu7j_)

On-chain governance on the hub is implemented in Gaia using the x/gov module in the Cosmos SDK. Every bonded token is allowed a single vote.

Participants in the process include:

- The proposal creator: develops the proposal, solicits feedback, submits and socializes the on-chain proposal
- Validators: vote on behalf of delegators. Voting power of validators is equivalent to total ATOMS delegated to them. There are currently 125 active validators in the validator set, updated from 100 validators through governance [proposal #10](https://cosmoscan.net/proposal/10). 
- Delegators: can cast their own vote, otherwise they inherit the vote of their delegates

### Process owners

- Former process owners are listed in  the now-deprecated [governance repo](https://github.com/cosmos/governance).

### Process maturity

- 37 proposals that have been voted on so far. The latest proposal as of July 2nd, 2021 is proposal ID #51 (proposals that don't meet minimum deposit don't count towards the 37)
- [Cosmoscan's governance charts](https://cosmoscan.net/governance-charts) provide insight on turnout and voter activity. [Mintscan](https://www.mintscan.io/cosmos/proposals) can be used to fill in any gaps.


## Cosmos Improvement Proposals (CIPs)

CIPs serve as the process for describing major changes or providing info about the protocol and APIs or processes of the Cosmos ecosystem.

"The CIP process draws heavily from Ethereum's EIP process and Rust's RFC process. It pertains primarily to the protocol and APIs of the Cosmos Hub blockchain (Cosmos, for short), including Tendermint, Cosmos-SDK, IBC, and other modules. A CIP is a design document providing information to the Cosmos community, or describing a new feature or major change for Cosmos or its processes or environment."

"This CIP process aims to subsume, but not necessarily to replace" the RFC and ADR processes.
🔗 <https://github.com/cosmos/cips/blob/main/CIPS/cip-1.md>

### User Story: Governing Technical Direction 

Alice, a member of one core development team, submits a PR to the Cosmos cips repo after a recurring issue is identified in the standing GAIA / ATOM call. There has been a recurring discussion about how to formalize emerging agreement on a distinctive Cosmos interpretation of a technical feature common to blockchains. There are existing prior specifications in the bitcoin ecosystem that were the direct inspiration for Cosmos development, but over time the core development teams have developed a contrasting understanding of how their implementation provides a pathway to future specification development. At the end of last call, Alice decides this was important enough to step forward and take a first pass at drafting the spec based on the current roadmap.

Alice follows the template from the repo to draft an early CIP and updates the frontmatter of the file to indicate the status is "draft." Once the PR is submitted, Alice pings a few developers who mentioned they would provide feedback in Discord and Slack bridge channels. The developers review the PR and leave inline comments and suggestions. Alice incorporates this feedback and requests the CIP be discussed at the next GAIA / ATOM call. In the meantime, Alice solicits community feedback on the PR, sharing it to the Cosmos Hub Discord and a relevant Slack connect channel. Once again Alice is asked to make minor changes, which are completed before the PR is finalized, the cip status is updated to "living" and it is merged by the cips repo owner.


### Process overview

![Diagram of standarization process for CIPS](https://github.com/cosmos/cips/raw/main/assets/cip-1/CIP-process.png)

- Ideas are ideally socialized first: "It is thus recommended to open a discussion thread on the Cosmos forum to do this, but you can also use the Cosmos Discord, the Cosmos subreddit or the Issues section of this repository." If the author decides to proceed, CIPs are drafted and submitted using the [cosmos/cips](https://github.com/cosmos/cips/) GitHub repo.
- When a CIP reaches the "Final" state, it represents a completed standard that is ready to be adopted.
- CIPs do not represent the views of the wider Cosmos community. CIP-1 states that "finalization of a CIP does not equate to acceptance into Cosmos. For that, CIP authors must turn to Cosmos Governance." 
- Not all CIPS are taken through an on-chain vote
- A situation where CIPs interact with Cosmos Governance is while coordinating a software upgrade among validators. [CIP-5](https://github.com/cosmos/cips/blob/17a9ffc1cc40933ea3cf4460849ae713e6c244e3/CIPS/cip-5.md) [PR not merged], which offers guidelines for new modules to be integrated into Cosmos Hub ensuring safety and robustness, states "motivated by decentralization and the Cosmos community's decisions, a module's code is activated by submitting a parameter change proposal."
  


### Process owners

CIP editor: Ethan Buchman ([@ebuchman](https://github.com/ebuchman))

### Process maturity

- There are 12 CIPs proposed to date, none are living, have been finalized, or taken through the on-chain governance process to be widely adopted.


## Cosmos SDK Architecture Decision Records (ADR)

ADRs serve as the main way to propose new feature designs, new processes, and to document design decisions for the Cosmos SDK.

"An Architectural Decision (AD) is a software design choice that addresses a functional or non-functional requirement that is architecturally significant. An Architecturally Significant Requirement (ASR) is a requirement that has a measurable effect on a software system's architecture and quality. An Architectural Decision Record (ADR) captures a single AD, such as often done when writing personal notes or meeting minutes; the collection of ADRs created and maintained in a project constitute its decision log."

🔗 <https://docs.cosmos.network/main/architecture/>

### Process overview

- Ideas are socialized on GitHub first: "Every proposal SHOULD start with a new GitHub Issue or be a result of existing Issues. The Issue should contain just a brief proposal summary. Once the motivation is validated, a GitHub Pull Request (PR) is created" 
- If the author decides to proceed, ADRs are drafted and submitted using the [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk/tree/master/docs/architecture) GitHub repo.
  1.  Copy the adr-template.md file. Use the following filename pattern: adr-next_number-title.md
  1.  Create a draft Pull Request if you want to get an early feedback.
  1.  Make sure the context and a solution is clear and well documented.
  1.  Add an entry to a list in the [README](https://docs.cosmos.network/main/architecture/) file.
  1.  Create a Pull Request to propose a new ADR.
  `<https://docs.cosmos.network/main/architecture/PROCESS.html>`
- ADRs go through a lifecycle: <https://docs.cosmos.network/main/architecture/PROCESS.html#adr-life-cycle>
```
DRAFT -> PROPOSED -> LAST CALL yyyy-mm-dd -> ACCEPTED | REJECTED -> SUPERSEEDED by ADR-xxx

                  \        |

                   \       |

                    v      v

                     ABANDONED
```

### Process owners

- SDK [codeowners](https://github.com/cosmos/cosmos-sdk/blob/master/.github/CODEOWNERS):  Aaron Craelius ([@aaronc](https://github.com/aaronc)) and Aleksandr Bezobchuk ([@alexanderbez](https://github.com/alexanderbez))

### Process maturity

- A bunch have passed, many are proposed: <https://github.com/cosmos/cosmos-sdk/tree/master/docs/architecture>


## Tendermint Request for Comments (RFC)

RFCs are ways to both investigate and develop an idea prior to formalizing for inclusion in the Tendermint Spec, they also describe proposals to change the spec.

"RFC stands for Request for Comments. It is a social device use to float and polish an idea prior to the inclusion into an existing or new spec/paper/research topic. RFC stands for Request for Comments. It is a social device use to float and polish an idea prior to the inclusion into an existing or new spec/paper/research topic."
🔗 <https://github.com/tendermint/spec/blob/master/rfc/README.md>

"As part of our 1.0 push, we'll determine if gRPC is the right framework for our RPC layer; and if so, we'll implement it. This work will begin with an RFC, and we'll seek further input from community members and users. If this RFC is accepted, we'll write a transition plan for the RPC layer and execute it."
🔗 <https://medium.com/tendermint/towards-tendermint-core-1-0-3a71b6ce73a3>

### Process overview

- Not publicly documented

### Process owners

- Specification [general codeowners](https://github.com/tendermint/spec/blob/master/.github/CODEOWNERS): Zarko Milosevic ([@milosevic](https://github.com/milosevic)), Ethan Buchman ([@ebuchman](https://github.com/ebuchman)), Josef Widder ([@josef-widder](https://github.com/josef-widder)), Igor Konnov ([@konnov](https://github.com/konnov))

### Process maturity

- 5 RFCs have been merged to the repo with an active pull request for adding one more


## Interchain Standards (ICS) 

ICSs are standards that document a particular protocol, standard, or feature of use to the Cosmos Ecosystem.

"Interchain Standards (ICS) for the Cosmos network & interchain ecosystem."
🔗 <https://github.com/cosmos/ibc>

"An inter-chain standard (ICS) is a design document describing a particular protocol, standard, or feature expected to be of use to the Cosmos ecosystem. An ICS should list the desired properties of the standard, explain the design rationale, and provide a concise but comprehensive technical specification. The primary ICS author is responsible for pushing the proposal through the standardisation process, soliciting input and support from the community, and communicating with relevant stakeholders to ensure (social) consensus."
🔗 <https://github.com/cosmos/ibc/blob/master/spec/ics-001-ics-standard/README.md>

### Process overview

- Unclear where early discussions would happen
- ICSs are drafted and submitted using the [cosmos/ibc](https://github.com/cosmos/ibc) GitHub repo:
- To propose a new standard, [open an issue](https://github.com/cosmos/ics/issues/new).
- To start a new standardisation document, copy the [template](https://github.com/cosmos/ibc/blob/master/spec/ics-template.md) and open a PR.
- Standardization process has 4 phases, laid out in [PROCESS.md](https://github.com/cosmos/ibc/blob/master/meta/PROCESS.md) for a description of the standardisation process.
  - Stage 1 - Strawman. Start the specification process
  - Stage 2 - Draft. Make the case for the addition of this specification to the IBC ecosystem, describe the shape of a potential solution, and Identify challenges to this proposal.
  - Stage 3 - Candidate. Indicate that further refinement will require feedback from implementations and users
  - Stage 4 - Finalised. Indicate that the addition is included in the formal ICS standard set

### Process owners

- IBC [Standards Committee](https://github.com/cosmos/ibc/blob/master/meta/STANDARDS_COMMITTEE.md): Aditya Sripal ([@adityasripal](https://github.com/adityasripal)), Christopher Goes ([@cwgoes](https://github.com/cwgoes)), Zarko Milosevic ([@milosevic](https://github.com/milosevic))

### Process maturity

- 16 have been merged into the repo with at least one more under active discussion: <https://github.com/cosmos/ibc>


---

## Observations and Discussion

This report provides a descriptive account of the existing governance documentation and a snapshot of existing processes. Future work can probe specific questions and assumptions (e.g., if the goals to distribute decision-making or ensure a degree of sovereignty for zones are met) and focus on process refinement and [maturity](https://docs.google.com/document/d/1k2dxvd9IQF5WKXn67656bRloBtgdOWJ4mJ29m_qstPo/edit#heading=h.m8lb7fphmit0).

### On-chain processes

- UX limits who can create and vote for proposals, currently requiring the use of the CLI. If Cosmos Hub sees [itself as a port city](https://blog.cosmos.network/the-cosmos-hub-is-a-port-city-5b7f2d28debf), offering the best possible services, there is an argument to be made that it should extend that commitment to governance to ensure a diverse range of city dwellers and visitors can participate.
- Some validators feel that active participation in governance is a bottleneck to setting up validator businesses. I.e., that there are already a number of proposals they are asked to vote on.
- Cosmos Hub governance documentation is out of date, challenging to maintain, and difficult to discover. Current governance documentation is in the [`governance` repo as markdown](https://github.com/cosmos/governance), the [`gaia` documentation as vuepress](https://hub.cosmos.network/main/), and [`cosmos-sdk` documentation as vuepress](https://docs.cosmos.network/).
-   Assessing this and making improvements is work that Hypha is currently undertaking, but there can be ongoing improvements
- The [upcoming x/gov and x/group alignment](https://docs.google.com/document/d/1w-fwa8i8kkgirbn9DOFklHwcu9xO_IdbMN910ASr2oQ/edit#) will allow for permissions related to governance to be delegated to other groups, opening up possibilities for multi-stakeholder governance approaches and products (see [related links](https://linktr.ee/cosmos_gov)).

### Off-chain processes

- More clarity is needed on when the CIPs should be used. It could be seen as the canonical home for high level decisions where alignment is required across the ecosystem but needs to be presented as such and the process needs refinement
- Some CIPS clearly impact all Cosmos ecosystem and blockchains and need ecosystem-wide buy-in, for example [CIP-11: Cosmos Hierarchical Deterministic key derivation](https://github.com/cosmos/cips/pull/11).
- ["RFC Interchain Staking Light Paper"](https://github.com/cosmos/gaia/issues/659) an example of a potential CIP that was PRd to the Gaia repo. The ambiguity makes sense: it fits criteria of informational CIP about the Cosmos environment (Light Paper), but also a shorter and higher level document is needed to function as more of a summary in order to get early user feedback and market ideas that isn't a CIP <https://github.com/cosmos/gaia/issues/659>
- The terms "Cosmos" and "Cosmos Hub" are used interchangeably in the CIPs repository, so the intended audience could be made more clear. The [module readiness process and checklist](https://github.com/cosmos/cips/pull/6/files), which proposes a process for modules to be adopted by the Gaia team, suggests that the process is intended for teams involved in development related to the Cosmos Hub.
- Tendermint has an [ADR process](https://github.com/tendermint/tendermint/tree/master/docs/architecture) as well. Documentation around the relationship between the Tendermint ADR and the RFC processes would be valuable.

<!-- markdown-link-check-enable -->
