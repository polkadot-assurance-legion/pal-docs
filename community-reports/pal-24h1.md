# PAL Community Report for 2024 H1
Date: 31.07.2024

This Community report summarizes the activity of the Polkadot Assurance Legion (PAL) during the first six months of 2024. PAL is a community-driven initiative that aims to make Polkadot a safer and more attractive place for both builders and users by allocating funds from the Polkadot treasury (bounty #22) to advance security in Rust / Polkadot SDK.

## Summary
In H1 2024, PAL focused exclusively on Rust audits in the Polkadot ecosystem. Any parachain team covering the [eligibility criteria](https://github.com/polkadot-assurance-legion/pal-docs/blob/main/applications_criteria.md) was welcome to apply for partial funding of their audits: Covering up to 80% of the applicants' costs, with a hard cap of 18,000 DOT.

The audits were carried out by a curated pool of auditors. To facilitate this, PAL onboarded [15 auditing organizations](https://github.com/polkadot-assurance-legion/pal-docs/blob/main/auditors.md), which are among the leaders in the Web3 security space. This includes both traditional auditors and 3 platforms for crowdsourced audits.

In total, PAL has paid out 157,155 DOT after approving 14 audit applications by 11 parachain teams, helping secure a total of 175,000+ Lines of Code (LOC).

The audits that were carried out helped identify at least 18 Critical or High-risk vulnerabilities, which, in many cases, could have led to the loss of user funds. A further 18 Medium-risk and 49 Low-risk vulnerabilities were reported. For more information, see the breakdown at the end of this report, which also includes references to the individual audit reports.

At the end of H1 2024, the PAL Treasury bounty #22 had 382,845 DOT remaining, which is 70% of the original amount that was reserved (540,000 DOT).

For H2 2024 and beyond, PAL is planning to expand its scope to address the following challenges:
* Include other consumers of coretime than just parachains;
* Include specific audits of the Polkadot relay chain and/or system chains (within limits);
* Cover Solidity audits (under some strict conditions);
* Go beyond audits and start providing funding for security tooling or other security practices beneficial to the Polkadot ecosystem at the discretion of the bounty curators.

PAL will submit a new OpenGov referendum in the upcoming weeks to effectuate this expansion in its scope.

## Audits Overview
