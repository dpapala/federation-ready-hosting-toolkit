# Federation-Ready Hosting Toolkit for Small Operators

This repository hosts the initial specification and scope of the *Federation-Ready Hosting Toolkit for Small Operators*, a project proposed under the NGI Fediversity programme.

## Problem

Small, independent hosting operators increasingly host federated services, but the operational effort required to deploy, run, and maintain such services remains high. Federation-related operational knowledge is often scattered across application-specific documentation and informal practices, making it difficult to reuse across different services and environments.

## Scope

The toolkit focuses on operator-facing infrastructure concerns related to hosting federated services. It provides practical building blocks, reference setups, and operational guidance that support deployment and day-to-day operation in small-scale hosting environments.

The toolkit is designed to be self-hostable and usable without reliance on a central service, platform, or coordination layer.

## Operator assumptions

The toolkit is designed with the following assumptions in mind:
- single-node or small multi-node hosting setups  
- no dedicated SRE or operations team  
- limited automation, with manual operational steps acceptable  

## Non-goals

The toolkit explicitly does **not** aim to:
- introduce a hosting platform, control plane, or centralised service  
- orchestrate federation or alter federation protocols  
- provide application-specific deployment tooling  
- replace existing hosting or orchestration systems  

## Status

This repository currently contains the project scope and design notes. Implementation will be developed as part of the funded project, if approved.

## License

All contents of this repository will be made available under an open-source license compatible with NGI Fediversity requirements.

