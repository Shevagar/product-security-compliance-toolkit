# Secure Product Lifecycle Review

## Scope and governance
- Is the product boundary, intended use and supported lifetime defined?
- Are security roles and decision owners explicit?
- Are security assumptions and external dependencies recorded?

## Requirements and architecture
- Are assets, interfaces and trust boundaries identified?
- Has threat/risk analysis produced traceable security requirements?
- Are identity, authorization, key management, secure storage, update and logging architectures reviewed?

## Implementation and verification
- Are secure coding and dependency-management practices defined?
- Are security requirements covered by verification evidence?
- Are release artifacts protected for integrity and provenance?

## SBOM and vulnerability management
- Is an SBOM generated and associated with a product/version?
- Is there an intake, triage, remediation and disclosure process for vulnerabilities?
- Are remediation decisions and residual risks recorded?

## Updates and operations
- Are updates authenticated and protected against rollback where required?
- Are signing keys and certificates lifecycle-managed?
- Is there a supported security-update period and end-of-life process?

## Evidence readiness
- Can a reviewer trace risk -> requirement -> design/control -> verification -> release evidence?
