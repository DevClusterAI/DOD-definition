# Security - Definition of Done

## Authentication
- [ ] Authentication mechanisms implemented according to specifications
- [ ] Multi-factor authentication enabled where required
- [ ] Password policies enforced (complexity, expiration, history)
- [ ] Account lockout after failed attempts implemented
- [ ] Session management follows security best practices
- [ ] Token-based authentication implemented correctly

## Authorization
- [ ] Role-based access control (RBAC) implemented
- [ ] Principle of least privilege applied to all user roles
- [ ] Authorization checks present on all protected resources
- [ ] API endpoints have appropriate permission controls
- [ ] Authorization bypass tests performed and passed
- [ ] Administrative functions properly restricted

## Data Protection
- [ ] Sensitive data encrypted at rest
- [ ] Data encrypted in transit (TLS 1.2+ or equivalent)
- [ ] Personally identifiable information (PII) properly protected
- [ ] Data anonymization/pseudonymization applied where appropriate
- [ ] Data retention policies implemented
- [ ] Secure key management practices followed

## Audit Logging
- [ ] Security events logged with appropriate detail
- [ ] Authentication attempts (success/failure) recorded
- [ ] Authorization failures logged
- [ ] Administrative actions logged
- [ ] Log tampering prevention measures in place
- [ ] Logs stored securely and retained according to policy

## Security Testing
- [ ] OWASP Top 10 vulnerabilities checked
- [ ] Dependency scanning for known vulnerabilities
- [ ] Static Application Security Testing (SAST) performed
- [ ] Dynamic Application Security Testing (DAST) if applicable
- [ ] Security code review completed
- [ ] All critical and high vulnerabilities addressed

## Verification Process
1. Run automated security scans
2. Perform manual security testing on critical paths
3. Review authentication and authorization implementation
4. Verify encryption implementation
5. Check logging and audit capabilities
6. Document any accepted risks with justification

## Tools
- SAST: ____________
- DAST: ____________
- Dependency Scanning: ____________
- Penetration Testing: ____________
- Compliance Checking: ____________

## Responsible Roles
- Primary: Security Engineer
- Support: Developers
- Verification: Security Architect
- Oversight: CISO/Security Team