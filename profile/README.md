# Welcome to our Organization!
We are a healthcare technology organization focused on improving patient outcomes and healthcare delivery through innovative software solutions. Our open-source repositories are dedicated to making healthcare data more accessible, secure, and interoperable.


# Repositories


## 1. Helth. server (Backend repository, FHIR Server with Google Cloud Healthcare API)
Our FHIR Server with Google Cloud Healthcare API is a backend for the FHIR-based client application, allowing it to store and retrieve data from the cloud. The server makes use of the Healthcare API offered by Google Cloud Platform (GCP) to provide a secure and scalable solution for managing patient data.

Objective: There is a lack of interoperability and availability of medical resources across institutions and even different departments of the same institution in the healthcare industry. The server is built as a proof of concept to tackle these issues by exposing an API which uses powerful queries using the Healthcare API nodejs library to expose ready-made endpoints that are made to fit the issues at hand.

The server uses a RESTful architecture to provide a standardized way of interacting with the Healthcare API. HTTP requests from the client are mapped to corresponding Healthcare API functions to perform requested operations on FHIR resources. Node.js Healthcare API functions offered by GCP are used to interact with the Healthcare API.


## 2. Helth. client (Frontend repository)
Helth. client is a frontend proof of concept application that provides a solution for managing patient records and encounters for healthcare practitioners. The app adheres to the FHIR standard and provides a standard way to store medical resource data. With an intuitive user interface and a range of features, the app enables healthcare practitioners to efficiently manage patient data. The app uses cloud storage and computing capabilities provided by Google Cloud Platform, making it scalable, cost-effective, and secure. Potential features include importing and exporting DICOM instances and viewing DICOM instances.


## Getting Started
To get started with our repositories, please refer to the README files of each repository.




Our repositories are open-source and licensed under the Apache License 2.0 license.
