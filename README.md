# Welcome to our Organization!
We are a healthcare technology company focused on improving patient outcomes and healthcare delivery through innovative software solutions. Our open-source repositories are dedicated to making healthcare data more accessible, secure, and interoperable.


# Repositories


## 1. Helth. server (FHIR Server with Google Cloud Healthcare API)
Our FHIR Server with Google Cloud Healthcare API is a backend for the FHIR-based client application, allowing it to store and retrieve data from the cloud. The server makes use of the Healthcare API offered by Google Cloud Platform (GCP) to provide a secure and scalable solution for managing patient data.

Objective: There is a lack of interoperability and availability of medical resources across institutions and even different departments of the same institution in the healthcare industry. The server is built as a proof of concept to tackle these issues by exposing an API which uses powerful queries using the Healthcare API nodejs library to expose ready-made endpoints that are made to fit the issues at hand.

The server uses a RESTful architecture to provide a standardized way of interacting with the Healthcare API. HTTP requests from the client are mapped to corresponding Healthcare API functions to perform requested operations on FHIR resources. Node.js Healthcare API functions offered by GCP are used to interact with the Healthcare API.


## 2. Helth. client
Our FHIR Validation Tool is an open-source command-line tool that validates FHIR resources against the FHIR specification. It uses the FHIR Validator library to validate resources and supports different output formats, making it easy to integrate into existing CI/CD pipelines.

Objective: FHIR resources must adhere to the FHIR specification to ensure data quality, interoperability, and consistency. The FHIR Validation Tool simplifies the validation process by providing a command-line tool that can be easily integrated into existing CI/CD pipelines.

The tool is written in TypeScript and uses the FHIR Validator library to validate resources. It supports different output formats, including JSON, XML, and YAML, making it easy to integrate with existing tools.


## Getting Started
To get started with our repositories, please refer to the README files of each repository.

For the FHIR Server with Google Cloud Healthcare API, please refer to the README.md file.
For the FHIR Validation Tool, please refer to the README.md file.


Our repositories are open-source and licensed under the Apache License 2.0 license.
