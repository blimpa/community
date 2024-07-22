---
title: Template - [Executive Vote] LITE-PSM-USDC-A Phase 1 Setup, Spark Proxy Spell - July 25, 2024
summary: Setting up the Lightweight Peg Stability Module (LITE-PSM-USDC-A) for Phase 1, triggering Spark Proxy Spell.
date: 2024-07-25T00:00:00.000Z
address: "$spell_address"

---
# [Executive Proposal] LITE-PSM-USDC-A Phase 1 Setup, Spark Proxy Spell - July 25, 2024

The Governance Facilitators, Dewiz, and Sidestream have placed an executive proposal into the voting system. MKR Holders should vote for this proposal if they support the following alterations to the Maker Protocol.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

---

## Executive Summary

If this executive proposal passes, the following **actions** will occur within the Maker Protocol:

- LITE-PSM-USDC-A Phase 1 actions:
  - PSM-USDC-A [Debt Ceiling Instant Access Module (DC-IAM)](https://mips.makerdao.com/mips/details/MIP104#14-3-1-4-debt-ceiling-instant-access-module-dc-iam-) parameters will be updated.
  - LITE-PSM-USDC-A DC-IAM parameteres will be set up.
  - The PSM_MOM GSM Delay Exception will be activated.
  - **20 million USDC** will be migrated from PSM-USDC-A to LITE-PSM-USDC-A.
  - The [GSM Pause Delay](https://mips.makerdao.com/mips/details/MIP113#10-1-gsm-governance-security-module-pause-delay) will be decreased.
  - The [Emergency Shutdown Module (ESM)](https://docs.makerdao.com/smart-contract-modules/shutdown/the-emergency-shutdown-process-for-multi-collateral-dai-mcd) [Minimum Threshold](https://docs.makerdao.com/smart-contract-modules/shutdown/emergency-shutdown-module) will be increased.
  - The LITE-PSM-USDC-A Keeper Network Job will be deployed.
  - Six additions will be made to the [Chainlog](https://chainlog.makerdao.com).
- A Spark Proxy Spell will be triggered.

**Voting for this executive proposal will place your MKR in support of the changes and additions outlined above.**

Unless otherwise noted, the changes and additions listed above are subject to the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay). This means that if this executive proposal passes, the changes and additions listed above will only become active in the Maker Protocol after the GSM Pause Delay has expired. The GSM Pause Delay is currently set to **30 hours**.

This executive proposal includes an office-hours modifier that means that it **can only be executed between 14:00 and 21:00 UTC, Monday - Friday**.

If this executive proposal does not pass within 30 days, then it will expire and can no longer have any effect on the Maker Protocol.

---

## Proposal Details

### LITE-PSM-USDC-A Phase 1 Actions

The actions described below are part of the [first phase](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1) in the migration process [from PSM-USDC-A to LITE-PSM-USDC-A](https://forum.makerdao.com/t/litepsm-lite-psm-usdc-a-introduction-and-overview/24512).

#### PSM-USDC-A DC-IAM Parameters Update

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the PSM-USDC-A DC-IAM parameter below will be updated as follows:

- The [Target Available Debt (`gap`)](https://mips.makerdao.com/mips/details/MIP104#14-3-1-4-2-target-available-debt-gap-) will be decreased by 20 million from 400 million to **380 million**.

#### LITE-PSM-USDC-A DC-IAM Setup

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the LITE-PSM-USDC-A DC-IAM will be set up as follows:

- [Maximum Debt Ceiling (`line`)](https://forum.makerdao.com/t/litepsm-lite-psm-usdc-a-introduction-and-overview/24512#lite-psm-usdc-a-parameters-overview-8): 50 million DAI
- [Target Available Debt (`gap`)](https://forum.makerdao.com/t/litepsm-lite-psm-usdc-a-introduction-and-overview/24512#lite-psm-usdc-a-parameters-overview-8): 20 million DAI
- [Ceiling Increase Cooldown (`ttl`)](https://forum.makerdao.com/t/litepsm-lite-psm-usdc-a-introduction-and-overview/24512#lite-psm-usdc-a-parameters-overview-8): 12 hours
- [Fixed-sized Amount of Pre-minted Dai (`buf`)](https://forum.makerdao.com/t/litepsm-lite-psm-usdc-a-introduction-and-overview/24512#lite-psm-usdc-a-parameters-overview-8): 20 million DAI

#### PSM_MOM GSM Delay Exception Activation

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the PSM_MOM GSM Delay Exception will be activated at [0x467b32b0407Ad764f56304420Cddaa563bDab425](https://etherscan.io/address/0x467b32b0407Ad764f56304420Cddaa563bDab425).

#### USDC Migration from PSM-USDC-A to LITE-PSM-USDC-A

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the following action will take place:

- An initial **20 million USDC** in reserve will be migrated from PSM-USDC-A to LITE-PSM-USDC-A.

#### GSM Pause Delay Update

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the [GSM Pause Delay](https://mips.makerdao.com/mips/details/MIP113#10-1-gsm-governance-security-module-pause-delay) will be updated as follows:

- The GSM Pause Delay will be decreased by 14 hours from 30 hours to **16 hours**.

#### ESM Minimum Threshold Update

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then the [ESM Minimum Threshold](https://docs.makerdao.com/smart-contract-modules/shutdown/emergency-shutdown-module) will be updated as follows:

- The ESM Minimum Threshold will be increased by 150,000 MKR from 150,000 MKR to **300,000 MKR**.

#### LITE-PSM-USDC-A Keeper Network Job Deployment

- **Authorization:** [Poll 1124](https://vote.makerdao.com/polling/QmdcHXHy), [Ecosystem Approval](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/2)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/1)

If this executive proposal passes, then a keeper network job for calling permissionless LitePSM functions will be deployed through contract call `sequencer.addJob(0x689cE517a4DfCf0C5eC466F2757D324fc292C8Be)` with the following parameters:

- `fill`: Set threshold at 15 million DAI.
- `trim`: Set threshold at 30 million DAI.
- `chug`: Set threshold at 300,000 DAI.

#### Additions to the Chainlog

- **Authorization:** [Ecosystem Approval](http://forum.makerdao.com/t/lite-psm-usdc-a-phase-1-test-period-proposed-parameters/24644/7)
- **Proposal**: [Forum post](https://forum.makerdao.com/t/jul-12-2024-proposed-changes-to-spark-for-upcoming-spell/24635)

If this executive proposal passes, then the following additions will be made to the [Chainlog](https://chainlog.makerdao.com):

- Add [0xf6e72Db5454dd049d0788e411b06CfAF16853042](https://etherscan.io/address/0xf6e72db5454dd049d0788e411b06cfaf16853042) as `MCD_LITE_PSM_USDC_A`.
- Add [0x37305B1cD40574E4C5Ce33f8e8306Be057fD7341](https://etherscan.io/address/0x37305B1cD40574E4C5Ce33f8e8306Be057fD7341) as `MCD_LITE_PSM_USDC_A_POCKET`.
- Add [0x69cA348Bd928A158ADe7aa193C133f315803b06e](https://etherscan.io/address/0x69cA348Bd928A158ADe7aa193C133f315803b06e) as `MCD_LITE_PSM_USDC_A_JAR`.
- Add [0x5eeB3D8D60B06a44f6124a84EeE7ec0bB747BE6d](https://etherscan.io/address/0x5eeB3D8D60B06a44f6124a84EeE7ec0bB747BE6d) as `MCD_LITE_PSM_USDC_A_IN_CDT_JAR`.
- Add [0x467b32b0407Ad764f56304420Cddaa563bDab425](https://etherscan.io/address/0x467b32b0407Ad764f56304420Cddaa563bDab425) as `LITE_PSM_MOM`.
- Add [0x689cE517a4DfCf0C5eC466F2757D324fc292C8Be](https://etherscan.io/address/0x689cE517a4DfCf0C5eC466F2757D324fc292C8Be) as `CRON_LITE_PSM_JOB`.

---

### Spark Proxy Spell

- **Authorization:** Ecosystem Approvals [1](http://forum.makerdao.com/t/jul-12-2024-proposed-changes-to-spark-for-upcoming-spell/24635/3), [2](http://forum.makerdao.com/t/jul-12-2024-proposed-changes-to-spark-for-upcoming-spell/24635/17)
- **Proposal**: Forum posts [1](https://forum.makerdao.com/t/jul-12-2024-proposed-changes-to-spark-for-upcoming-spell/24635), [2](http://forum.makerdao.com/t/jul-12-2024-proposed-changes-to-spark-for-upcoming-spell/24635/14)

If this executive proposal passes, a Spark Proxy Spell will be triggered at [0x18427dB17D3113309a0406284aC738f4E649613B](https://etherscan.io/address/0x18427dB17D3113309a0406284aC738f4E649613B). This proxy spell will take the following action:

- [Mainnet] Activate a Morpho market for Pendle PT sUSDe with Oct 24, 2024 maturity.

## Review

Community debate on these topics can be found on the MakerDAO [Governance forum](https://forum.makerdao.com/). Please review any linked threads to inform your position before voting.

---

## Resources

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).