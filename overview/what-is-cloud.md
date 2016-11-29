---
title: What is cloud.gov.au
layout: page
---

<p class="abstract">cloud.gov.au is a platform that allows government teams to deploy, manage and scale their applications in the cloud.</p>

## The guiding principles of cloud.gov.au

1. Teams should spend the majority of their time building services that meet user needs: not setting up, operating and maintaining the underlying infrastructure
2. Small agile teams should be able to own the deployment of their application
3. Teams should be able to deploy updates to their application at human timescales rather than infrequent scheduled major releases.
4. Processes such as testing and deployment should be automated where possible
5. Small, simple, frequent deployments and more efficient, valuable and safer than large, complex, infrequent deployments

cloud.gov.au gives digital teams working on Australian Government services a platform to rapidly build and release products. It’s built to keep applications online even with large numbers of users and sharp increases in usage.

It handles the complexity of setting up and managing cloud infrastructure, so teams can spend their time doing the stuff that matters: building applications that meet user needs.

cloud.gov.au is built and managed by the DTA.

## cloud.gov.au is a Platform as a Service
The core of cloud.gov is a Platform as a Service (PaaS) built specifically for government work, based on the open source Cloud Foundry project hosted on Australian based AWS.

cloud.gov.au runs on top of Amazon Web Services infrastructure in the Sydney region. It is IRAP certified and accredited by the Australian Signals Directorate up to Unclassified DLM, and is listed on the ASD Certified Cloud Services List (CCSL).

Cloud Foundry allows many teams to securely interface with a single AWS instance(help me here - explain why we need CloudFoundry). This means the delivery team is responsible for their custom application code, and the cloud.gov.au platform takes care of the security and maintenance of everything underneath.

The cloud.gov.au team provides guidance to teams setup continuous deployment and continuious integration. We recommend using CircleCI and GitHub. Both of these services are not hosted in Australia and are not IRAP certified. You do not need to uses these tools to use cloud.gov.au.
