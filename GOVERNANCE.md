# Governance Proposal

[Home](README.md) · [Design](DESIGN.md) · [Participation](CONTRIBUTING.md)

Version 0.1 · 16 October 2026. This is a proposal for communities formed from forks. No voting service, elected body, enforcement mechanism, or automatic merging is operating in this seed.

## Put the future in the participants' hands

A project that asks powerful institutions to make their evidence inspectable should make its own decisions inspectable too. People who contribute their time, knowledge, and care deserve to know how priorities are chosen, how authority is exercised, and how it can be challenged.

The invitation is to build a community whose direction belongs to its participants. Publish the rules. Show who holds the keys. Preserve disagreement. Give the next generation a way to continue the work without waiting for a founder's permission. The proposal below offers a starting point for that shared responsibility.

## Publication and departure

The initiator publishes the vision and initial design, then stops participating in management. The original repository is intentionally unmaintained: no review, moderation, transfer, successor selection, service operation, or financial support is promised. The initiator may retain the account-level ownership that GitHub requires; that technical fact does not create a promise to act on community requests. Silence must never be treated as approval.

Anyone may reuse the original documents under their license and organize a fork without requesting permission. A fork should identify its own custodians and state clearly that it is an independent community, with no automatic exclusive succession or endorsement. Multiple communities may coexist, collaborate, disagree, or develop different designs. None can bind another without its explicit agreement.

## Establishing a working community

Publish a founding notice in the fork identifying its scope, founding participants, provisional custodians, decision location, and an adoption procedure for a charter. Until a working voting system and a sufficiently broad electorate exist, disclose the provisional process and the people exercising control. Do not present a few technical accounts as an already decentralized institution.

For an organization-owned fork, at least two consenting people should hold the GitHub Owner role for continuity. GitHub does not provide ownerless organizations or enforce a constitutional multi-signature rule on Owners: they retain administrative powers. Reduce dependence on them through public decisions, minimal routine permissions, term limits, access reviews, mirrors, and the ability to fork again.

## Roles and authority

Anyone can propose ideas, question evidence, report errors, and submit changes to a maintained fork. Voting eligibility need not confer repository write access. Elected custodians execute recorded decisions, maintain access and security, and publish administrative actions. Method reviewers evaluate evidence against public standards and disclose conflicts of interest. They must explain a rejection with reasons that can be challenged.

Votes decide priorities, governance, resources, and proposed changes. Votes do not make an empirical claim true. A supported counterexample remains relevant even when its author loses a vote. Preserve minority opinions, correction requests, source responses, and the history of revised findings.

## Suggested voting rules to adopt or revise

Use an explicit voter register, stable numeric GitHub account identifiers, and one vote per eligible participant. As an initial proposal, require accounts at least 90 days old, project participation spanning at least 30 days, and public review of eligibility. These measures raise the cost of abuse; they do not establish one human per account or prevent coordinated capture. Publish admission evidence without requiring public real identities, allow appeals, and explain how linked or compromised accounts are handled.

Freeze the eligible electorate at the start of each ballot, excluding bots and the author of the change from that ballot. Publish the proposal version and, for a code change, the exact head and base commits; bind the vote to the charter and electorate versions too. Material changes invalidate the ballot and require a fresh one. Register changes take effect only in a later voting period. Likes, stars, followers, and emoji totals are not ballots.

| Decision | Voting period | Participation | Minimum yes/no votes | Approval among yes/no votes | Cooling-off period |
| --- | --- | --- | --- | --- | --- |
| Ordinary proposal or change | 7 days | At least 60% of eligible voters and at least 5 participants | 5 | At least two thirds | 24 hours |
| Charter, control, security-sensitive access, or major resource commitment | 14 days | At least 70% of eligible voters and at least 10 participants | 10 | At least 80% | 48 hours |

Round required participant counts upward. Abstentions count toward participation but not the approval fraction or minimum yes/no votes. Missing quorum means no approval; do not quietly lower the threshold. If the community is too small, remain in an explicitly provisional phase or publicly adopt a different charter before using it. Record deadlines in UTC, an accountable tally, vote changes, conflicts, and the result. A community must specify ballot authentication, editing, deletion, closing, challenge, and appeal procedures before relying on the table.

## Reviews, security, and future automation

An approved change still requires the checks and independent review specified by the adopted charter. Security reviewers may pause a change for a documented technical reason, subject to appeal; this is not a personal policy veto. Emergency containment should be narrow, logged, and time-limited, with review by other custodians and a subsequent public account that protects sensitive details.

If participants later build automation, separate public contribution tests from privileged tallying and merging. Verify actual success, exact versions, trusted check provenance, and all required reviews immediately before merging. Account for changes to the base branch and serialize conflicting operations. Keep credentials away from untrusted changes. A same-named CI job or a vote-count comment is not a trusted authorization. Enabling such automation is a future project requiring its own review, not a feature of this publication.

## Languages and resources

English is this seed's reference text. A maintained community should publish its own language and translation policy, preserve meaningful dissent across languages, and make charter changes accessible before a vote. No participant has a duty to donate money, credentials, compute, or labour. Funding and affiliations must be disclosed and must not purchase extra votes. New financial obligations require explicit acceptance by the people or entity bearing them.

## A charter becomes real through people

These words acquire practical meaning when people adopt them, take responsibility for their powers, and remain answerable to one another. Fork the seed, discuss what your community can honestly sustain, and shape a charter you are prepared to uphold. The work belongs with those willing to carry it forward.

## GitHub references

- [Maintaining ownership continuity](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/maintaining-ownership-continuity-for-your-organization)
- [Contributing through forks](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)
- [Rules available for rulesets](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/available-rules-for-rulesets)
