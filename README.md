# cyart-red-teaming
# 🔴 Red Team Capstone: Full Adversary Simulation

A comprehensive red team exercise demonstrating modern attack techniques from initial access to data exfiltration in a cloud environment.

## 🎯 Objectives

- Full-spectrum adversary simulation
- Cloud security testing (AWS)
- Detection capability evaluation
- Evasion technique validation

## 🛠️ Tools Used

- **C2**: Cobalt Strike, Metasploit
- **Cloud**: Pacu, awscli, ScoutSuite
- **Phishing**: Evilginx2
- **Evasion**: msfvenom, proxychains

## 📊 Results

### Attack Phases
| Phase | Tool | Technique | Status |
|-------|------|-----------|--------|
| Recon | Pacu | T1580 | ✅ |
| Phishing | Evilginx2 | T1566.001 | ✅ |
| C2 | Cobalt Strike | T1059.001 | ✅ |
| Privilege Escalation | Pacu | T1078.004 | ✅ |
| Exfiltration | awscli | T1048 | ✅ |

### Key Findings
- **Public S3 buckets** enabled data access
- **Overprivileged IAM roles** allowed admin escalation
- **Phishing & C2** activities went undetected
- **AV bypass** successful with obfuscated payloads
