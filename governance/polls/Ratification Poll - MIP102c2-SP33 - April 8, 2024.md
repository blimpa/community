---
title: Ratification Poll for MIP Amendment Subproposal (MIP102c2-SP33) - April 8, 2024
summary: This subproposal seeks to amend MIP16 to accomodate the transition from the Goerli Testnet network to different testing tools, among other updates.
discussion_link: https://forum.makerdao.com/t/mip102c2-sp33-mip102-amendment/23792
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 10000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-04-08T16:00:00
end_date: 2024-04-11T16:00:00
---
# Ratification Poll for MIP Amendment Subproposal (MIP102c2-SP33) - April 8, 2024

The Governance Facilitators have placed a ratification poll into the [voting system](https://vote.makerdao.com/polling) as part of the responsibilities defined in [MIP51](https://mips.makerdao.com/mips/details/MIP51). This Governance [Poll](https://manual.makerdao.com/governance/governance-cycle/weekly-governance-cycle#weekly-governance-cycle-definitions-mip16c1) will be active for fourteen days beginning on Monday, April 8 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to MIP102c2-SP33 being accepted and implemented in the Maker Protocol.

A brief summary of this proposal has been provided by the MIP Author and is shown below:

*The Governance Facilitator teams have observed a rising number of proposals containing logic intended to block other proposals editing the same section of a MIP or Scope Artifact (Example 1, Example 2) within the same Governance Cycle. This type of blocking language undermines effective governance by preventing voters from selecting their preferred option in the event that there are opposing amendments. Simultaneously, there is a risk of a stalemate situation where two or more proposals seeking to edit the same component contain such blocking language, making it logically impossible for either to be ratified.*

*This proposal introduces language that will:*

- *Ban the use of such blocking language in MIP102c2 subproposals.*
- *Authorize Governance Facilitators to streamline and merge non-conflicting proposals editing the same component.*
  - *For example, simultaneous subproposals may edit the same component in ways that do not conflict. These scenarios could be easily solved by combining the logic of both proposals, or by changing numbering without the need for further governance overhead.*
- *Specify a polling process to decide the preferred option of voters in the event two conflicting proposals pass within the same Governance Cycle.
Please review the links below to inform your position on this proposal before voting.*

- [Canonical Proposal Version](https://github.com/makerdao/mips/blob/f9aa8d1eb400f011f4194d80a2e01320bc9bbb10/MIP102/MIP102c2-Subproposals/MIP102c2-SP33.md)
- [Latest Proposal Version](https://mips.makerdao.com/mips/details/MIP102c2SP33)
- [Proposal Discussion Thread](https://forum.makerdao.com/t/mip102c2-sp33-mip102-amendment/23792)
- [Amendment Pull Request](https://github.com/makerdao/mips/pull/1064)

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation is currently set to **10,000 MKR**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option exceed 10,000 MKR, then the following actions will be taken:**
- The Governance Facilitators will confirm its passage by marking the proposal **Accepted** on the [MIPs portal](https://mips.makerdao.com/mips/list) and across all other relevant governance mediums.
- Any further work required to implement the proposal will be tasked to the relevant [Ecosystem Actors](https://mips.makerdao.com/mips/details/MIP101#7-professional-actors).

**Otherwise, this proposal will be marked as rejected per [MIP51](https://mips.makerdao.com/mips/details/MIP51#mip51c2-ratification-poll).**

---

## Resources

[MIP51: Monthly Governance Cycle](https://mips.makerdao.com/mips/details/MIP51) describes this type of poll and its position and significance within the rest of the governance cycle.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
