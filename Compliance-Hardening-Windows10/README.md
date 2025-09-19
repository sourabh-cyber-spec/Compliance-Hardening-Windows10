# Windows 10 Compliance Hardening Project

This project demonstrates endpoint hardening and compliance alignment on a Windows 10 VM.  
Implemented security policies are aligned with **NIST SP 800-53** and **CMMC frameworks**.

##  Key Implementations
- **Password Policy Hardening**: Minimum 12 characters, complexity enabled, password history & expiry enforced.
- **Account Lockout Policy**: Lockout threshold after 5 invalid attempts, duration 15 minutes.
- **BitLocker Encryption**: Full-disk encryption applied (AES-128), ensuring data confidentiality.
- **USB Restrictions**: Blocked all removable storage devices to prevent data exfiltration.
- **Audit Logging**: Enabled Success & Failure auditing for logon, account management, policy changes, and system events.
- **Event Viewer Verification**: Verified logs (Event ID 4689) confirming real-time monitoring.

## Screenshots
Screenshots of all configurations and proof of execution are included in the `Screenshots/` folder:
- Password Policy
- USB Restriction
- BitLocker Status
- Audit Policy (multiple)
- Event Viewer Security Logs

## Outcomes
- Demonstrated compliance-driven hardening on Windows 10.
- Strengthened skills in **endpoint protection, policy enforcement, encryption, and auditing**.
- Useful for SOC, Security Analyst, and Compliance roles.

---

**Author**: Sourabh Kumar Singh  
