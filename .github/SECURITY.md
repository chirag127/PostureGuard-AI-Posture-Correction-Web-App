# Security Policy for PostureGuard

The PostureGuard team and community take the security of our application very seriously. We appreciate your efforts to responsibly disclose your findings, and we will make every effort to acknowledge your contributions.

## Supported Versions

Only the latest stable version of PostureGuard is actively supported with security updates. We encourage all users to stay on the most recent release to benefit from the latest features and security patches.

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0.0 | :x:                |

## Reporting a Vulnerability

We are committed to working with the community to verify and address any potential vulnerabilities. Please follow this process for reporting:

**DO NOT report security vulnerabilities through public GitHub issues.**

Instead, please use the **private vulnerability reporting feature** provided by GitHub.

1.  Navigate to the [**Security Advisories**](https://github.com/chirag127/PostureGuard-AI-Posture-Correction-Desktop-App/security/advisories) tab in our repository.
2.  Click on the **"Report a vulnerability"** button to open a new advisory.
3.  Please provide as much information as possible in your report, including:
    *   A clear and concise description of the vulnerability.
    *   The type of vulnerability (e.g., Cross-Site Scripting, Remote Code Execution, etc.).
    *   The version of PostureGuard affected.
    *   Step-by-step instructions to reproduce the issue.
    *   Any proof-of-concept code, screenshots, or logs that can help us understand the impact.

### Our Commitment

-   We will endeavor to acknowledge receipt of your vulnerability report within **48 hours**.
-   We will provide you with regular updates on our progress in investigating and patching the vulnerability.
-   We will publicly credit you for your discovery (unless you prefer to remain anonymous) once the vulnerability has been addressed.

## Security Architecture & Practices

PostureGuard is built on a modern and security-conscious technology stack, including [Tauri](https://tauri.app/v1/references/security/), which leverages Rust for the backend. This architecture helps mitigate many common vulnerabilities found in traditional desktop applications.

We also utilize automated tools to enhance our security posture:
-   **Dependabot:** For automated dependency scanning and updates to keep our third-party libraries secure.
-   **GitHub Actions:** Our CI/CD pipeline includes steps for static analysis and code scanning to catch potential issues before they reach production.

Thank you for helping keep PostureGuard and its users safe.