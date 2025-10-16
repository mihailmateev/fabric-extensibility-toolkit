# Workload Validation and Attestation

## Overview

This document provides guidance on validating your Microsoft Fabric workload against the required standards and completing the necessary attestation process before publishing to the marketplace.

## Validation Requirements

Before publishing your workload, you must ensure compliance with Microsoft Fabric's comprehensive requirements across multiple domains:

### 1. Workload Requirements

All workloads must meet the **Publish Workload Requirements** as defined by Microsoft. These requirements cover:

- **Business Requirements**: Value proposition, trial experience, monetization
- **Technical Requirements**: Authentication, OneLake integration, APIs, monitoring
- **Design/UX Requirements**: Common UX patterns, accessibility, internationalization
- **Security/Compliance Requirements**: Data protection, privacy, compliance certifications
- **Support Requirements**: Live site support, service health, documentation
- **Fabric Features Integration**: ALM, private links, data hub, lineage, sensitivity labels

📖 **Reference**: [Microsoft Fabric Publish Workload Requirements](https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements)

### 2. Item Requirements

Each item type in your workload must comply with specific item requirements including:

- **Functional Requirements**: Item CRUD operations, state management, collaboration
- **UX Requirements**: Item creation experience, editor patterns, ribbon controls
- **Integration Requirements**: Workspace integration, monitoring hub, settings panel
- **Data Requirements**: OneLake storage, data formats, lineage tracking

## Attestation Process

### Vendor Self-Attestation

Microsoft requires vendors to complete a formal **Vendor Self-Attestation** document that declares compliance with all publish workload requirements. This attestation serves as a formal commitment from your organization to Microsoft and your customers.

### Attestation Template

Use the provided attestation template to complete your vendor attestation:

📄 **Template**: [Vendor Attestation Template](./VendorAttestationTemplate.md)

The attestation document consists of three sections:

#### Section I: ISV Information
- Company and contact information
- Workload details (name, version, release date)

#### Section II: Attestation Declaration
- Formal attestation statement
- Signature and date from authorized vendor representative
- Commitment to compliance across all requirement categories

#### Section III: Detailed Requirements Checklist
- Comprehensive checklist for each requirement category
- Checkboxes for supported/not supported features
- Space for detailed explanations, exceptions, and variances
- Links to supporting documentation and compliance reports

### Hosting Requirements

> **Important**: Section III of the attestation (Detailed Requirements Checklist) must be hosted on your vendor website and kept up-to-date as new versions are released.

### Notification Requirements

You must notify Microsoft promptly prior to releasing changes if they materially impact the attestation, especially regarding:

- **Security** changes or vulnerabilities
- **Compliance** and privacy modifications
- **Design/UX** significant variances from guidelines
- **Data residency** or storage changes

## Validation Checklist

Use this checklist to track your validation progress:

### Pre-Attestation Validation

- [ ] Review all Publish Workload Requirements documentation
- [ ] Complete security assessment and testing
- [ ] Complete privacy review and assessment
- [ ] Verify Microsoft Entra authentication integration
- [ ] Test OneLake data integration
- [ ] Validate UX compliance with Fabric design guidelines
- [ ] Implement required monitoring and diagnostics
- [ ] Complete accessibility testing
- [ ] Test trial experience (if applicable)
- [ ] Verify marketplace integration
- [ ] Prepare support documentation and service health dashboard
- [ ] Document compliance certifications (ISO, SOC2, HIPAA, etc.)

### Attestation Completion

- [ ] Complete Section I: ISV Information
- [ ] Complete Section II: Attestation Declaration with authorized signature
- [ ] Complete Section III: Detailed Requirements Checklist
- [ ] Host Section III on vendor website
- [ ] Submit complete attestation to Microsoft
- [ ] Receive attestation approval from Microsoft

### Post-Attestation

- [ ] Maintain Section III documentation on vendor website
- [ ] Version attestation documentation with each release
- [ ] Monitor for new Microsoft requirements
- [ ] Notify Microsoft of material changes
- [ ] Update attestation when requirements change

## Supporting Documentation

Ensure you have the following documentation ready for attestation:

### Required Documentation

- **Security Assessment Reports**: Latest security testing and vulnerability assessments
- **Privacy Policy**: Public privacy policy URL
- **Compliance Certifications**: ISO, SOC2, HIPAA, or other relevant certifications
- **Terms of Service**: Customer-facing terms and conditions
- **Support Policy**: SLA, support channels, response times
- **Service Health Dashboard**: URL to live service health status page
- **Data Residency Documentation**: Commitments to data geography and compliance

### Recommended Documentation

- **Architecture Documentation**: System design and data flow diagrams
- **API Documentation**: Public APIs and integration guides
- **User Documentation**: End-user guides and tutorials
- **Admin Documentation**: Configuration and management guides
- **Disaster Recovery Plan**: BCDR strategy and procedures

## Validation Tools and Testing

### Functional Testing

- Test all item CRUD operations
- Verify authentication and authorization flows
- Test OneLake integration and data persistence
- Validate API integrations (Admin API, Public APIs)
- Test B2B collaboration scenarios

### UX/Design Testing

- Review against Fabric UX guidelines
- Test ribbon controls and item editor patterns
- Verify monitoring hub integration
- Test settings panel implementation
- Validate accessibility compliance (WCAG standards)

### Security Testing

- Penetration testing and vulnerability scanning
- Authentication and authorization testing
- Data encryption verification (in transit and at rest)
- Third-party cookie compliance verification
- Conditional access testing

### Performance Testing

- Load testing for expected capacity
- Resource utilization monitoring
- Scalability testing
- Performance metrics collection

### Compliance Testing

- Data residency verification
- Privacy controls validation
- Regulatory compliance testing (GDPR, CCPA, etc.)
- Audit logging verification

## Common Attestation Issues

### Frequent Challenges

1. **Incomplete Security Documentation**: Ensure all security assessments are current and comprehensive
2. **Missing Privacy Assessment**: Complete formal privacy review before attestation
3. **Data Residency Ambiguity**: Clearly document where data is stored and processed
4. **UX Guideline Variances**: Document and justify any deviations from Fabric UX guidelines
5. **Monitoring Gaps**: Implement comprehensive logging and diagnostics for 30+ days
6. **Support Documentation**: Ensure support channels and SLAs are clearly documented

### Best Practices

- **Start Early**: Begin validation process during development, not after completion
- **Document Continuously**: Maintain documentation throughout development
- **Test Thoroughly**: Don't skip security, privacy, or accessibility testing
- **Be Transparent**: Clearly document limitations and exceptions
- **Keep Updated**: Version attestation with each release
- **Communicate Proactively**: Notify Microsoft of material changes before release

## Resources

### Microsoft Documentation

- [Publish Workload Requirements](https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements)
- [Workload Development Kit Documentation](https://learn.microsoft.com/en-us/fabric/workload-development-kit/)
- [Fabric UX Guidelines](https://learn.microsoft.com/en-us/fabric/workload-development-kit/design-guidelines)
- [Security Requirements](https://learn.microsoft.com/en-us/fabric/workload-development-kit/publish-workload-requirements#security-requirements)
- [Marketplace Publishing Guide](https://learn.microsoft.com/en-us/azure/marketplace/)

### Toolkit Documentation

- [Vendor Attestation Template](./validation/VendorAttestationTemplate.md)
- [Project Structure](./Project_Structure.md)
- [Project Setup](./Project_Setup.md)

### Compliance Resources

- [GDPR Compliance](https://gdpr.eu/)
- [CCPA Information](https://oag.ca.gov/privacy/ccpa)
- [ISO Standards](https://www.iso.org/)
- [SOC 2 Compliance](https://www.aicpa.org/soc4so)

## Getting Help

### Support Channels

- **Microsoft Partner Support**: Contact your Microsoft partner representative
- **Workload Development Kit Forums**: Community support and discussion
- **Documentation Issues**: Submit feedback through Microsoft Learn
- **Technical Questions**: Use Microsoft Q&A for technical queries

### Contact Information

For questions about the attestation process or validation requirements, contact your Microsoft partner representative or the Fabric Workload Development team.

---

**Last Updated**: October 2025  
**Document Version**: 1.0
