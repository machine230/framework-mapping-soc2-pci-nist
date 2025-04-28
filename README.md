# SOC 2 and PCI DSS 4.0.1 to NIST 800-53 Mapping

## Overview
This project provides a simple mapping between SOC 2 Trust Services Criteria (TSC), PCI DSS 4.0.1 Requirements, and NIST 800-53 Rev 5 Controls.  
The goal is to help GRC professionals, auditors, and compliance teams align multiple frameworks efficiently.

## Purpose
Many organizations need to comply with multiple frameworks simultaneously.  
This lightweight mapping can support:
- Audit preparation
- Gap analysis
- Cross-framework reporting
- Control rationalization projects

## Structure
| SOC 2 Category | SOC 2 Criteria | PCI DSS 4.0.1 Requirement | NIST 800-53 Control | Notes |
|:--------------|:---------------|:-------------------------|:-------------------|:------|
| Security | CC1.1 | 5.2.1 | AC-2 | Account management |
| Security | CC5.1 | 8.3.6 | SC-12 | Data encryption at rest |
| Security | CC6.1 | 10.4.1 | AU-6 | Log review and audit trails |
| Availability | CC7.1 | 11.5.1 | IR-4 | Incident handling |
| Confidentiality | CC8.1 | 3.5.1 | SC-12 | Encryption of stored data |
| Processing Integrity | PI1.1 | 6.2.2 | CM-2 | Secure configuration management |
| Privacy | P1.1 | 3.2.1 | AC-8 | Data minimization and protection |

## How to Use
- Download the `mapping.csv` file.
- Customize mappings based on your organization's interpretation.
- Extend to other frameworks like ISO 27001, CIS Controls, etc.

## Disclaimer
This is an unofficial mapping provided for educational and general reference purposes.  
Please consult with your compliance or audit advisors for formal mappings.

## License
Distributed under the MIT License. See `LICENSE` for more information.
