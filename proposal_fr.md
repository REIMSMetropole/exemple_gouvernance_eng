# Processus de contribution et de révision

## Introduction

Before making any contributions, it is important for contributors and the community at large to open discussions ( proposals ) about addition or significant improvement of features.

Avant toute contribution, les contributeurs et la communauté (au sens large) discutent (proposent) les ajouts ou modifications importantes des fonctionnalités.

Those proposals are centralized on issues tagged "proposals" in the `iTowns/itowns` repository.

Ces propositions sont répertoriées dans les tickets, taggés "propositions"/"proposals" dans le dépôt du code. 

This allows contributors to demonstrate the existence of real use cases and gain a concrete understanding of user needs, as well as a more fluid process for contributions, and better visibility for the end users and stakeholders.



## Types of Contribution

Contributions can be of 4 types:

- **Documentation**
- **Bug fixes** linked to an open bug issue on the `itowns/itowns` repository.
- **Significant improvement of an existing feature or component**
- **Addition of a new feature.**

*Note: Proposals are only required for improvements or additions of features. Bug reports are sufficient for proposing a fix.*

## Documentation

Documentation changes can be proposed directly through pull requests. In case of questions or issues with documentation, an issue should be opened, following the same proposal process as other contribution types.

## Bug Discovery and Correction Process

The entire bug discovery and correction process takes place on the `itowns/itowns` repository

1. A user or contributor submits a bug report through an issue (using the predefined template)
2. A contributor submits a fix by opening a pull request linked to the corresponding issue in the description

## Significant improvements and new features

Significant improvements or new features occur through opening of a dedicated proposal issue on the `itowns/itowns` repository.

This can be initiated in two ways:
- As a community member through an informal discussion. The final feature takes shape through discussions and users feedback.
- As a contributor through an issue using the defined template containing:
   - Concise details of the feature, including its rationale, and use cases supported by user needs
   - Technical explanation of the suggested implementation

*Note: Contributors can still directly open a pull request on the itowns/itowns repository. In this case, it is expected for the pull request to include the same informations as for a proposal issue. PRs submitted without proposal will not likely be prioritized by reviewers.*

The Core Contributors are in charge of verifying the validity of the proposal : 

- adherence to processes, values and overall project direction
- technical coherency with existing code base
- technical quality of the chosen solution.
- impact on the rest of the codebase.
- non-regression

Expressions of non-validity of the proposal must be motivated and their rationale explained, with reference to the values, processes and documents of the project.

If at least one of the Core Contributors expresses a non-favorable advice to the proposal, the issue can remain open, the proposal can be amended and discussions can continue until the negative advice is removed. Meanwhile, no implementation corresponding to this proposal should be merged.

The Product Committee can give advice on proposals, considering existing priorities, resource allocations and knowledge of other features currently planned. The PC can integrate the proposal to its roadmap items, and to the list of items subjects for resource allocations from the Sponsors.

If a consensus is reached, or no negative advice from Core Contributor has been expressed 1 month after the last comment on the proposal, it is considered as acceptable, and a pre-approval of the corresponding Pull Request.

## Implementation & review

After the proposal phase, contributors can:
- Implement the feature following the chosen solution
- Open a draft pull request on the main itowns/itowns repository (linking to the proposal issue in `itowns/itowns`)

After implementation, the PR is marked as "Ready", and the review phase can begin : 

1. Functional review: The reviewer ensures that the implementation adds the proposed functionality corresponding to the initial proposal
2. Technical review: The reviewer ensures that the implementation respects the project's processes and meets technical consensus

The review can be made by any contributor. 

Product committee members are also expected to assess the functional aspect of the implementation.

The merge action is achieved by a Core Contributor, who is expected to take responsibility for the code merged, with the collaboration of the initial contributor(s).

This review phase is simplified as previous discussions around the proposal helped understand the author's intentions and choices.

## Sponsors Comittee veto

**At any point in time, the Sponsors Committee can emit a veto for a proposal or a Pull Request**. This veto must be motivated and its rationale explained in detail, with references to the project's values, processes and global strategy and purpose.


