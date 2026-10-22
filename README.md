
# Beam Trade-In App – Smartphone Evaluation & Trade-In Platform

**Author:** Vaishnavi

**Email:** vaishum3004@gmail.com 

**Client / Platform:** Unicorn  

**Platforms:** Android and iOS

---

## Introduction

The Beam Trade-In App is a mobile application developed for Unicorn to evaluate the condition of pre-owned smartphones and estimate their trade-in value through a structured, question-based assessment.

The application guides users through a series of device checks covering essential components such as the display, battery, camera, and overall functionality. Based on the assessment responses, the application determines an estimated trade-in value, helping make the valuation process more transparent, consistent, and convenient.

The platform simplifies smartphone trade-in operations by providing a guided digital assessment experience for both buyers and sellers.

---

## Key Tools and Technologies

- **Flutter:** Cross-platform mobile application development.
- **Dart:** Application logic and business workflow implementation.
- **REST APIs:** Communication between the mobile application and backend services.
- **JSON Parsing:** Processing API responses and displaying dynamic data.
- **State Management:** Managing assessment progress and dynamic UI updates.
- **Git & GitHub:** Version control and source code management.
- **TestFlight:** iOS application testing and distribution.

---

## Project Overview

The Beam Trade-In App streamlines the evaluation of pre-owned smartphones through a step-by-step assessment workflow. Users answer questions about the condition and functionality of their devices, allowing the application to support an estimated trade-in valuation.

### Key Features

- **Device Assessment:** Guides users through a structured questionnaire to evaluate smartphone condition.
- **Display Evaluation:** Supports assessment of the device's display condition.
- **Battery Assessment:** Includes battery-related checks as part of the evaluation workflow.
- **Camera Evaluation:** Covers camera condition and functionality.
- **Functional Checks:** Evaluates other relevant aspects of overall device functionality.
- **Trade-In Valuation:** Calculates or displays an estimated trade-in value based on assessment responses and configured valuation rules.
- **Dynamic User Interface:** Displays relevant questions and information throughout the assessment.
- **Backend Integration:** Connects with REST APIs to retrieve or submit relevant application data.
- **Cross-Platform Development:** Supports Android and iOS application workflows.

---

## Application Screenshots

### 1. Home Screen
<img width="170" height="350" alt="1" src="https://github.com/user-attachments/assets/e43d2938-a90b-4aa8-9b87-232fe606b9e8" />
<img width="170" height="350" alt="2" src="https://github.com/user-attachments/assets/04b8524d-ab1f-4a5e-81fb-2bafb1bf18cd" />
<img width="170" height="350" alt="3" src="https://github.com/user-attachments/assets/844f5677-49ab-4dd3-82ad-6b9356c8c00c" />
<img width="170" height="350" alt="4" src="https://github.com/user-attachments/assets/40965f3b-bd1d-466f-b774-484cc698dafd" />

The main screen through which users access the smartphone trade-in assessment.

### 2. Device Assessment
<img width="170" height="350" alt="5" src="https://github.com/user-attachments/assets/3367228c-23c1-4fdd-991c-7adc324b8166" />
<img width="170" height="350" alt="6" src="https://github.com/user-attachments/assets/759bbbee-997e-4c5e-a114-1ccaad108d97" />

A question-based workflow that guides users through the assessment of a pre-owned smartphone.

### 3. Component Evaluation
<img width="170" height="350" alt="7" src="https://github.com/user-attachments/assets/433a8115-892d-452c-a455-c16c8a894f5f" />

Evaluates key smartphone components, including the display, battery, camera, and overall functionality.


### 4. Estimated Trade-In Value
<img width="170" height="350" alt="8" src="https://github.com/user-attachments/assets/64d0c0d5-6b55-4fdb-8a36-7d41004f6ff3" />

Displays the estimated trade-in value based on the device condition and assessment responses.

### 5. Bonus Application
<img width="170" height="350" alt="9" src="https://github.com/user-attachments/assets/72aca393-75f4-402e-a182-952cffa4686c" />

Provides a dedicated interface for users to view and apply eligible bonuses or additional trade-in offers after the device evaluation.

### 6. Customer Verification
<img width="170" height="350" alt="10" src="https://github.com/user-attachments/assets/0920dd14-ffb1-4c39-9b5b-5e803917c195" />

Displays the customer verification interface to validate the customer's details before proceeding with the trade-in transaction.

### 7. Required Details and IMEI Information
<img width="170" height="350" alt="11" src="https://github.com/user-attachments/assets/92ff2e56-e008-4e36-a565-6e0e2f3a5769" />
<img width="170" height="350" alt="12" src="https://github.com/user-attachments/assets/157ccd34-90cc-48eb-af72-981f78789963" />

Allows users to enter the required device and transaction details, including the old device's IMEI 1 and IMEI 2, along with the new device's IMEI information, as applicable.

### 8. Payment Method Selection
Enables users to select their preferred payment method for the trade-in transaction.

### 9. Document Upload
Provides an interface for uploading the required customer documents to support verification and transaction processing.

### 10. Order Preview
Displays a summary of the trade-in order, including device details, applicable bonus, customer information, payment method, and other relevant transaction details for review before confirmation.

### 11. Bond Generation
Generates the transaction bond containing the relevant trade-in and customer details for confirmation and record-keeping.

### 12. Digital Signature
Allows users to provide a digital signature on the required transaction documents to confirm and authorize the process.

### 13. Invoice Generation
Generates the invoice with the relevant transaction details after the required confirmation steps are completed.

### 14. Order Successfully Placed
Displays the order success screen confirming that the trade-in order has been successfully placed.


## Development Process

### 1. Understanding the Requirements
Analyzed the smartphone trade-in workflow, including device assessment, bonus eligibility, customer verification, and order processing.

### 2. Designing the Assessment Workflow
Designed a guided questionnaire to evaluate the condition and functionality of pre-owned smartphones.

### 3. Implementing the User Interface
Developed responsive and reusable Flutter UI components for device assessment, bonus application, customer verification, document upload, and order processing.

### 4. Integrating Backend APIs
Integrated REST APIs to retrieve and submit relevant device, customer, and transaction data.

### 5. Implementing Assessment Logic
Handled assessment responses, application state, and the estimated trade-in valuation workflow.

### 6. Bonus Application and Customer Verification
Implemented UI workflows for applying eligible bonuses and completing customer verification before proceeding with the transaction.

### 7. Device Details and Document Management
Developed forms to capture required device information, including IMEI details, and interfaces for uploading customer documents.

### 8. Payment Method and Order Preview
Implemented payment method selection and an order preview screen to review relevant transaction details before confirmation.

### 9. Bond Generation and Transaction Confirmation
Worked on the workflow for generating the required transaction bond and capturing digital signatures where applicable.

### 10. Invoice Generation and Order Placement
Supported the final transaction workflow, including invoice generation and the order success confirmation screen.

### 11. Testing and Debugging
Tested the application workflow, identified functional issues, and implemented fixes to improve reliability and usability.

### 12. Application Build and Distribution
Worked on cross-platform build workflows and iOS testing and distribution through TestFlight.

---

## Challenges and Solutions

### Structured Device Assessment

**Challenge:** Presenting multiple device-condition questions in a clear and easy-to-follow sequence.

**Solution:** Organized the assessment into a guided workflow to help users provide relevant responses for smartphone evaluation.

### Dynamic Data Handling

**Challenge:** Managing assessment information and updating the interface based on user responses and backend data.

**Solution:** Implemented appropriate data handling, API integration, and UI state updates to support the assessment workflow.

### Trade-In Valuation Workflow

**Challenge:** Supporting a consistent estimated valuation based on the device's reported condition.

**Solution:** Worked on the assessment flow and application logic associated with processing responses and displaying the estimated trade-in value.

---

## My Role and Responsibilities

As a Flutter Developer at Beam Innovate Pvt. Ltd., I contributed to the development and maintenance of the Beam Trade-In mobile application for Unicorn.

My responsibilities included developing cross-platform UI components, implementing the smartphone assessment workflow, integrating REST APIs, handling JSON data, managing application state, supporting business logic, debugging issues, and assisting with application testing and distribution.

---

## Key Learnings

- Hands-on experience in developing cross-platform mobile applications using Flutter and Dart.
- Understanding question-based assessment workflows and dynamic UI rendering.
- Practical experience integrating REST APIs and handling JSON responses.
- Improved understanding of application state management and business logic.
- Experience debugging application issues and testing mobile workflows.
- Exposure to a real-world smartphone trade-in and estimated valuation use case.

---

## Conclusion

The Beam Trade-In App demonstrates the use of mobile technology to simplify the evaluation of pre-owned smartphones. Through a structured assessment workflow and estimated trade-in valuation, the application helps create a more convenient, transparent, and consistent experience for users involved in the trade-in process.

