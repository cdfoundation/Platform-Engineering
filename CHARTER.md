# CDF SIG Platform Engineering — Charter

## SIG Name

CDF Special Interest Group: Platform Engineering

## Mission Statement

The CDF SIG Platform Engineering exists to advance the practice of platform engineering within continuous delivery ecosystems by developing vendor-neutral guidance, reference architectures, and community resources that help organizations build Internal Developer Platforms (IDPs) grounded in open-source CI/CD tooling. We believe that platform engineering—when practiced with a clear delivery focus—reduces cognitive load on development teams, accelerates software delivery, and provides the operational guardrails necessary for secure, scalable, and sustainable software organizations.

## Background and Context

Platform engineering has evolved from an informal practice into a recognized discipline with its own tools, frameworks, and organizational models. Teams building Internal Developer Platforms increasingly rely on many of the same technologies that the CD Foundation stewards: pipeline orchestration, artifact management, continuous delivery workflows, and deployment governance.

Despite this alignment, there is no authoritative, vendor-neutral reference for how platform teams should adopt, integrate, and build upon CD Foundation projects. Practitioners face a fragmented landscape of tooling choices, inconsistent maturity models, and limited community resources tailored to their domain.

The CDF SIG Platform Engineering addresses this gap directly by connecting the platform engineering practitioner community with the CD Foundation ecosystem and its collaborative governance model.

## Scope

### In Scope

- Vendor-neutral guidance on building and operating Internal Developer Platforms (IDPs)
- CI/CD integration patterns for platform engineering teams using CDF ecosystem projects
- Developer experience (DevEx) frameworks, golden path templates, and self-service workflow patterns
- Platform engineering maturity models aligned with DORA metrics and industry benchmarks
- Reference architectures for platform teams integrating open-source tooling
- Guidance on embedding security and compliance automation into platform engineering workflows
- Interoperability patterns between CDF projects and adjacent ecosystems (Backstage, Crossplane, CNCF tooling)
- Community education through documentation, presentations, and working sessions

### Out of Scope

- Creating or maintaining platform engineering tooling
- Providing compliance certification or auditing services
- Replacing individual CDF project documentation
- Defining new security frameworks (aligned with, but not duplicating, the CDF CI/CD Cybersecurity SIG)
- Vendor-specific implementation guidance or product endorsements

## Relationship to Other CDF SIGs and Projects

This SIG operates in close coordination with:

- **CDF CI/CD Cybersecurity SIG**: The Platform Engineering SIG consumes and references security guidance produced by the Cybersecurity SIG, particularly around embedding security guardrails into platform workflows, rather than duplicating that work.
- **CDF TOC**: The SIG reports to the Technical Oversight Committee and operates under its governance framework.
- **CDF Projects** (Jenkins, Tekton, Spinnaker, Shipwright, Ortelius, CDEvents): The SIG serves as a practitioner-facing bridge that documents how platform teams can integrate and build upon these projects.

## Deliverables

### Primary Deliverable: Platform Engineering Guide

A living, open-source guide that documents:

- Core platform engineering patterns and their CI/CD integration points
- Tooling guidance for platform teams building on CDF ecosystem projects
- Reference architectures and golden path templates
- Developer experience measurement and improvement approaches
- Platform engineering maturity model

### Additional Deliverables

- Meeting notes and decision records (published to the SIG repository)
- Recorded working sessions and presentations
- Roadmap and backlog maintained in the SIG repository
- Blog posts and community reports submitted to the CDF blog
- Input to CDF project communities on platform engineer needs and gaps

## Success Metrics

The SIG will measure success by:

- Active maintainers and regular contributors across organizations
- Published and community-reviewed Platform Engineering Guide content
- Number of CDF projects with documented platform integration patterns
- Community engagement: meeting attendance, mailing list activity, Slack participation
- Adoption references at CDF events, KubeCon, PlatformCon, and industry publications
- Contributor diversity across companies, roles, and geographies
- Feedback from CDF End User Council and CDF Member companies

## Governance

### Guiding Principles

- **Vendor neutrality**: All guidance and tooling recommendations must remain vendor-neutral and grounded in open-source solutions.
- **Practitioner focus**: Content is developed by and for platform engineering practitioners, not tool vendors.
- **Open collaboration**: All decisions, proposals, and meeting records are public.
- **Consensus-driven**: Major decisions are made by SIG consensus, with escalation to the CDF TOC where needed.

### Decision-Making

The SIG operates using a consensus-driven open governance model. Proposals are raised as GitHub issues or pull requests, discussed in SIG meetings and on the mailing list, and accepted through lazy consensus (no objections within a defined period) or explicit vote when required. The SIG Chair facilitates decision-making and escalates unresolved disagreements to the CDF TOC.

### Meetings

The SIG meets on a regular cadence (frequency to be confirmed at charter ratification). All meetings are:

- Open to the public
- Recorded and published
- Documented with written meeting notes in the SIG repository

### Communication Channels

- **Slack**: CDF Slack workspace *(channel to be created)*
- **Mailing List**: *(to be created at lists.cd.foundation)*
- **GitHub**: [https://github.com/cdfoundation/sig-platform-engineering](https://github.com/cdfoundation/sig-platform-engineering) *(pending repository creation)*
- **Meeting Notes**: Linked from the SIG repository

## Leadership

### Chair

Jennifer Mulford ([@jenmmulford](https://github.com/jenmmulford)), Senior Platform Security Engineer, Okta

The Chair is responsible for:

- Facilitating SIG meetings and maintaining the meeting agenda
- Representing the SIG at CDF TOC meetings and community events
- Driving the SIG roadmap and ensuring deliverable progress
- Welcoming new contributors and maintaining an inclusive community
- Coordinating with other CDF SIGs and projects

### TOC Sponsor

*To be confirmed*

### Initial Committers

| Name | GitHub | Affiliation |
|------|--------|-------------|
| Jennifer Mulford | [@jenmmulford](https://github.com/jenmmulford) | Okta |
| [Name] | [@handle] | [Affiliation] |

## Initial Roadmap

### Phase 1 — Foundation
- Establish SIG governance: mailing list, Slack channel, GitHub repository, meeting cadence
- Recruit initial members and define contribution model
- Draft and ratify the Platform Engineering Guide outline
- Publish first set of core platform engineering patterns

### Phase 2 — Guide Development
- Develop and publish Platform Engineering Guide sections covering IDP foundations, CI/CD integration patterns, and developer experience frameworks
- Document integration patterns for key CDF projects
- Publish Platform Engineering Maturity Model (v1)

### Phase 3 — Community Growth and Iteration
- Iterate guide content based on community feedback and industry evolution
- Expand reference architectures and golden path templates
- Engage CDF End User Council for practitioner feedback
- Deepen collaboration with CNCF, Backstage, and OpenSSF communities
- Present SIG work at CDF events and industry conferences

## Statement of Alignment with CDF Mission

The Continuous Delivery Foundation's mission is to improve the world's capacity to deliver software. Platform engineering is one of the most direct expressions of that mission in modern organizations: it is the discipline of building the platforms that enable continuous delivery at scale.

The CDF SIG Platform Engineering directly advances the Foundation's mission by:

- Providing practitioner guidance that accelerates adoption of CDF ecosystem tooling
- Strengthening the feedback loop between platform engineering end users and CDF projects
- Enabling interoperability between CDF-hosted projects and the broader platform tooling ecosystem
- Contributing to a more secure, reliable, and developer-friendly software delivery landscape
- Establishing CDF as the authoritative community resource for platform engineering in the context of continuous delivery

## Code of Conduct

All SIG participants are expected to uphold the [CDF Code of Conduct](https://github.com/cdfoundation/community/blob/main/CODE_OF_CONDUCT.md).

## License

All SIG-produced content is licensed under the [Apache 2.0 License](LICENSE).

---

*Charter ratified: [Date pending TOC approval]*  
*Last updated: June 2026*
