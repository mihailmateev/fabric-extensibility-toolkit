# Microsoft Fabric Workload Validation - Test Cases

> **Document Version:** 2025-10-16  
> **Status:** Official Validation Guidelines

This document outlines all validation requirements for Microsoft Fabric workloads.

---

## 1. Business Requirements

Requirements related to business value, marketplace presence, and customer-facing information

---

### 1.1 - Value To Customers

Workload must clearly articulate its value proposition, benefits, and use cases to help customers understand how it solves their business problems

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.2.1 - Terms of use link in Workload page is correct

Workload must provide a valid, accessible HTTPS link to terms of use in the manifest

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.2.2 - Privacy Policy link in workload hub is correct

Workload must provide a valid, accessible HTTPS link to privacy policy in the manifest

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.3.1 - Marketplace Offer has been published

Workload must have a published marketplace offer with a valid, accessible license URL

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.3.2 - Marketplace Offer Link in workload page is correct

The offer link needs to point to azuremarketplace or appsource.

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.3.3 - Workload publisher name is clear

Workload must display a clear, professional publisher name that helps customers identify the vendor

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.3.4 - Workload publisher name is aligned with marketplace

Publisher name must be consistent between the workload manifest and Azure Marketplace listing to avoid customer confusion

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4.1 - Attestation Link in workload page is correct

Workload must provide a valid, accessible HTTPS link to certification attestation documentation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4.2 - Getting started material exist

Workload must provide learning materials or getting started guides to help new users onboard successfully

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4.3 - At a glance section includes image or a video

Workload must include visual content (images or videos) in the 'At a glance' section to demonstrate functionality

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4.4 - Learning Material must land on static pages

Learning material links must direct users to stable, static documentation pages rather than dynamic or temporary content

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 1.4.5 - Documentation link in Workload page is correct

Workload must provide a valid, accessible HTTPS link to comprehensive product documentation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## 2. Technical Requirements

Technical implementation requirements including authentication, APIs, and integration

---

### 2.1.1 - Verified Entra App ID

Workload must register a valid Entra (Azure AD) application with proper GUID format and configuration

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.1.2 - Dependency on Fabric.Extend scope

Workload Entra app must include the Fabric.Extend scope with admin consent granted for proper integration

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.1.3 - Entra Redirect URL must return an html page tha just callse JS windows.close()

Authentication redirect URL must return a minimal HTML page that only executes windows.close() JavaScript without additional content

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.1.4 - Entra Scopes are kept to a limit

Workload should request only essential Entra scopes to minimize permissions and follow principle of least privilege

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 2.2 - OneLake

Workload must demonstrate integration with OneLake for data storage and management as documented in attestation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.3 - AAD Conditional Access

Workload must support Microsoft Entra Conditional Access policies for enterprise security requirements

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.4 - Customer Facing Monitoring & Diagnostic

Workload must provide monitoring and diagnostic capabilities for customers to troubleshoot and track usage

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.5 - B2B

Workload should support Business-to-Business (B2B) collaboration scenarios for enterprise customers

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 2.6 - Business Continuity and disaster recovery

Workload should implement business continuity and disaster recovery strategies to ensure data protection and service availability

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

### 2.7 - Performance

Workload must meet performance standards and provide responsive user experience as documented in attestation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.8 - Presence

Workload must implement presence indicators to show user activity and collaboration status

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.9 - Accessibility

Workload must meet accessibility standards (WCAG) to ensure usability for all users including those with disabilities

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 2.10 - World Readiness

Workload must support internationalization and localization for global markets including multiple languages and regions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## 3. Design & UX Requirements

User experience and design requirements following Microsoft Fabric design guidelines

---

### 3.1.1 - Workload has a clear name

Workload must have a clear, descriptive name that helps users understand its purpose at a glance

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2 - Workload icons and images are clear

Workload must provide custom, professional icons and images that are distinct from default placeholders and represent the brand

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.1 - Product icon is clear

Product icon must meet dimension requirements (240x240) and be visually clear and recognizable

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.2 - Favicon icon is clear

Favicon must be provided in the manifest with appropriate dimensions and clarity for browser tab display

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.3 - Custom actions Icon validation

Custom action icons must meet dimension requirements and be clear, recognizable representations of their functions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.4 - Create experience Icon validation

Create experience icons must meet dimension requirements and provide clear visual representation for item creation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.5 - Create experience Icon small validation

Small create experience icons must meet dimension requirements and remain clear at reduced sizes

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.6 - Tabs Icon validation

Tab icons must meet dimension requirements and be visually distinct to aid navigation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.2.7 - Tabs Icon active validation

Active tab icons must meet dimension requirements and provide clear visual indication of selected state

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.3 - Workload has a clear sub title

Workload must provide a clear, concise slogan/subtitle that complements the name and communicates key value

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.4 - Workload has a clear description

Workload must provide a comprehensive description that explains features, capabilities, and use cases

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.4.1 - Workload has a clear description in the Workload Hub Card

Workload Hub card must include a concise description optimized for the card display format

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.5 - Workload info page has banner at size 1920X240

Workload must provide a banner image with exact dimensions of 1920x240 pixels for the info page header

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 3.1.6 - Gallery videos are not allowed to show non product related ads

Gallery videos must focus exclusively on product features without displaying third-party advertisements or unrelated content

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## 4. Security & Compliance Requirements

Security, privacy, and compliance requirements for data protection and regulatory adherence

---

### 4.1.1 - Publisher must obtain user Entra ID token from the Fabric host before calling Fabric JS functions

Workload must obtain Entra ID tokens exclusively through the Fabric host before invoking any Fabric JavaScript functions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.2 - Publisher must only obtain any entra token using the JavaScript APIs provided by the Fabric Workload Client SDK

Workload must use only the official Fabric Workload Client SDK JavaScript APIs for obtaining Entra tokens, no custom implementations

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.3 - Publisher must not use third party cookies as part of their solution

Workload must not rely on third-party cookies; only essential HTTP-only cookies after authentication are permitted

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.1.4 - Entra App Name and publisher need to be aligned with the Workload

Entra application name and publisher must align with the workload name to ensure clear identity and avoid user confusion

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.2.2 - Publisher using only essential HTTP-only cookies after positively authenticating the user

Workload may only use essential HTTP-only cookies and only after successful user authentication

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.3 - Data Residency

Workload must comply with data residency requirements ensuring customer data stays in specified geographic regions

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 4.4 - Compliance attestation

Workload must provide attestation documentation demonstrating compliance with relevant regulatory and industry standards

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

## 5. Support Requirements

Support and documentation requirements for customer assistance and troubleshooting

---

### 5.1 - Livesite

Workload must have live site support processes and incident response procedures to maintain service availability

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 5.2.1 - Help Link in Workload Page is correct

Workload must provide a valid, accessible HTTPS link to help resources and support documentation

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 5.2.2 - Support contact is listed in the product details page

Product details page must clearly display support contact information for customer assistance

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 5.3 - Service Health & Availability

Workload should provide service health status page and availability metrics for customer transparency

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ⚠️ Optional | ⚠️ Optional |

---

## 6. Fabric Features

Integration with Microsoft Fabric platform features and capabilities

---

### 6.1 - ALM

Workload must support Application Lifecycle Management (ALM) capabilities for deployment and version control

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 6.2 - Private Links

Workload must support Azure Private Links for secure, private network connectivity

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 6.3 - Data Hub

Workload must integrate with Fabric Data Hub for centralized data discovery and management

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 6.4 - Data lineage

Workload must support data lineage tracking to show data flow and transformations across the platform

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

### 6.5 - Sensitivity Labels

Workload must support Microsoft Purview sensitivity labels for data classification and protection

**Stage Requirements:**

| Preview | General Availability |
|---------|---------------------|
| ✅ Required | ✅ Required |

---

---

## Additional Information

### Version History

This document is automatically generated.

---

*Generated by Microsoft Fabric Workload Validation System*  
*© 2025 Microsoft Corporation. All rights reserved.*
