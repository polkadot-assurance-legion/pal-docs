# PAL Community Report 2024 H1
Date: 26.07.2024

This Community report summarizes the activity of the Polkadot Assurance Legion (PAL) during the first six months of 2024. PAL is a community-driven initiative that aims to make Polkadot a safer and more attractive place for both builders and users by allocating funds from the Polkadot treasury (bounty #22) to advance security in Rust / Polkadot SDK.

## Summary
![PAL Community Report 2024 H1](./pal-24h1.jpeg)

The focus of PAL in 2024 H1 was exclusively on Rust audits in the Polkadot ecosystem. Any parachain team covering the [eligibility criteria](https://github.com/polkadot-assurance-legion/pal-docs/blob/main/applications_criteria.md) was welcome to apply for partial funding of their audits: Covering up to 80% of the applicants' costs, with a hard cap of 18,000 DOT.

The audits were carried out by a curated pool of auditors. To facilitate this, PAL onboarded [15 auditing organizations](https://github.com/polkadot-assurance-legion/pal-docs/blob/main/auditors.md), which are among the leaders in the Web3 security space. This includes both traditional auditors and 3 platforms for crowdsourced audits.

In 2024 H1, PAL has paid out 157,155 DOT to co-fund [14 Rust audits](/audits/24h1/) of 11 parachain teams, helping secure a total of 175,000+ Lines of Code (LOC).

The audits that were carried out helped identify at least **18 High-risk vulnerabilities**, which, in many cases, could have led to the loss of user funds. A further **28 Medium-risk** and **49 Low-risk vulnerabilities** were reported. For more information, see the breakdown at the end of this report, which also includes references to the individual audit reports.

At the end of H1 2024, the PAL Treasury bounty #22 had 382,845 DOT remaining, which is 70% of the original amount that was reserved (540,000 DOT).

For H2 2024 and beyond, PAL is planning to expand its scope to address the following challenges:
* Include other consumers of coretime than just parachains;
* Include specific audits of the Polkadot relay chain and/or system chains (within limits);
* Cover Solidity audits (under some strict conditions);
* Go beyond audits and start providing funding for security tooling or other security practices beneficial to the Polkadot ecosystem at the discretion of the bounty curators.

PAL will submit a new OpenGov referendum in the upcoming weeks to effectuate this expansion in its scope.

## Overview
| ID   | Audit                | Co-funded  | LOC    | High | Med  | Low  | Report                                            |
|------|----------------------|------------|--------|------|------| ---- | --------------------------------------------------|
| 560  | phala-c4-2401        | 9,379 DOT  | 2,391  | 0    | 4    | 7    | [report](../audits/24h1/phala-c4-2401.pdf)        |
| 561  | acala-c4-2401        | 5,876 DOT  | 1,135  | 3    | 4    | 7    | [report](../audits/24h1/acala-c4-2401.pdf)        |
| 581  | t3rn-srl-2401        | 18,000 DOT | 74,368 | 5    | 3    | 1    | [report](../audits/24h1/t3rn-srl-2401.pdf)        |
| 583  | hydradx-c4-2401      | 15,335 DOT | 5,980  | 1    | 10   | 18   | [report](../audits/24h1/hydradx-c4-2401.pdf)      |
| 594  | bifrost-oak-2401     | 4,738 DOT  | 3,569  | 1    | 0    | 9    | [report](../audits/24h1/bifrost-oak-2401.pdf)     |
| 595  | astar-srl-2401       | 6,694 DOT  | 5,427  | 2    | 1    | 1    | [report](../audits/24h1/astar-srl-2401.pdf)       |
| 634  | astar-zellic-2401    | 988 DOT    | 251    | 0    | 0    | 1    | [report](../audits/24h1/astar-zellic-2401.pdf)    |
| 709  | invarch-srl-2402*    | 15,726 DOT | 5,442  | N/A* | N/A* | N/A* | N/A*                                              |
| 710  | moonbeam-srl-2401*   | 18,000 DOT | N/A*   | N/A* | N/A* | N/A* | N/A*                                              |
| 727  | peaq-srl-2402*       | 18,000 DOT | 54,391 | N/A* | N/A* | N/A* | N/A*                                              |
| 981  | astar-srl-2403       | 1,057 DOT  | 130    | 0    | 0    | 1    | [report](../audits/24h1/astar-srl-2403.pdf)       |
| 1310 | hydradx-srl-2405     | 1,620 DOT  | 1,012  | 0    | 1    | 0    | [report](../audits/24h1/hydradx-srl-2405.pdf)     |
| 1311 | hyperbridge-srl-2405 | 18,000 DOT | 14,300 | 7    | 4    | 4    | [report](../audits/24h1/hyperbridge-srl-2405.pdf) |

Audits marked with `*` are still ongoing, once finalized they will be included in this report.  

The PAL curators have received 2,742 DOT in curator fees in relation to these audits.

A further 3,000 DOT was allocated for travel expenses by curators. Out of this, 1,190 DOT has been spent.
