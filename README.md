# Secure Network Architecture

## Overview
I implemented secure network segmentation between Finance, HR, and Database subnets to enforce least privilege and protect sensitive financial data. Firewall rules, deny‑by‑default policies, and tcpdump validation ensured only authorized Finance systems accessed the MySQL database.

## Key Features
- Finance subnet allowed controlled access to Database subnet (TCP 3306).
- HR subnet denied access to Database services.
- Firewall rules enforced segmentation and blocked unauthorized traffic.
- Traffic validation performed with tcpdump and connectivity tests.

## Alignment
This configuration aligns with PCI DSS, CIS Controls v8, Zero Trust concepts, and defense‑in‑depth strategies.

## Conclusion
The project demonstrates how segmentation and firewall controls reduce attack surface, limit lateral movement, and strengthen enterprise security posture.
