---
linkTitle: "Home"
weight: 1
layout: docs
---


<div style="text-align: center; width: 100%;">

  <img
    src="/images/platformengineeringLogo.png"
    alt="Platform Engineering Golden Paths"
    style="display: block; margin: 0 auto 20px auto; width: 360px; max-width: 100%; height: auto;"
  />

  <h1 style="text-align: center; margin-bottom: 30px;">
    Platform Engineering Golden Paths
  </h1>

</div>

## Building Better Developer Experiences with Open-Source Golden Paths

Platform engineering helps organizations simplify software delivery by providing developers with consistent, reliable, and self-service ways to build, deploy, and operate applications. Rather than asking every team to assemble and maintain its own tooling, infrastructure, and workflows, platform teams create shared capabilities that reduce complexity while allowing developers to focus on delivering software.

The **Continuous Delivery Foundation (CDF) Platform Engineering Special Interest Group (SIG)** is developing the **Platform Engineering Golden Paths Guide** to share practical approaches, reusable patterns, and open-source tooling that help organizations build and evolve their internal developer platforms.

The guide focuses on **golden paths**: documented, supported, and preferably automated ways to complete common development and operational tasks. A golden path may combine templates, workflows, platform services, policies, and guidance to help teams complete a task with less friction and greater consistency. Golden paths should make a recommended approach easy to adopt without preventing teams from choosing alternatives when their needs differ.

Designed for platform engineers, developers, DevOps and SRE teams, engineering leaders, and other practitioners, this community-developed guide will explore how to turn platform engineering principles into practical, repeatable workflows using open-source solutions.

**Note:** The guide is being developed by the CDF Platform Engineering SIG. Its aim is to share vendor-neutral patterns and open-source approaches, not to prescribe a single platform architecture or endorse a commercial product.

## Why This Guide?

Organizations often face the same delivery challenges: fragmented developer experiences, inconsistent environments, duplicated automation, complex onboarding, and too many choices about how to build and operate software.

Platform engineering addresses these challenges by treating the internal developer platform as a product and developers as its customers. Golden paths translate that product mindset into clear, supported workflows for the tasks developers perform most often.

The guide is intended to help teams answer practical questions:

- Which developer workflows would benefit most from a golden path?
- How can platform teams make common tasks self-service?
- What should be standardized, and where should teams retain flexibility?
- How can open-source tools be connected into reusable workflows?
- How can platform capabilities support reliability, security, compliance, and cost awareness without creating unnecessary friction?
- How should platform teams measure adoption, developer experience, and outcomes?
- How can organizations start small, gather feedback, and improve golden paths over time?

The objective is to share real-world patterns that teams can adapt to their own environments, whether they are introducing platform engineering practices or expanding an established internal developer platform.

## What Is a Golden Path?

A **golden path** is a recommended, well-supported way to accomplish a common task. It brings together the tools, automation, documentation, and platform capabilities needed to help developers succeed without having to become experts in every underlying system.

For example, a golden path might help a developer create a new service, provision a development environment, establish a CI/CD pipeline, deploy to a Kubernetes cluster, observe application health, or respond to a production issue.

Effective golden paths generally share several characteristics:

- **Discoverable:** Developers can easily find the path and understand when to use it.
- **Self-service:** Routine tasks can be completed with minimal manual handoffs.
- **Repeatable:** Teams can achieve consistent results across projects and environments.
- **Automated:** Common steps are captured in templates, pipelines, APIs, or workflows.
- **Flexible:** Teams can extend or depart from the recommended path when appropriate.
- **Well-supported:** Documentation, ownership, maintenance, and feedback channels are clear.
- **Measurable:** Platform teams can evaluate adoption, friction, reliability, and outcomes.

A golden path is more than a collection of tools. It is an end-to-end developer experience built around a specific need.

## Guide Organization

The guide will organize golden paths around three broad phases of the application lifecycle. This structure is intended to help platform teams identify the services and workflows developers need, from the first project setup through ongoing production operations.

### Phase 1: Develop and Prepare

Developers need a simple, consistent way to begin working on applications and services. Platform teams can streamline onboarding through standardized templates, ready-to-use development environments, shared resources, and clear documentation. Golden paths simplify common tasks such as repository setup, configuration management, version control, and collaboration while reducing repetitive work.

They can also support AI-assisted development and incorporate baseline quality, security, and operational practices, allowing developers to focus on building software rather than managing tools and infrastructure.

**Goal:** Help developers start productive work quickly through discoverable, consistent, and self-service development experiences.

### Phase 2: Build and Deliver

Once development is underway, teams need a consistent and reliable path from source code to deployment. Platform teams can simplify software delivery through standardized CI/CD pipelines, automated builds and testing, artifact management, infrastructure provisioning, and reusable deployment workflows.

Golden paths can also streamline configuration management, secrets handling, release strategies, and rollback while providing traceability across builds and deployments. By incorporating quality, reliability, and security checks into these workflows, platform teams reduce complexity and enable developers to deliver software faster and with greater confidence.

Goal: Provide development teams with a consistent, automated, and dependable delivery process that can be centrally maintained and continuously improved.

### Phase 3: Operate and Improve

Golden paths should extend beyond deployment to simplify application operations and ongoing maintenance. Platform teams can provide shared services for monitoring application health, accessing logs and metrics, managing incidents, and maintaining reliability and performance.

Standardized workflows can also streamline configuration changes, scaling, software updates, vulnerability management, and resource optimization. By providing visibility into deployed applications, service ownership, and operational costs, platform teams help developers manage their applications more effectively while continuously improving the developer experience.

Goal: Make application operations more observable, reliable, and manageable through shared services and repeatable workflows.

## Building Golden Paths with Open-Source Tooling

Open-source projects offer many of the building blocks needed to create internal developer platforms and golden paths. Depending on an organization's architecture, these may include developer portals, repository templates, CI/CD engines, infrastructure automation, deployment tools, service catalogs, observability systems, and policy engines.

The guide will explore how these building blocks can work together to create complete developer workflows. It will emphasize:

- **Developer experience:** Reduce cognitive load and unnecessary steps.
- **Self-service:** Give teams direct access to routine capabilities.
- **Automation:** Replace repetitive manual processes with reliable workflows.
- **Interoperability:** Connect tools using open standards, APIs, and reusable integrations.
- **Consistency:** Establish supported defaults without unnecessary restrictions.
- **Reliability:** Make dependable operation part of the delivery experience.
- **Security and governance:** Incorporate appropriate guardrails into routine workflows.
- **Visibility:** Help teams understand their applications, deployments, and platform services.
- **Flexibility:** Support different application types, architectures, and organizational needs.
- **Continuous improvement:** Use feedback and measurable outcomes to evolve the platform.

No single tool or reference architecture is right for every organization. The guide will focus on patterns that can be adapted to different technology stacks and operating models.

## Platform Engineering as a Product

A successful internal developer platform is more than a collection of infrastructure components. It is a product that should be designed, documented, supported, and continuously improved based on the needs of developers.

The guide encourages platform teams to approach golden paths with a product mindset, beginning with an understanding of common developer tasks and the challenges that slow down software delivery. By identifying workflows where standardization and automation can provide the greatest value, platform teams can work directly with developers to create practical, reusable solutions. Golden paths should simplify repetitive tasks, reduce errors, and provide clear documentation while allowing flexibility when teams have requirements that fall outside the recommended approach.

Continuous improvement is an essential part of this process. Platform teams should gather developer feedback, monitor adoption, and measure how effectively golden paths improve the development experience. Metrics such as onboarding time, time to first deployment, deployment frequency, workflow completion time, reliability, support requirements, and developer satisfaction can help teams evaluate their progress. The emphasis should be on selecting meaningful measures that reflect organizational goals and using those insights to make golden paths more effective over time.

## Sharing Community Golden Paths

The CDF Platform Engineering SIG is developing this guide as a community-driven resource for sharing practical golden paths. By bringing together real-world experiences, open-source tooling, reusable workflows, and implementation guidance, the guide will help platform teams learn from one another and avoid reinventing common solutions.

Contributors are encouraged to share architectural patterns, templates, automation approaches, lessons learned, and methods for measuring platform effectiveness and developer experience. The goal is not to define a single universal golden path, but to build a growing collection of proven approaches that teams can evaluate, adapt, and improve to meet their own needs.

## Who Should Use This Guide?

This guide is intended for organizations and practitioners involved in designing, delivering, or consuming shared developer capabilities, including:

- **Platform engineers** building and operating internal developer platforms.
- **Application developers** looking for simpler, more predictable delivery workflows.
- **DevOps and SRE teams** improving automation, operations, and reliability.
- **Engineering leaders** seeking to improve developer productivity and consistency.
- **Security and compliance teams** working to integrate guardrails into developer workflows.
- **Open-source maintainers and contributors** sharing tools, integrations, and implementation experience.

The guide is designed to be useful to teams at different stages of maturity, from those creating their first golden path to organizations operating platforms at scale.

## Getting Involved

The Platform Engineering Golden Paths Guide is a work in progress led by the **Continuous Delivery Foundation Platform Engineering SIG**. Contributions, examples, and feedback from the broader community are welcome.

If your team has created a successful golden path—or learned from one that proved difficult to adopt—your experience can help others. The guide aims to turn those lessons into accessible guidance that strengthens the platform engineering community.

**The goal is to help platform teams make software development and delivery easier, more consistent, and more reliable by sharing practical golden paths built on open-source technologies.**

## Additional Resources

- [Continuous Delivery Foundation](https://cd.foundation/)
- [Continuous Delivery Foundation GitHub](https://github.com/cdfoundation)
- [Cloud Native Computing Foundation](https://www.cncf.io/)


## Disclaimer

This guide is intended as a community reference and educational resource. The examples and recommendations should be evaluated and adapted to each organization's technical environment, operational requirements, and policies. Inclusion of a project or approach does not constitute endorsement by the Continuous Delivery Foundation or the Linux Foundation.

This project is hosted by the [Continuous Delivery Foundation](https://cd.foundation/).

<img
  src="/images/cdf-stacked-color.png"
  alt="Continuous Delivery Foundation"
  style="display: block; margin: 0 auto 20px auto; width: 360px; max-width: 100%; height: auto;"
/>
