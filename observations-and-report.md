# 🛡️ Vulnerability Scan Report – macOS Localhost (127.0.0.1)

**Date:** June 26, 2025  
**Tool:** Nessus Essentials  
**Scan Type:** Basic Network Scan  
**Target:** 127.0.0.1 (macOS 15.5)

---

## 🔍 Scan Summary

- **Total Vulnerabilities Found**: 50
- **Severity Breakdown**:
  - Critical: 0
  - High: 3
  - Medium: 1
  - Low/Info: 46

---

## 🔴 High Severity Vulnerabilities

### 1. Google Chrome (Multiple Issues)
- **Severity**: HIGH (Mixed)
- **Description**: Multiple security issues affecting older versions of Google Chrome including potential RCE and privilege escalation.
- **Fix**: Update to the latest version via Chrome > About > Update.

---

### 2. Cisco Webex App – Client-Side RCE
- **Severity**: HIGH (CVSS 8.8)
- **Description**: Remote attackers can execute arbitrary code via crafted web content.
- **Fix**: Upgrade Webex to latest version per [Cisco advisory](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/).

---

### 3. Oracle VM VirtualBox (April 2025 CPU Advisory)
- **Severity**: HIGH (CVSS 8.1)
- **Description**: Vulnerabilities allowing guest VM users to escalate privileges or crash host system.
- **Fix**: Update VirtualBox from [official website](https://www.virtualbox.org/).

---

## 🟠 Medium Severity

- **Docker Desktop < 4.41.0**  
  *Fix:* Upgrade Docker to latest version for macOS.

---

## 🧼 Mitigation Plan

| Issue                             | Action Taken / Recommendation      |
|----------------------------------|-----------------------------------|
| Chrome issues                    | ✅ Updated Chrome                  |
| Webex RCE                        | 🔄 Updating Webex                  |
| VirtualBox vulnerabilities       | 🔄 Scheduled upgrade               |
| Docker Desktop disclosure        | 🔄 Scheduled upgrade               |

---

## 📷 Screenshots

See `/Report/screenshots/` folder for detailed images of scan setup, execution, and results.

---

## ✅ Conclusion

This scan provided hands-on experience using Nessus Essentials to detect local vulnerabilities. Remediation steps were initiated for all high-risk findings, and future scans will be scheduled post-update verification.

