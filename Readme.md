# Sukun Application: Prerequisites

## Overview

"Sukun" is a cloud-based application aimed at transforming the management of doctors' appointments and health records. To successfully develop and deploy the application on the IBM Cloud platform, several prerequisites need to be met. This document outlines the technical requirements and skills needed to build the application effectively.

## Technical Prerequisites

1. **IBM Cloud Account**
2. **GitHub Repository**
3. **Web Development Skills**
   - **HTML, CSS, JavaScript**
   - **Bootstrap**

4. **IBM Cloud Services**
   - **IBM Cloud Foundry**
   - **IBM Cloud Object Storage**

## Development Environment Setup

1. **Code Editor**

2. **IBM Cloud CLI**

3. **Git**: 

## Project Structure

We basically develop frontend part on Frontend Directory and backend Part on diffrent directory, TO achieve this we make two branch in the given repository. We Considered this structure:

```
Sukun-FrontendApp/
├── index.html  
│   
├── src/
│   ├── components
|   |-- App.css
│   └── App.js
|    
└── README.md

Sukun-BackendApp/
├── Apps
├── Sukun
│   ├── settings.py
│   └── urls.py
|
├── manage.py
└── README.md
```

## Implementation Steps

1. **Front-End Development**: Create the user interface for the application using HTML,CSS,React.js and Bootstrap. Ensure the design is intuitive and user-friendly, facilitating easy appointment scheduling and health record access.

2. **Appointment Scheduling Logic**: Plan a logic and then convert into python code with the help of django rest framework.

3. **Health Record Management**: Develop features to securely upload, retrieve, and display health records. Utilize IBM Cloud Object Storage for secure data storage.

4. **Deployment**: Deploy the application on IBM Cloud Foundry. Set up appropriate configurations and environment variables.


## Documentation

Thoroughly document the following aspects of your project:

1. **README**: We Create a detailed README file in our GitHub repository and describe how to set up and run the application.

2. **Code Documentation**: Comment in our code to explain its functionality and usage.



---
