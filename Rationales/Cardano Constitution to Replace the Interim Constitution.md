# Governance Vote Rationale – Cardano Constitution to Replace the Interim Constitution

**Proposal Details**
- Proposal ID: gov_action133jnaewfsq8x6v08ndd87l2yqryp63r30t2dkceacxx5cply5n7sqzlcyqf
- Summary: This Cardano Constitution is proposed to replace the Interim Constitution. The Cardano Constitution is the result of extensive Cardano community consultation throughout 2024. The Interim Constitution was intended to be temporary, and its Appendix II: Ratification of Final Constitution required its replacement to be submitted on-chain no later than January 31, 2025.

## Vote Decision: NO

## **Rationale**

Since the inception of the CIP-1694 workshops, which introduced the Cardano on-chain governance model, little to no research has been conducted to ensure that the governance structure maintains both the integrity and decentralization of the system. This issue persisted throughout the drafting of the constitution across more than 50 different countries.

As participants in this process, we observed that discussions were often guided toward a predetermined outcome, limiting the scope of debate. For example, during our own workshop, discussions were restricted to only three facilitator-chosen questions—this was a pattern across all workshops. The claim that all articles of the constitution had “global consensus” is therefore misleading.

The process culminated at the Constitutional Convention in Argentina in December 2024, where we were present. While some improvements were made—particularly regarding treasury management—the event felt more like a formality than a substantive governance exercise. Critical issues, such as the preamble and key structural safeguards, were not adequately addressed.

## Why the Constitution Is Not Ready for On-Chain Implementation

### Definition of ADA Owner
The constitution defines an ADA holder as someone who either holds their private keys or entrusts them to a third-party custodian. However, it does not emphasize self-custody as a core principle. Given Cardano's proof-of-stake model and its 1 ADA = 1 vote governance mechanism, this presents a significant risk.

Article III, Section 3 states:
> "Owners of ADA who use third-party custodians or other designees to hold their ADA may authorize or may withhold authorization for such third parties to vote on their behalf."

This provision does not mandate custodians to implement voting delegation, meaning major exchanges like Coinbase and Binance could effectively consolidate disproportionate governance power, endangering Cardano’s decentralization.

### Separation of Powers
The constitution states that governance should be maintained through three independent entities: **Delegated Representatives (DReps), Stake Pool Operators (SPOs), and the Constitutional Committee (CC).** However, the current framework allows individuals to serve in multiple roles simultaneously, undermining the intended system of checks and balances.

Article III, Section 2 states:
> "Three independent governance bodies shall participate in voting for on-chain governance actions to provide checks and balances for the Cardano Blockchain, consisting of Delegated Representatives (DReps), Stake Pool Operators (SPOs), and the Constitutional Committee (CC)."

Without a clear mechanism to prevent consolidation of roles, this system remains vulnerable to individuals or entities accumulating excessive influence. The constitution relies on "social contracts" to prevent this, assuming that the community will call out bad actors. However, without enforceable safeguards, this approach is insufficient.

### Definitions and Their Control
During the Constitutional Convention, definitions were heavily debated, yet they were ultimately placed into a separate, **non-binding** document. This means the Constitutional Committee may use them for interpretation—but is not required to.

By allowing definitions to be changed without going through the full constitutional amendment process, governance risks being controlled behind closed doors at **Intersect**. Whoever controls the definitions ultimately controls the interpretation of governance itself.

### DRep and CC Compensation
Article V, Section 5 states:
> "DReps who are representing delegators may be compensated for their efforts. DReps shall ensure that any compensation received in connection with their activities as a DRep is disclosed."

The use of the word **"may"** leaves compensation ambiguous. Furthermore, as of February 2025, **Intersect** has taken responsibility for DRep and CC compensation within its own budget. This creates a major **conflict of interest**, as DReps vote on treasury withdrawals. Any compensation mechanism should be direct, **through protocol-level rewards**, similar to how SPOs receive staking incentives, rather than through an intermediary entity.

### Net Change Limit (NCL) Vulnerability
The constitution lacks safeguards against treasury depletion. A proposer with enough influence could set the **net change limit (NCL)** to 100% of the treasury and approve a full withdrawal.

Instead of being set arbitrarily, the **NCL should follow a predefined formula** based on annual inflows, inflation, and a percentage cap that ensures sustainable fund allocation.

### Undefined "Administrator" Role
The constitution introduces the concept of **Cardano Administrators** who receive direct funding from the treasury, yet it does not define what qualifies as an administrator or how one attains this designation. This lack of clarity could lead to **centralized control** over funding distribution.

Treasury allocations should be transparently accessible to all projects **without requiring administrative gatekeeping** from centralized entities like **Intersect**.

### Conflicting Governance Rules on Info Actions
Article III, Section 4 states that **Info actions** are non-binding, yet Article VII, Section 4 suggests that they are required for budgeting and treasury withdrawals.

This contradiction was acknowledged at the Constitutional Convention but was deferred to a "future workstream" without resolution. While this is not an immediate governance crisis, it **reflects a lack of foresight in the governance design process**.

### Third-Party Voting Risks
Allowing third-party custodians such as centralized exchanges (CEXs) and decentralized exchanges (DEXs) to vote on behalf of ADA holders significantly **undermines democratic governance**. This issue, as previously noted, relates to the **ADA ownership definition** and remains unresolved.

### Treasury Auditor Independence
Article IV, Section 4 mandates audits for treasury-funded actions but contains a **major loophole**: administrators may influence the **selection of auditors**, creating potential conflicts of interest.

To ensure integrity, **the community—not the administrator receiving funds—must have the authority to select treasury auditors**.

### Liability Protections for DReps and CC Members
The constitution **does not** provide legal or security protections for DReps and Constitutional Committee members, despite requiring public transparency in their decision-making. Without a liability clause, participants in governance may be subject to **external legal risks**.

### The Preamble Lacks a Clear Vision
The **preamble** of the constitution lacks any **inspirational messaging** or core values that reinforce Cardano’s guiding principles. Absent are references to:
- Peer-reviewed research
- Striving for decentralization
- Promoting self-sovereignty

These elements should be present in any foundational document that seeks to define the future of the ecosystem.

## Conclusion
While the governance process has made notable progress, the current version of the Cardano Constitution is **not yet ready for on-chain implementation**. It introduces significant risks, including **centralization of power, lack of treasury safeguards, and unresolved conflicts of interest**.

As **Cardano Ethical Oversight**, our role is to critically evaluate governance structures to ensure they align with **the decentralized ethos of Cardano**. At this stage, we believe additional refinements and transparency mechanisms are necessary before this constitution can be considered a viable foundation for governance.

We urge the community to **continue refining governance proposals**, ensure **true decentralization**, and establish **protocol-level protections** that prevent **any single entity from exerting undue control over the system**.

**Proposal Link: https://adastat.net/governances/8c653ee5c9800e6d31e79b5a7f7d4400c81d44717ad4db633dc18d4c07e4a4fd00**

