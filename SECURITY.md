# Security Policy

The security of repositories, tools, and services under the `@bhubbard` account is taken seriously. This document outlines our default security commitment and reporting procedures across all repositories.

---

## Reporting a Vulnerability

**Please DO NOT open public GitHub issues or discussions for suspected security vulnerabilities.** Public disclosure before a fix is available puts users and production services at risk.

### Private Reporting Channels

1. **GitHub Private Vulnerability Reporting (Preferred):**
   Navigate to the **Security** tab of the specific repository and select **"Report a vulnerability"** (or use the repository's security advisory link). This opens a private, encrypted thread directly with the maintainers.

2. **Direct Contact:**
   If GitHub Private Reporting is unavailable, send an email to `hello@brandonhubbard.com` with the subject tag `[SECURITY: <repo-name>]`.

### What to Include in Your Report

To help investigate and patch quickly, please include:
- A clear description of the vulnerability and attack vector.
- The affected repository, branch, or release version.
- Step-by-step reproduction steps or a minimal Proof of Concept (PoC).
- Potential impact (e.g., Remote Code Execution, Denial of Service, data exposure, timing side-channels).
- Any proposed mitigations or patch suggestions if available.

---

## Response Timeline

We adhere to the following SLA:

- **Initial Acknowledgment:** Within **24 to 48 hours** of receiving your report.
- **Triage & Severity Assessment:** Within **3 business days**.
- **Patch Development & Testing:** Priority based on severity (Critical/High addressed with urgent priority).
- **Public Advisory & Release:** Coordinated disclosure once the patch is released and users have an upgrade path.
