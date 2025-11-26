# Security Overview

Security posture of **Global Edge CDN Platform**.

## Edge Security

- **WAF integration**: OWASP rules, bot protection
- **DDoS protection**: Shield Standard/Advanced
- **Geo-blocking**: Country-level restrictions
- **Signed URLs**: Time-limited access

## Data Protection

- **HTTPS only**: TLS 1.2+ enforced
- **Origin access**: OAI/OAC for S3
- **Field-level encryption**: Sensitive data
- **Custom SSL**: Your own certificates

## Access Controls

- **IAM policies**: Distribution management
- **Origin authentication**: Signed requests
- **Cache behaviors**: Per-path policies
- **Real-time logs**: Kinesis integration

## Compliance

- PCI-DSS compliant
- SOC 2 Type II
- HIPAA eligible
- GDPR ready

> See `SECURITY.md` for detailed configurations.
