# 🔍 Localhost Vulnerability Assessment – macOS (Nessus Essentials)

This project documents a **basic vulnerability scan** of a macOS machine using **Tenable Nessus Essentials**, a widely-used free vulnerability scanner.

---

## 🧭 Objective

Perform a local vulnerability scan on my Mac (localhost) to identify potential security risks and gain hands-on experience with vulnerability management.

---

## 🛠 Tools Used

- **Nessus Essentials** (Community Edition by Tenable)
- **macOS 15.5**
- **Scan Target**: `127.0.0.1` (localhost)

---

## 🧪 Scan Setup & Process

1. ✅ Downloaded and installed Nessus Essentials on macOS.
2. ⚙️ Created a new scan using the **Basic Network Scan** template.
3. 🎯 Set the target as `127.0.0.1`.
4. 🟢 Ran a full vulnerability scan (~30–40 minutes).
5. 📊 Reviewed the scan results, focusing on high-severity issues.
6. 📌 Documented the findings and applied security recommendations.

---

## 📌 Top Vulnerabilities Found

| Severity | Vulnerability                                           | Recommendation                              |
|----------|---------------------------------------------------------|----------------------------------------------|
| High     | Google Chrome – Multiple Issues                         | Update Chrome to latest version              |
| High     | Cisco Webex App – Client-Side RCE (CVSS 8.8)            | Apply Cisco security update                  |
| High     | Oracle VirtualBox – April 2025 CPU Advisory (CVSS 8.1)  | Upgrade VirtualBox to patched version        |
| Medium   | Docker Desktop < 4.41.0 – Info Disclosure               | Upgrade Docker to ≥ 4.41.0                   |

More details in [`generated-detailed-report/`](./generated-detailed-report/)

---

## 📷 Screenshots

All steps and results are documented in the [`snapshots/`](./snapshots/) folder, including:

- Nessus installation
- Scan creation
- Running scan
- Vulnerability findings

---

## 🎯 Outcome

This scan helped me:

- Understand how Nessus scans a system.
- Identify and prioritize vulnerabilities.
- Learn how to interpret CVSS scores and plugin findings.
- Practice real-world mitigation using public advisories and updates.

---

## 📚 References

- [Tenable Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)
- [CVSS Scoring Guide](https://www.first.org/cvss/)
- [Common Vulnerabilities & Exposures (CVE)](https://cve.mitre.org/)

---

> ⚠️ **Disclaimer:** This scan was performed on my own device (`localhost`) in a controlled environment. All shared findings are non-sensitive and pose no risk to my system or others.

