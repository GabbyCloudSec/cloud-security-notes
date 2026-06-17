
# Security Groups

## Purpose

Security groups act as virtual firewalls for AWS resources.

## Components

- Inbound Rules
- Outbound Rules
- Protocols
- Ports

## Common Ports

| Port | Service |
|--------|---------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 3389 | RDP |

## Best Practices

- Allow only required traffic.
- Restrict source IP addresses.
- Use least privilege.

## Notes

Security groups are stateful and control traffic to EC2 instances.
