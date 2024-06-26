# DKSR-Connector-SDK
Open Source DKSR Connector SDK enables writing Connector Code while using dependencies from Connector SDK libraries to send data to DKSR OUP. The aim of the Connector SDK is to reduce the effort of the connector development by providing an abstraction layer by providing interfaces and libraries for the developers. With the SDK, developers would be able to use the SDK libraries and use them directly, rather than writing their whole implementations. With the Connector SDK, it would be possible to write a huge part of the code as configurations rather than writing individual code for each functionality. The configuration abstracts a lot of code for the developers allowing them to use minimal effort to connect to the DKSR OUP and start sending streaming data through OUP’s interfaces. 

The Connector SDK heavily depends on the Vert.x technology (http://vertx.io/). Besides the core API, its advised to familiarise with Vert.x unit (http://vertx.io/docs/vertx-unit/java/) for testing instructions. Please refer to the list of open source Connectors published in [Connector Library](https://github.com/DKSR-Data-Competence-for-Cities-Regions/Connector_Library) for better understanding the use of Connector SDK and its use for building connectors.

![DKSR-logo](https://user-images.githubusercontent.com/102658834/171163305-cdd99910-1b93-4d74-be88-7c1d23fdcf0d.png)


# Licence Information
This code is published by DKSR Gmbh under the German Free Software License. Please refer to the document in the link for usage, change and distribution information:
https://www.hbz-nrw.de/produkte/open-access/lizenzen/dfsl/german-free-software-license

# Documentation

The documents below describe the different parts of the SDK and provide an overview of how to create SDK based connectors: 

1. Connector Components and their usage
 * [Data Flow for Connectors](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Data-Flow-for-Connectors)
 * [Connector Components](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Components-of-the-Connector)
 * [Details of Connector Verticles](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Details-of-Connector-Verticles)

2. Build and Test a Connector
 * [Software Components Required](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Software-Components-Required)
 * [Setting up the project](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Setting-up-the-project)
 * [Creating a connector](https://github.com/DKSR-Data-Competence-for-Cities-Regions/DKSR-Connector-SDK/wiki/Creating-a-connector)

   

