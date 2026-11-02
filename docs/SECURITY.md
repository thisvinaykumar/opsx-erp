# Security at OpsX

OpsX is built by **Opsx Apex Private Limited** with security as a core requirement.

- **Encryption at rest on devices:** Android kiosk tablets use SQLCipher (AES-256) for the local database.
- **Encryption in transit:** all edge-to-cloud sync uses TLS.
- **Tenant isolation:** every request and record is scoped to a tenant.
- **Dynamic RBAC:** least-privilege access, configurable per tenant, with audit logs.
- **Privacy:** live tracking is limited to duty hours.

## Reporting a vulnerability
Please report security issues privately through the contact options on [opsx.in](https://opsx.in/).
Do not open public GitHub issues for security vulnerabilities.
