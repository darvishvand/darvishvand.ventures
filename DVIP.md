---
dvip: 1
title: DVIP Purpose and Guidelines
author: "The Darvishvand.Ventures Founding Team"
discussions-to: "https://forum.darvishvand.ventures/c/proposals"
status: Active
type: Process
created: 2025-09-16
---

## Simple Summary

A DVIP (Darvishvand.Ventures Improvement Proposal) is a formal design document for introducing features, changes, or new ventures to the Darvishvand.Ventures DAO.

## Abstract

DVIPs are the primary mechanism for proposing and voting on any and all changes or actions within the Darvishvand.Ventures ecosystem. This includes proposing new startups for incubation, making changes to the DAO's governance framework, and updating operational processes. A DVIP must provide a concise technical or business specification and a clear rationale. The DVIP author is responsible for building community consensus before a proposal is put to a vote. The revision history of each DVIP serves as the historical record of the proposal.

## Motivation

Inspired by Bitcoin's BIPs, the DVIP process is designed to provide a transparent, structured, and accountable framework for governance. Given that Darvishvand.Ventures aims to solve the opacity of traditional accelerators, it is critical that its own governance be radically transparent and community-driven. This process ensures that every decision, from funding a new venture to changing a parameter in a smart contract, is publicly documented, debated, and decided upon by the DAO members.

## Specification

### DVIP Types

There are four types of DVIPs:

*   **Venture DVIP**: This is the core proposal type for the DAO's primary mission: accelerating startups. A Venture DVIP is used to propose a new business or startup idea for the DAO to fund and incubate. If approved, a "Venture Pod" is formed and allocated a budget from the DAO treasury.

*   **Protocol DVIP**: Describes any change to the core Darvishvand.Ventures protocol or architecture. This includes changes to the smart contracts, tokenomics, the four-layered architecture (Legal, Governance, Operational, Economic), or anything affecting the interoperability of the DAO's systems. This is analogous to a "Standards Track" proposal.

*   **Process DVIP**: Describes a process surrounding the DAO or proposes a change to a process. This DVIP itself is a Process DVIP. Examples include modifying the voting process, changing these guidelines, or defining the roles and responsibilities of a Pod.

*   **Informational DVIP**: Provides general guidelines, information, or a declaration of intent to the community. Informational DVIPs do not require a formal vote for implementation but serve to signal community consensus or document important information.

### DVIP Workflow

The Darvishvand.Ventures governance lifecycle is designed to be rigorous and transparent, moving from idea to execution.

**Phase 0: Ideation**
*   **Action**: An idea is informally discussed in the appropriate category on the [Darvishvand.Ventures Discussions Space](https://github.com/darvishvand/darvishvand.ventures/discussions).
*   **Goal**: To gauge community interest, gather initial feedback, and find collaborators. This step prevents time being wasted on proposals that are unlikely to gain traction.

**Phase 1: Drafting**
*   **Action**: The proposal author drafts the DVIP using the appropriate template below.
*   **Goal**: To create a formal, high-quality document that clearly articulates the proposal and its rationale.

**Phase 2: Review**
*   **Action**: The author submits the DVIP as a pull request to the `/DVIPs` folder. A DVIP Editor assigns a DVIP number and merges the draft. The author then posts a link to the draft on the Discussions Space for formal community review.
*   **Goal**: To gather detailed feedback from the community and refine the proposal. The DVIP may be updated several times during this phase.

**Phase 3: Voting**
*   **Action**: Once the author believes the proposal is mature and has sufficient community support, they will request a formal vote. A DVIP Editor will then move the proposal to the DAO's official voting platform.
*   **Goal**: To make a formal, binding decision on the proposal. The voting period and quorum requirements are defined by the Governance Layer of the DAO.

**Phase 4: Execution**
*   **Action**: If the vote passes, the proposal is implemented.
    *   For a **Venture DVIP**, the Treasury allocates the requested budget to a new, dedicated multi-sig wallet for the "Venture Pod," and the project officially begins. The DVIP status becomes `Incubating`.
    *   For a **Protocol DVIP**, the changes are implemented and deployed by the core team or a designated developer pod.
    *   For a **Process DVIP**, the changes are enacted and documentation is updated.
*   **Final Statuses**: `Accepted`, `Rejected`, `Withdrawn`. A Venture DVIP moves from `Incubating` to `Completed` or `Failed` based on its performance against its stated milestones.

### Structure of a Successful DVIP

Each DVIP must have the following parts:

*   **Preamble**: RFC 822 style headers containing metadata.
*   **Simple Summary**: A one or two-sentence summary of the proposal.
*   **Abstract**: A short (~200 word) description of the issue being addressed or the venture being proposed.
*   **Motivation**: A clear explanation of why this proposal is necessary or valuable.
*   **Specification**: The technical or business specification of the proposal.
*   **Rationale**: An explanation of the design choices and alternatives considered.
*   **Security Considerations**: A discussion of any security implications.
*   **Copyright**: Must be waived via CC0.

---

### Additional Sections for a **Venture DVIP**

A Venture DVIP requires a more detailed business plan and must include these additional sections:

*   **Venture Pod**: The names/pseudonyms of the initial members of the Venture Pod, including the designated Pod Lead.
*   **Problem Statement**: A detailed description of the market problem being solved.
*   **Proposed Solution**: A detailed description of the product or service.
*   **Business Model**: How the venture will generate revenue.
*   **Funding Request**: The total amount of capital requested from the DAO treasury and a detailed breakdown of how it will be used.
*   **Milestones & KPIs**: A clear, measurable set of milestones and Key Performance Indicators for the first 12 months. Funding may be released in tranches based on hitting these milestones.
*   **Value Accrual**: The proposed percentage of revenue or equity that will be returned to the main DAO treasury, per the Economic Layer design.

---

### DVIP Editors

The DVIP Editors are the members of the **Community Pod**, as defined in the DAO's Operational Layer. They are responsible for the administrative and editorial aspects of the DVIP process.

### Editor Responsibilities

The DVIP Editors' responsibilities include:
*   Reading proposals to ensure they are well-formed, complete, and technically/commercially sound.
*   Assigning DVIP numbers and merging pull requests.
*   Updating the status of DVIPs.
*   Interfacing with authors to guide them through the process.
*   Moving mature proposals to the official voting platform.

The Editors' role is to facilitate the process, not to act as gatekeepers. They will not unreasonably deny a proposal that meets the minimum criteria.

## Copyright

All contributions to this proposal are licensed under the GNU General Public License v3.0. By submitting a DVIP, you agree to license your contribution under the same terms as the project's license, which can be found in the `LICENSE.md` file.
