# Governance

webpack is a tool that is used by the entire world. This meanas that in order to ensure stability, a set of collaborators is required to make sure the project is stable, secure and relevant.

## Contributors

Contributors are people that contribute to webpack. There are different methods of contributing, such as documentation work in different parts of webpack. Documentation contributions are an important part of the webpack organization - the documentation of webpack itself or 2nd hand documentation webpack contrib.

Another method of contributing to webpack is to participate in issue triaging, contributing code. There are no expectations of actively participating to webpack. Any person is welcome to contribute to webpack, regardless of skillsets or experience.

If a contributor has contributed to the organization for a prolonged period of time and shown progression, a contributor may request to join webpack's Technical Steering Committee (TSC).

### Triagers

A triager is an individual that has shown interest in the webpack project and has done continuous work in the issue tracker of the webpack organization. A triager is expected to be active in the organization and participate in the organization's activities. Triagers are given the "Triage" GitHub role and have:

- Ability to label issues and pull requests
- Ability to comment, close, and reopen issues and pull requests

### Commiters

A commiter is an individual that has shown prolonged interested in the webpack project and has done continuous code contributions to the webpack organization. A commiter is given "Write" GitHub role to one or more repositories in the webpack organization.

A commiter may contribute to one or more repositories in the webpack organization. A commiter is expected to be active in the organization and participate in the organization's activities.

The webpack organization has different Working Groups (WGs) and teams that are responsible for different aspects of the project. The [List of current teams][] describes their objectives and current members.

#### Documenters

This section describes the documentation work in both the official documentation (webpack.js.org), and documentation in each webpack repository.

A "Documenter" is a contributor that is working on documentation on the main webpack.js.org page and in the webpack repositories. This work is very important for the webpack project in order for users to be able to understand how to use webpack and its 2nd hand tools.

The work as a "Documenter" is done by understanding the API And codebase of webpack and webpack-contrib well enough to express how to use it as a user. To become a documenter:

- Play well with others and show good team synergy.
- Be able to communicate factual topics to a understandable format.
- Shown activity in webpack and/or webpack-contrib.

During Technical Steering Commitee meetings, the team will assign and/or discuss efforts in the webpack documentation. If a new contributor to the documentation (documenter) is involved in webpack/webpack contrib, the team will nominate this individual to the documentation team.

#### Core Commiters

A core commiter is an individual that has a good understanding of the core of webpack and that has done continuous code contributionsd to the core of webpack. A core commiter performs all the duties and has all the rights of a commiter, but necessarily has "Write" access to the core of webpack.

## Technical Steering Committee (TSC)

A subset of the collaborators forms the Technical Steering Committee (TSC). The TSC has final authority over this project, including:

* Technical direction
* Project governance and process (including this policy)
* Contributor policies
* GitHub repository hosting
* Code of Conduct guidelines
* Maintaining the list of collaborators

The current list of TSC members is in [the project README][].

The [TSC Charter][] governs the operations of the TSC. All changes to the charter need approval by the [OpenJS Foundation Cross-Project Council][] (CPC).

### TSC Meetings

Technical Steering Commitee meetings are hosted on Slack over text or video conferencing depending on the agreement of the current members.

- Meetings are held on a regular basis and are either recorded (when over video conferencing) or have meeting minutes taken.
  - During the meeting, the TSC meeting chair (decided within the meeting) ensures that someone takes minutes. After the meeting, the TSC chair ensures that someone opens a pull request with the minutes.
  - Meeting minutes are reviewed and approved by the TSC after the meeting has ended, it should be done through a pull request targeting the `TSC_MEETINGS` folder.
    - The meeting minutes may follow the [meeting minutes template][].
- Meetings are only held when there are pending topics for the TSC to discuss (issues or pull requests with the `tsc-agenda` label).
  - The TSC reserves the right to conduct ad-hoc meetings whenever needed at their own discretion. These are also subjected to the same rules as regular meetings.
- Meetings are closed to the public, but the TSC may invite people to take part in a non-voting capacity.

Any community member can create a GitHub issue asking that the TSC review something. If consensus-seeking fails for an issue, a collaborator may apply the `tsc-agenda` label. That will add it to the TSC meeting agenda.

## Consensus-Seeking Process

The TSC follows a [Consensus Seeking][] decision-making model per the [TSC Charter][]. The consensus seeking process exists to ensure that all voices are heard and that decisions are made with the best interest of the project in mind.

----

This work is a derivative of the [Node.js Project Governance Model](https://github.com/nodejs/node/blob/main/GOVERNANCE.md).

[consensus seeking]: https://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[contribution guidelines]: https://github.com/webpack/webpack/blob/main/CONTRIBUTING.md
[the project readme]: https://github.com/webpack/webpack/blob/main/README.md#PLACE-FOR-TSC-MEMBERS
[tsc charter]: ./TSC_CHARTER.md
[list of current teams]: ./WORKING_GROUPS.md
[meeting minutes template]: ./TSC_MEETINGS/TEMPLATE.md
[the project readme]: ./README.md
[openjs foundation cross-project council]: https://github.com/openjs-foundation/cross-project-council/