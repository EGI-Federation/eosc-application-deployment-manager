
# EOSC Data Transfer Service

![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?label=License)
![Release](https://img.shields.io/github/v/release/EGI-Federation/eosc-application-deployment-manager?label=Release)
![GitHub issues](https://img.shields.io/github/issues/EGI-Federation/eosc-application-deployment-manager?label=Issues)


## European Open Science Cloud

The [European Open Science Cloud](https://eosc-portal.eu) (EOSC) gives European
researchers access to a wide web of [FAIR data](https://en.wikipedia.org/wiki/FAIR_data)
and science-related services. It was designed, delivered, and is contiunously improved under the
[Horizon Europe](https://commission.europa.eu/funding-tenders/find-funding/eu-funding-programmes/horizon-europe_en)
project, funded by the European Commission.

[EOSC](https://open-science-cloud.ec.europa.eu/) was initially delivered by the
[EOSC Future](https://eoscfuture.eu), while the [EOSC Beyond](https://www.eosc-beyond.eu)
project continues this development to deliver the next generation of EOSC core services.

## Application Deployment Manager

This is the [REST](https://restfulapi.net) API specification for the Application Deployment Manager (ADM)
core service of future EOSC nodes. This API can be used to:

- discover the tool blueprints available in the EOSC node
- discover the compute resource allocations of a user in the EOSC node
- deploy any of the tools from the EOSC node (or from other EOSC nodes) to any of the resource allocations of the user
- manage (query, update, stop, delete, etc.) the tool deployments of the user
