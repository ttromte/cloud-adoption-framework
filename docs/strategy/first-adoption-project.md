---
title: First cloud adoption project
description: Use the Cloud Adoption Framework for Azure to learn the processes for cloud adoption and the operation of workloads hosted in the cloud.
author: BrianBlanchard
ms.author: brblanch
ms.date: 5/19/2019
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: strategy
---

# First cloud adoption project

There's a learning curve and a time commitment associated with cloud adoption planning. Even for experienced teams, proper planning takes time: time to align stakeholders, time to collect and analyze data, time to validate long-term decisions, and time to align people, processes, and technology. In the most productive adoption efforts, planning grows in parallel with adoption, improving with each release and with each workload migration to the cloud. It's important to understand the difference between a cloud adoption plan and a cloud adoption strategy. You need a well-defined strategy to facilitate and guide the implementation of a cloud adoption plan.

<!-- docutune:ignore "Strategy, Plan, Ready, Adopt, and Operate phases" -->

The Cloud Adoption Framework for Azure outlines the processes for cloud adoption and the operation of workloads hosted in the cloud. Each of the processes across the Strategy, Plan, Ready, Adopt, and Operate phases require slight expansions of technical, business, and operational skills. Some of those skills can come from directed learning. But many of them are most effectively acquired through hands-on experience.

Starting a first adoption process in parallel with the development of the plan provides some benefits:

- Establish a growth mindset to encourage learning and exploration.
- Provide an opportunity for the team to develop necessary skills.
- Create situations that encourage new approaches to collaboration.
- Identify skill gaps and potential partnership needs.
- Provide tangible inputs to the plan.

## First project criteria

Your first adoption project should align with your [motivations](./motivations.md) for cloud adoption. Whenever possible, your first project should also demonstrate progress toward a defined [business outcome](./business-outcomes/business-outcome-template.md).

## First project expectations

Your team's first adoption project is likely to result in a production deployment of some kind. But this isn't always the case. Establish proper expectations early. Here are a few wise expectations to set:

- This project is a source of learning.
- This project might result in production deployments, but it will probably require additional effort first.
- The output of this project is a set of clear requirements to provide a longer-term production solution.

## First project examples

To support the preceding criteria, this list provides an example of a first project for each motivation category:

- **Critical business events:** When a critical business event is the primary motivation, implementation of a tool like [Azure Site Recovery](../migrate/azure-migration-guide/secure-and-manage.md#replicate-an-azure-vm-to-another-region-with-site-recovery-service) might be a good first project. During migration, you would use a tool like [Azure Migrate](../migrate/azure-migration-guide/migrate.md#azure-migrate) to quickly migrate datacenter assets. But during the first project, you could first use Azure Site Recovery as a disaster recovery tool. Reducing dependencies on disaster recovery assets within the datacenter before pragmatically planning the migration.

- **Migration motivations:** When migration is the primary motivation, it's wise to start with the migration of a noncritical workload. The [Azure setup guide](../ready/azure-setup-guide/index.md) and the [Azure migration guide](../migrate/azure-migration-guide/index.md) can provide guidance for the migration of your first workload.

- **Innovation motivations:** When innovation is the primary motivation, creation of a targeted dev/test environment can be a great first project.

<!-- docutune:ignore "data migration services" -->

Additional examples of first adoption projects include:

- **Business continuity and disaster recovery (BCDR):** Beyond Azure Site Recovery, you can implement multiple BCDR strategies as a first project.
- **Nonproduction:** Deploy a nonproduction instance of a workload.
- **Archive:** Cold storage can place a strain on datacenter resources. Moving that data to the cloud is a solid quick win.
- **End of support (EOS):** Migrating assets that have reached the end of support is another quick win that builds technical skills. It could also provide some cost avoidance from expensive support contracts or licensing costs.
- **Virtual desktop interface (VDI):** Creating virtual desktops for remote employees can provide a quick win. In some cases, this first adoption project could also reduce dependence on expensive private networks in favor of commodity public internet connectivity.
- **Dev/test:** Remove dev/test from on-premises environments to give developers control, agility, and self-service capacity.
- **Simple apps (less than five):** Modernize and migrate a simple app to quickly gain developer and operations experience.
- **Performance labs:** When you need high-scale performance in a lab setting, use the cloud to quickly and cost-effectively provision those labs for a short time.
- **Data platform:** Creating a data lake with scalable compute for analytics, reporting, or machine learning workloads, and migrating to managed databases using dump/restore methods or data migration services.

## Next steps

Learn about strategies for [balancing competing priorities](./balance-competing-priorities.md).

> [!div class="nextstepaction"]
> [Balance competing priorities](./balance-competing-priorities.md)
