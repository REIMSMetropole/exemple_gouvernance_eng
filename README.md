Governance Proposal ( 2024 )

Proposition de charte de gouvernance ( 2024 )
----

## Préambule

le projet #### est ... un projet opensource,  description du projet.

~~iTowns is an **open-source framework** designed for the **efficient visualization, navigation, and interaction** with **multi-scale 2D and 3D geospatial data** on the **web**.
Built on the [`three.js`](three) general-purpose 3D library, it enables users to easily build their own customized 3D geographic applications.~~

Ce projet est un **commun**, développé collectivement, par une communauté de contributeurs, financiers ou au code, indépendant, public, laboratoires de recherche et entreprises privées.

Le commun est régi par des **règles** qui garantissent son amélioration et l'invariabilité de sa nature partagée et open. 

~~The commons is guided by **rules** that safeguard its expansion and the immutability of its open and shared nature.~~

Ce document formalise les **valeurs fondamentales**, la **structure communautaire** et la **gouvernance** du projet.

~~This document formalizes the **core values**, **community structure** and **governance** of the [`iTowns`](itowns) project.~~


## Values

- iTowns is a **commons**, developed collectively by a diverse community. Its **open and shared nature** is **immutable**
- Operating as **free software** under the MIT or CeCILL-B license, it permits unrestricted reuse and modifications, with the source code readily accessible at [https://github.com/iTowns/itowns](itowns:github)
- Contributors must adhere to the established rules and agree to the [**code of conduct**](coc)
- **Peer reviewing** is a fundamental aspect of the project. Contributors can gain a more significant role by providing high-quality contributions within the established guidelines
- The community holds **sovereignty** and autonomously exercises governance over the project, free from external authority
- **Future developments** are publicized and discussed openly before implementation
- The dynamics of the open-source project are maintained to keep it aligned with **state of the art developments** in the field of 3D geospatial data visualization.

## Roles

- A "**User**" encompasses an individual or organization using the `iTowns` framework.
- A "**Contributor**" refers to any individual or organization actively involved in improvements to the iTowns project, whether through feature development, documentation additions, bug fixes or other contributions to the project.
- A "**Core contributor**" is any contributor holding commit rights to the main branch of the project.  These core developers handle technical governance of the project and guarantee its durability and independance
- A "**Sponsor**" refers to organizations providing financial support for the growth, initiatives, and activities of the iTowns project. These sponsors are responsible for funding decisions, and governance of the sponsors committee 
- The "**Community**" serves as an umbrella term, encompassing users, contributors, sponsors and stakeholders within the iTowns project.

## Sustainability

- The project identifies **key sponsors** which contribute significantly to its sustainability across its life cycle, adhering to the sponsors governance rules defined by the project. Current **key sponsors** are given in the [members](./members.md) document.

## Core contributors

A "**Core contributor**" is any contributor holding commit rights to the main branch of the project. These core contributors handle technical governance of the project and guarantee its durability and independance.

### Operation of Core Contributors

- Ensure the project's sustainability in terms of maintainability and technical debt
- **Monitor** ongoing **developments**
- Make consensus-based decisions on technical architecture and ensure its coherence
- Operate continuously, with responsiveness, in a dedicated public discussion channel
- Enforce the principle of reviewing and cross-validation, prohibiting validators from validating their own contributions or those of their respective organizations
- **Address requests** in issues

#### Joining the Core Contributors

Every contributor holding commit rights to the main project is a Core Contributor.

Achieving status of Core Contributor requires significant contributions to the project, a demonstrated ability to produce high-quality code or other resources, and adherence to the guidelines outlined in the code of conduct, CODING.md and CONTRIBUTING.md documents.

Access to the Core Contributor role is subject to a double majority vote by the Core Contributors. This role is granted on an individual basis (not as part of an organization). It may be rescinded for rule violations or if contributions cease for a one-year period. Revocation requires a double majority vote, excluding the concerned individual.

A Core Committer loses their rights after more than 6 months of inactivity and may also have their membership status challenged by peers for non-compliance with governance and project rules (code of conduct, adherence to contribution rules, etc.).

## Governance Organization & committees

Governance is structured into quickly deployable **committees**, each possessing **well-defined responsibilities** and a **transparent decision-making process**.
The objective is to ensure clarity and understanding for the `iTowns` project community.

### Project Steering Committee (PSC)

The project steering committee is the main governing body for the OpenSource project. The PSC comprises a subset of core developers holding commit rights to the main branch of the project. The PSC operates openly with a consensus based approach. The PSC mainly exists to solve conflicts or urgent issues where a consensus is hard to reach. The PSC may delegate specific responsibilities to particular project members.

The PSC upholds adherence to the project's architectural coherence, technical viability, and oversee contributions in accordance to the roadmap.

#### Role of the PSC

- **Ensure that all projects rules are respected**, be it values, governance or technical processes
- **Arbitrates** on the conformity of pull requests with the functional roadmap and established technical consensuses
- **Oversees the project's sustainability** in terms of maintainability and technical debt
- **Arbitrates decisions on technical architecture** and ensures its coherence
- Oversees ongoing **developments**
- Arbitrates requests for Core Contributor's rights and their removal

The PSC designates a release manager every two years with a majority vote.

#### Meetings

The PSC holds meetings at the request of any PSC member, and every 3 months minimum, and publishes meeting summaries via a public channel on GitHub. Active contributors who are not committee members may be invited to PSC meetings.

Members opinions are documented for transparency and as an objective metric of active participation, and proposed and adopted solutions are specifically reported.

### Sponsors committee

Comprising sponsors providing financial support the growth, initiatives and activities of the iTowns project, the **Sponsors committee** (*SC*) manages funding and investment, as well as mutualization and sharing of development efforts. It oversees the synchronization of efforts among its members. It also helps on the communication and marketing levels. The sponsors committee has a specific power to veto certain developments.

Through funding and resources allocation, the Sponsors Committee shapes the **strategic directions** of the project.

#### Role of the Sponsors committee

- Makes **decisions on budget** matters and funds allocation
- Shapes the **strategic directions** of the project in collaboration with all stakeholders
- **Prioritize** technical and functional proposal, through funding and resource allocation
- Handles **relationships with external entities** such as industrial partners, institutional bodies, scientific organizations and associations
- Oversees **project communication** strategies and actions
- **Establishes and executes its own governance**
- **Votes membership** requests within the committee.
- Has the **right to veto** specific contributions, with an open written motivation referencing core project values, processes and documents

#### Joining the Sponsors committee

Organizations seeking SC membership must meet the following prerequisites:

- **Contribute** an amount equivalent of a full-time annual commitment for one year to the project ( funding or resources )
- **Adhere** to project's governance rules
- **Commit to continue collaboration** under equivalent or higher resource conditions for a minimum of two years.

**New memberships** are subject to a simple majority vote by current Sponsors committee members, taking into account adherence to the values and rules of the present document.

Members requesting or discontinuing collaboration for a one-year period will automatically exit the Sponsors committee.

#### Meetings

The Sponsors Committee : 

- Convenes **formal meetings every six months**, either in person or via video conference,  and remains accessible via email as required by the product committe or PSC
- Publishes **meeting summaries** on a dedicated public channel ([iTowns website](itowns) or [GitHub](itowns:github))
- Collaborates closely with the product committee
- Has the authority to **invite** other project actors to its meetings, granting them an advisory role without voting rights

### Product Committee (PC)

The **Product Committee** (*PC*) comprises representatives from project-stakeholders and core developers.

The PC **oversees the functional aspects and roadmap** of the project, ensuring alignment with defined goals and needs, and serves as an operational relay of the Sponsors Committee.

#### Role of the PC

- Ensures **project alignment** with the Community's needs and the strategic directions set by the Sponsors for the project
- Organizes the collection of requirements based on information provided by the Sponsors Committee and the Community
- Coordinates the collection of user requirements through pull requests, user feedback, and discussions
- Proposes roadmap items to the Sponsors Committee for funding and resource allocation
- Proposes release schedule of feature items to the Sponsors Committee with corresponding resources
- Help Core developers to evaluate and improve proposals 
- Contributes to functional testing of pre-production versions

#### Joining the PC

The bi-annual renewal and structure of the Product Committee are as follows:

- Two-thirds of its members are designated by the Sponsors Committee.
- One-third is elected by the Core Developers.

#### Meetings

- Convenes **formal meetings every two months** and engages in **continuous discussion** through a [dedicated public channel](itowns:chan).
- Publishes **meeting summaries** on a dedicated public discussion channel ([iTowns website](itowns) or [Github](itowns:github)).
- Has the authority to **invite** other project actors to its meetings, granting them an advisory role without voting rights.

## Contribution process

See [Proposal process](proposal.md).

## Versions

A new version of iTowns is released every 4 months.  

### Release

- The release manager validates the next planned release date
- The release manager launches the release process
- Tests are launched before the release of the new version:
  + Unit tests
  + Functional tests
  + Client application test on the next branch
  + Regression tests through a complete run of all examples.
- The release manager validates the release and finishes the release process

The release manager may forward the release responsibility to another Core Contributor for a specific release.

### Communication

- The Changelog is published on Github.
- Distribution on npmjs/github:
  + Description of the version
  + Link to changelog
  + Link to examples

### Roadmap Update

- The items foreseen for the next releases are published on a public (non-exhaustive) roadmap and updated regularly by the Product Committee and the Sponsors Committee
- the project's progress is public and can be tracked at https://github.com/iTowns/itowns/projects?query=is%3Aopen.
- Anyone can suggest adding a new feature to the roadmap through a proposal.

[coc]: https://www.contributor-covenant.org/fr/version/2/0/code_of_conduct/
[itowns]: http://www.itowns-project.org/
[itowns:github]: https://github.com/iTowns/itowns
[itowns:chan]: todo
[three]: https://threejs.org/



adapté du projet de gouvernance rédigé par Oslandia : ajout du lien.
