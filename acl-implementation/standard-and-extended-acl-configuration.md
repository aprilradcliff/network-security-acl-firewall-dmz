# Standard and Extended ACL Configuration

## Overview

This artifact demonstrates the implementation and validation of both standard and extended Access Control Lists (ACLs) within a simulated enterprise network environment.

The objective was to restrict and permit traffic based on IP address and protocol while validating enforcement through connectivity testing.

---

## Environment

- Cisco router (Packet Tracer)
- Windows-based endpoints
- Segmented internal network
- Admin and kiosk host roles
- File server access validation

---

## Standard ACL Implementation

Standard ACLs were configured to filter traffic based on source IP address.

The ACL was applied to the appropriate router interface to enforce traffic restrictions between segments.

### Validation

- Verified allowed traffic using ping tests.
- Confirmed denied traffic behavior when ACL rule matched.
- Observed correct packet filtering at interface level.

---

## Extended ACL Implementation

Extended ACLs were configured to filter traffic based on:

- Source IP
- Destination IP
- Protocol (e.g., SMTP, POP3 as applicable)

Extended ACLs allowed more granular control compared to standard ACLs.

### Validation

- Confirmed restricted access to file server.
- Verified permitted traffic for authorized hosts.
- Tested rule order impact and enforcement behavior.
- Validated deny behavior through access attempts.

---

## Security Principles Demonstrated

- Least Privilege
- Network Segmentation
- Policy-Based Traffic Filtering
- Defense in Depth
- Configuration Validation & Troubleshooting

---

## Outcome

The ACL configurations successfully enforced controlled access between segmented hosts while maintaining required service availability for authorized systems.

This demonstrates applied experience with router-level traffic control, interface binding, and validation testing in a controlled lab environment.
