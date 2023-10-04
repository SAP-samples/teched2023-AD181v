[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-AD181v)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-AD181v)

# AD181v - Delve into ABAP Cloud on SAP BTP ABAP environment

## Description

This repository contains the material for the SAP TechEd 2023 session called AD181v - Delve into ABAP Cloud on SAP BTP ABAP environment.  

The ABAP RESTful application programming model is at the heart of the ABAP Cloud development model for building transactional, cloud-ready apps and services on SAP BTP, ABAP environment and SAP S/4HANA, in the cloud and on premise. Learn how to use RAP features, such as late numbering, side effects, and business events, to build your own SAP Fiori apps. We focus on the development capabilities in the ABAP development tools. 

## Overview

This session introduces attendees to the use of core features of the ABAP RESTful Application Programmig Model (RAP) offered to build modern, transactional SAP Fiori apps and services.

<details>
  <summary>Click to expand!</summary>

### Business Scenario

> In this hands-on session we will guide you through the development of the OData service of a SAP Fiori elements based _Travel Processing App_ with RAP, using the _managed_ business object (BO) runtime implementation with semantic key and late numbering. We will give you more details on the scenario in the different exercises.
>   
> The OData service you are going to implement is based on the _ABAP Flight Reference Scenario_. To set the business context, the scenario is the following: The department responsible for managing worldwide Travels for multiple Agencies is requesting you to build a new Fiori app with draft capabilities for processing (i.e. creating, updating and deleting) Travels. 
  
<details>
  <summary>Click to expand!</summary>
   
The resulting _Travel_ app is a List Report app with navigation to an Object Page for entry details that will look like this:
<!-- <img src="exercises/images/rap110_travelapp.png" alt="RAP110 Travel App" width="100%"> -->

**List Report**:
<img src="exercises/images/rap110_travelapp01.png" alt="RAP110 Travel App - List Report" width="100%">
  
**Object Page**: 
<img src="exercises/images/rap110_travelapp02.png" alt="RAP110 Travel App - Object Page" width="100%">

Below is the simplified _Flight_ data model underlying the app.

<img src="exercises/images/rap110_datamodel.png" alt="RAP110 Data Model" width="80%">

</details>


#### About the ABAP RESTful Application Programming Model (RAP)
   
> **ABAP Cloud** is the development model for building cloud-ready business apps, services and extensions on SAP BTP and all SAP S/4HANA editions, i.e. public or private cloud, and even on-premise. [Learn more...](https://blogs.sap.com/2022/12/22/abap-cloud/)
>
> The **ABAP RESTful Application Programming Model (RAP)** is the centerpiece of _ABAP Cloud_ for building transactional, cloud-ready SAP Fiori apps and Web APIs. RAP offers a set of concepts, tools, languages, and powerful frameworks provided on the ABAP platform. It supports the efficient development of innovative and cloud-ready enterprise applications, as well as the extension of SAP standard applications in an upgrade-stable way in the cloud and on-premise.

<details>
<summary>Click to expand!</summary>

RAP is an enabler for improving the user experience and innovating business processes in ABAP-based SAP solutions by leveraging SAP Fiori, SAP HANA, and the cloud. 
It is a long-term strategic solution for ABAP development on SAP’s flagship product SAP S/4HANA, in the cloud and on-premise (as of release 1909), as well as on the SAP BTP ABAP Environment.

The illustration below shows the high-level end-to-end development stack when working with RAP.  

<img src="exercises/images/rap_bigpicture.png" alt="RAP Big Picture" width="80%">

> **Read more**: [Modern ABAP Development with the ABAP RESTful Application Programming Model (RAP)](https://community.sap.com/topics/abap/rap)

</details>

</details>

## Requirements

The requirements to follow the exercises in this repository are:
1. [Create an user on the SAP BTP ABAP Environment Trial](https://developers.sap.com/tutorials/abap-environment-trial-onboarding.html)
2. [Install the latest Eclipse platform and the latest ABAP Development Tools (ADT) plugin](https://developers.sap.com/tutorials/abap-install-adt.html)


## Exercises

Start the exercises [here](https://github.tools.sap/D040081/rap_workshops/blob/master/rap1xx/rap110/README.md#-exercises).

## Presentation & Replay

Access the ...
- Session presentation: AD181v_RAP@SAP_TechEd_2023.pdf
- Session replay (_login required_)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
