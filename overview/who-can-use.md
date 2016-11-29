---
title: Who can use it
layout: page
---

<p class="abstract">cloud.gov.au is for agile teams building new applications using modern technology. It is not designed for moving legacy systems to the cloud.</p>

## Good fit for cloud.gov.au

- You have a technical team (internal or contracted) that can push applications to cloud.gov.au (See technical requirements below.)
- You work for an Australian government organisation.
- You understand that cloud.gov.au is a product under active development and will see changes in the future.
- Your application is Unclassified:DLM or lower.

### Technical requirements

- Your team has access to the cloud.gov.au API through the cloud.gov.au command line interface (compatible with Windows, Mac, and Linux).
- Your application is built using Ruby, Python, Node, Java or Go.
- Your application stores configuration in the environment.
- Your application uses one stateless process at a time (that can be horizontally scaled).
- Your application listens to a single port.
- Your dependencies are explicitly declared (such as requirements.txt for Python).
- You don’t rely on local storage for long-term data stores.

### Optional but recommended

- Your application can follow the 12-Factor App guidelines.

## Not a good fit

- Your application requires Oracle, SQL Server, or proprietary databases.

## Cannot use cloud.gov

- You work for a non-government organisation.
- You want to store protected or classified information
