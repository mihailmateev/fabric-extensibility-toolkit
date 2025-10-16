# Microsoft Fabric Vendor (ISV) Attestation Documentation Process

## Executive Summary

This Vendor Self-Attestation document is designed for vendors to formally declare their compliance with the requirements outlined by Microsoft for publishing workloads using the Microsoft Workload Development Kit (WDK). It includes an attestation of adherence to standards in areas such as functional compatibility, security, performance, reliability, supportability, and legal compliance. Additionally, an attestation checklist is included to provide further details regarding each requirement and identify any exceptions, variances or specific notes.

## Key Terms Defined

- **Vendor / Independent Software Vendor (ISV) / Partner**: The company or individual responsible for developing, distributing and maintaining the workload using Microsoft Fabric's Workload Development Kit. Vendors may also provide value-added services, support, or integration solutions to extend the capabilities of Microsoft workloads and assist customers in their deployment and management. In this document, the vendor attests to their compliance with the requirements set forth by Microsoft.

- **Customer**: The end user or organization that uses the workload developed by the vendor. Customers benefit from the functionalities provided by the workload, and their needs drive the requirements for reliability, performance, and supportability.

- **Workload**: A software component or solution designed to perform specific tasks on the Microsoft Fabric platform. Workloads typically interact with various services and require compatibility, reliability, and security measures to ensure seamless operation.

- **Microsoft Fabric Workload Development Kit (WDK)**: A toolkit provided by Microsoft that includes tools, guidelines, and best practices for developing and publishing workloads to run efficiently on the Microsoft Fabric platform.

- **Publish Workload Requirements**: A set of requirements and standards specified by Microsoft that each workload must meet to be published and deployed within the Microsoft environment. These include functional, security, performance, and compliance standards.

The document serves as an assurance from vendors to Microsoft and its Customers, ensuring that all requirements are met for the safe and efficient operation of workloads within the Microsoft ecosystem.

The appendix allows vendors to provide detailed information about each requirement, specifying whether it is supported, and detailing any exceptions or additional information for clarity.

## Process

The document is comprised of three sections. All sections are to be provided to Microsoft as Vendor's formal attestation, while **ONLY Section III** which details all of the specifics on the attestation are to be hosted on the partner's website for customers to reference.

> **Important**: Microsoft must be notified promptly prior to releasing any changes if the changes materially impact the attestation especially regarding security, compliance, privacy and/or if the change has significant variance from the design / UX guidelines.

---

## Section I: ISV Information

### Vendor Information

| Field | Value |
|-------|-------|
| **Company Name** | `<Required>` |
| **Company Website** | `<Required>` |
| **Address** | `<Required>` |
| **City** | `<Required>` |
| **State** | `<Required>` |
| **Postal Code** | `<Required>` |
| **Country** | `<Required>` |
| **Phone** | `<Optional>` |

### Primary Contact

| Field | Value |
|-------|-------|
| **Name** | `<Required>` |
| **Title** | `<Required>` |
| **Email** | `<Required / Email Alias OK>` |

### Workload Information

| Field | Value |
|-------|-------|
| **Workload Version** | `<Required>` |
| **Workload Name** | `<Required>` |
| **Release Date** | `<Required>` |

---

## Section II: Attestation

**To:** Microsoft Corporation  
**Subject:** Vendor Self-Attestation for Compliance with Microsoft Workload Development Requirements

We, the undersigned, **[Vendor Name]**, hereby confirm and attest that we have reviewed, understood, and complied with all applicable requirements as outlined in the Microsoft Workload Development Kit (WDK) documentation, specifically the Publish Workload Requirements located at [https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements](https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements).

### We hereby attest that:

1. **Functional and Design Compatibility**: We confirm that our workload complies with all Functional and Design compatibility requirements. We have ensured that our workload integrates seamlessly with the Microsoft Fabric environment and that it meets the technical, design and UX requirements to function properly across the Microsoft Fabric platform as outlined in the documentation.

2. **Security Compliance**: We attest that our workload adheres to the security standards mandated by Microsoft. Our workload complies with the data security, privacy, encryption, and identity requirements, ensuring the protection of users' data and mitigating risks as per Microsoft's guidelines.

3. **Performance and Scalability**: We confirm that our workload meets the performance and scalability requirements as outlined. Our workload is optimized to handle the expected workload size, meets the performance benchmarks, and can scale efficiently based on user demands.

4. **Reliability and Availability**: We affirm that our workload is reliable and meets the availability standards set forth by Microsoft. We have conducted appropriate testing to ensure that our workload will maintain continuous service and meet the required uptime metrics.

5. **Monitoring and Diagnostics**: We confirm that our workload incorporates proper monitoring and diagnostic capabilities as defined by the Microsoft guidelines. This includes implementing logging, telemetry, and diagnostic tools to ensure effective monitoring and issue resolution.

6. **Resource Efficiency**: We attest that our workload has been designed and optimized for efficient resource utilization. We have tested and confirmed that our workload uses memory, CPU, and other system resources in line with Microsoft's efficiency standards.

7. **Updates and Lifecycle Management**: We confirm that we have processes in place for the timely updating, patching, and managing of our workload throughout its lifecycle, including addressing any vulnerabilities and maintaining compatibility with future updates to the Microsoft Fabric platform.

8. **Supportability**: We attest that our workload is designed for long-term supportability, and we will provide timely technical support to resolve any issues that arise in the course of its deployment and use.

9. **Compliance with Legal and Ethical Standards**: We confirm that our workload complies with all relevant legal, regulatory, and ethical standards, including compliance with local and international data privacy laws, such as GDPR, and any other legal obligations as they pertain to workload deployment on the Microsoft platform.

10. **Documentation and Transparency**: We have provided clear, comprehensive, and up-to-date documentation for our workload to ensure that end-users and administrators can efficiently install, manage, and troubleshoot the workload.

11. **Testing and Validation**: We confirm that we have completed all required testing and validation procedures as outlined in the Microsoft Publish Workload Requirements. We have validated that our workload performs as expected in the Microsoft Fabric environment.

12. **Updates on New Requirements**: We commit to updating our workload to meet any new or evolving requirements that Microsoft may introduce, ensuring ongoing compliance and alignment with best practices.

### Declaration

We, **[Vendor Name]**, affirm that all the information provided in this self-attestation is accurate and that we have met or exceeded the requirements specified by Microsoft in the Publish Workload Requirements document. Details, exceptions and variances related to each of the attested categories can be found in **Section III: Publish Workload Requirements Attestation Checklist** of this document.

We understand that any failure to comply with these requirements may result in penalties or the suspension of our workload from the Microsoft Fabric platform.

**Signed,**

`[Signature Here]`  
**[Vendor Representative Name]**  
**[Vendor Representative Title]**  
**[Vendor Company Name]**  
**Date:** `[Insert Date]`

---

> **Note**: Section III is the only section that needs to be hosted on the vendor website and versioned as new releases are made if anything changes.
>
> Microsoft must be notified prior to releasing the changes if the change is material, especially if it impacts security, compliance, privacy and/or has significant variance from the design / UX guidelines.

---

## Section III: Publish Workload Requirements Attestation Checklist

We, the vendor, **[Vendor Name]**, confirm and attest to reviewing, meeting and complying with the requirements outlined in the Microsoft Fabric Workload Development Kit (WDK) specifically the Publish Workload Requirements located at [https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements](https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements).

The following sections document details, exceptions, or variances regarding the attestation of adherence to the Publish Workload Requirements.

---

### Business Requirements

#### 1. Value To Customers

The workload provides the following value to customers:

```
<Short paragraph here with text and/or bulleted items>
```

#### 2. Trial

We provide an easy and fast trial experience. The trial is available to the customer without waiting time (less than 5 seconds), and provides a free and easy way to explore the offered workload for a limited time in accordance with Microsoft guidelines for Trials.

- [ ] Yes
- [ ] No

```
<Description of the trial and the limits around the trial>
```

#### 3. Monetization

The workload is available on the marketplace for the customer to procure with or without a trial in accordance with the monetization guidelines.

- [ ] Yes
- [ ] No

```
<Link to the workload on marketplace>
```

---

### Technical Requirements

#### 1. Microsoft Entra Access

The workload(s) use Microsoft Entra authentication and authorization.

- [ ] No additional authentication and authorization mechanisms are used
- [ ] Additional authentication and authorization mechanisms are used for stored data in Fabric

**Details:**
```
1) Provide the endpoint / tenant ID for the Entra
2) If additional Non-Entra Authentication and Authorization Mechanisms are required, please outline details
```

#### 2. OneLake

Workloads integrate with OneLake to store data in the standard formats supported by the Fabric platform so that other services can take advantage of it.

- [ ] All data and metadata is stored in OneLake or Fabric Data Stores
- [ ] Not all data and metadata is stored in OneLake or Fabric Data Stores

```
<Clarify what data or metadata is stored outside of OneLake and/or Fabric>
```

#### 3. Microsoft Entra Conditional Access

Enterprise customers require centralized control and management of the identities and credentials used to access their resources and data via Microsoft Entra to further secure their environment via conditional access.

- [ ] The service works in its entirety even if customers enable this functionality
- [ ] The service works with limitations if customers enable this functionality
- [ ] The service does not work with Microsoft Entra Conditional Access

```
<Clarify limitations, constraints, exceptions if applicable>
```

#### 4. Admin REST API

Admin REST APIs are an integral part of Fabric admin and governance process. These APIs help Fabric admins in discovering workspaces and items, and enforcing governance such as performing access reviews, etc. Basic functionality is supported as part of the Workload Development Kit and doesn't need any work from Partners.

- [ ] Microsoft Fabric Admin APIs are being leveraged (/admin/*)
- [ ] No Microsoft Fabric Admin APIs are being used

#### 5. Customer Facing Monitoring & Diagnostic

Health and telemetry data needs to be stored for a minimum of 30 days including activity ID for customer support purposes, including Trials.

- [ ] Minimum 30 days requirement is adhered to
- [ ] Vendor stores the data for __ additional days beyond the minimum requirement

#### 6. B2B

The implementation of the workload is in line with Microsoft Fabric's sharing strategy focused on allowing customers to collaborate with their business partners, customers, vendors, subsidiaries etc. It also means users from other tenants can potentially be granted access to items partners are creating.

- [ ] Cross tenant B2B collaboration supported
- [ ] Workload Item Access only within the tenant

```
<Clarify limitations, constraints, exceptions if applicable>
```

#### 7. Business Continuity and Disaster Recovery

The vendor has a comprehensive Business Continuity and Disaster Recovery (BCDR) plans designed to tackle unplanned disasters and recovery steps.

```
<Either provide a link to the BCDR plan or Terms of Service (ToS) for their offering here along with a summary>
```

#### 8. Performance

The Workload implementation takes measures to test and track performance of their Items.

- [ ] Performance Metrics on workload performance are available via the monitoring hub
- [ ] Workload additionally includes a separate monitoring UI to test and track performance
- [ ] Performance tracking is not currently available to the end user however vendor support personnel can monitor, test, track performance via their internal instrumentation and monitoring systems

```
<Additional notes here>
```

#### 9. Presence

To ensure that customer expectations independent of their home or capacity region are met, vendors need to align with Fabric regions and clouds. Availability in certain regions also impacts your Data Residency commitments.

- [ ] Service availability and colocation/alignment in the following fabric regions

```
<List regions here>
```

- [ ] All or part of the service does not reside in Azure

```
<Additional notes here>
```

#### 10. Public APIs

Fabric Public APIs are the backbone of automation, enabling seamless communication and integration for both customers and partners within the Fabric ecosystem. Fabric Public API empowers users to build innovative solutions, enhance scalability, and streamline workflows.

- [ ] The workload uses Fabric Public APIs

---

### Design / UX Requirements

#### 1. Common UX

The workload and all item types the partner provides as part of it comply with the Fabric UX guidelines.

- [ ] The following variance and/or exceptions have been granted by Microsoft

```
<Exception and reason for variance and/or exception>
```

#### 2. Item Creation Experience

The item creation experience is in accordance with the Fabric UX System.

- [ ] Yes
- [ ] No

#### 3. Monitoring Hub

All long running operations need to integrate with Fabric Monitoring Hub.

- [ ] Yes
- [ ] No

#### 4. Trial Experience

The workload provides a Trial Experience for users as outlined in the design guidelines.

- [ ] Trial Supported
- [ ] Trial Not Supported

#### 5. Monetization Experience

The monetization experience is in line with the design guidelines provided.

- [ ] The monetization experience is completely integrated with the marketplace and compliant with the guidelines
- [ ] Bring Your Own License (BYOL)
- [ ] Free / Freemium
- [ ] Other

```
<Limitations here, outline details for Other and Freemium models, link to Terms of Service if applicable>
```

#### 6. Accessibility

The user experience is in compliance with the Fabric UX design guidelines for Accessibility.

- [ ] The user experience is completely compliant with the guidelines
- [ ] The following limitations exist

```
<Limitations here>
```

#### 7. World Readiness / Internationalization

English is supported as the default language. Localization, though optional, should be considered.

- [ ] English is the only supported language
- [ ] The following are the additional languages supported

```
<List of Languages>
```

#### 8. Item Settings

Item settings are implemented as a part of the ribbon as outlined in the UX guidelines.

- [ ] Yes
- [ ] No

```
<Clarify any variances/exceptions>
```

#### 9. Samples

Samples are optionally provided that preconfigure items of their type to help customers get started more easily.

- [ ] Samples not provided
- [ ] Samples for pre-configuration of items provided

#### 10. Custom Actions

Custom actions can be optionally provided as a part of the item editor.

- [ ] Custom Actions are not implemented
- [ ] Custom Actions implemented as part of Workload

```
<List of custom actions>
```

#### 11. Workspace Settings

Workspace settings provide a way that workloads can be configured on a workspace level.

- [ ] Supported
- [ ] Not Supported

#### 12. Global Search

Searching for items in Fabric is supported through the top search bar.

- [ ] Supported
- [ ] Not supported

---

### Security / Compliance Requirements

#### 1. Security General

Protection of customer data and metadata is of paramount importance. Workloads must go through a security review and assessment. Vendor attests that the security review and assessment was completed and will be periodically performed as enhancements and changes are made. Security issues discovered which could have a detrimental impact on the customer should be addressed promptly and customers notified where applicable.

```
Please outline all the security and compliance tests, attestations performed. The more detailed this is the easier it is for customers/Microsoft to review. This should include references to the latest security assessment reports.
```

#### 2. Privacy

Partners that build workloads also have a responsibility to protect that data when they access it. Every workload goes through a privacy assessment and a privacy review. Vendor attests that privacy review was completed and is periodically performed as enhancements and changes are made.

**Extra Requirements:**

- [ ] Publisher attests that only essential HTTP-only cookies are used by the Workload and only after positively authenticating the user
- [ ] Publisher attests that it is not using or relying on third-party cookies as part of their solution
- [ ] Publisher attests that is obtaining any Microsoft Entra token using the JavaScript APIs provided by the Fabric Workload Client SDK

```
Please outline all the privacy assessment and reviews performed. Links to latest reports and privacy policy provided here.
```

#### 3. Data Residency

Microsoft Fabric is making an Enterprise Promise around data not leaving the geography of the tenant for stored data and data in transit. As a workload in Fabric, customers need to be aware what your commitments to Data Residency are.

```
<Please summarize your commitments. For additional details on Data Residency and compliance please provide an existing link to your Data Residency and compliance support>
```

#### 4. Compliance

The publisher attests to the following security, data and compliance regulations and standards.

```
<Summarize how your app handles security, data, and compliance. Describe the Workload's security attributes and data-handling practices. If applicable to your customers, align with Fabric certifications.

Please list all standards compliance / reports / certifications here: ISO, SOC2, HIPAA and others

For additional details reference a link to your security, data and compliance>
```

---

### Support

#### 1. Live Site

Partner workloads are an integral part of Fabric that require the Microsoft support teams to be aware of how to contact you in case customers are reaching out to us directly.

**Microsoft direct vendor outreach:**

| Contact Method | Details |
|----------------|---------|
| **Contact Name/Team** | `<Vendor Primary contact Name / Team Here>` |
| **Number** | `<Optional Phone # here>` |
| **Email alias** | `<Email alias here>` |
| **Self Service portal** | `<Link to website>` |

#### 2. Supportability

Vendors are responsible for defining and documenting their support parameters (Service level agreement, contact methods, ...). This information needs to be linked from the Workload page and should always be accessible to customers. In addition, the Marketplace criteria need to be taken into account for the listing of the SaaS offer.

- [ ] Vendor attests that support information is published to the marketplace offering and available to users/customers directly via the workload

#### 3. Service Health and Availability

Vendors need to host a service health dashboard that shows their service health and availability to customers. This information can be included on the Supportability page.

**Service health dashboard can be found here:**
```
<URL to service health dashboard>
```

---

### Fabric Features

#### 1. Application Life Cycle Management (ALM)

Microsoft Fabric's lifecycle management tools enable efficient product development, continuous updates, fast releases, and ongoing feature enhancements.

- [ ] Supported
- [ ] Not Supported

#### 2. Private Links

In Fabric, you can configure and use an endpoint that allows your organization to access Fabric privately.

- [ ] Supported
- [ ] Not Supported

#### 3. Data Hub

The OneLake data hub makes it easy to find, explore, and use the Fabric data items in your organization that you have access to. It provides information about the items and entry points for working with them. If you're implementing a Data Item, show up in the Data Hub as well.

- [ ] Supported
- [ ] Not Supported

#### 4. Data Lineage

In modern business intelligence (BI) projects, understanding the flow of data from the data source to its destination can be a challenge. The challenge is even bigger if you built advanced analytical projects spanning multiple data sources, data items, and dependencies. Questions like "What happens if I change this data?" or "Why isn't this report up to date?" can be hard to answer.

- [ ] Supported
- [ ] Not Supported

#### 5. Sensitivity Labels

Sensitivity labels from Microsoft Purview Information Protection on items can guard your sensitive content against unauthorized data access and leakage. They're a key component in helping your organization meet its governance and compliance requirements. Labeling your data correctly with sensitivity labels ensures that only authorized people can access your data.

**Extra requirements:**
For partners that are using Export functionality within their Item they need to follow the guidelines.

- [ ] Supported
- [ ] Not Supported

---

## Additional Notes

Please use this section to provide any further explanations, references, or notes that may be relevant to your attestation:

```
<Additional Notes by Vendor>
```

---

## References

Please consolidate all relevant references here for completeness (e.g. support policy, compliance, ToS, service health etc.). Might seem redundant but useful to have it in a single place:

```
<List all relevant references here>
```

---

**Document Version:** 1.0  
**Last Updated:** `[Insert Date]`
