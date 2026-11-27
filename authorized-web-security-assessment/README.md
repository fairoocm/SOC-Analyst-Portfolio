# Authorized Web Application VAPT Assessment

## Project Overview

A practical Web Application Vulnerability Assessment and Penetration Testing (VAPT) case study conducted with written institutional authorization.

The assessment focused on evaluating publicly accessible web application security configurations, identifying potential weaknesses, reviewing security controls, and documenting evidence-based observations.

## Assessment Scope

- Public-facing web application
- DNS and hosting boundary analysis
- HTTP and HTTPS configuration
- Security header inspection
- Session cookie security attributes
- Client-side form and CAPTCHA analysis
- URL routing and response behavior

## Tools & Technologies

- Kali Linux
- Nmap
- WhatWeb
- cURL
- OpenSSL
- DNS utilities
- WHOIS
- Firefox Developer Tools

## Verified Findings

| ID | Finding | Severity |
|---|---|---|
| VAPT-01 | Missing HTTP Security Headers | Low |
| VAPT-02 | Unhardened PHPSESSID Cookie | Low |
| VAPT-03 | Temporary HTTPS Redirect | Low |
| VAPT-04 | Client-Side CAPTCHA & No CSRF Token | Low |
| VAPT-05 | Soft-200 Routing & OG Path Concatenation | Informational |
| VAPT-06 | Outdated Front-End Library | Informational |

## Positive Security Observations

- Valid wildcard TLS certificate.
- Deprecated TLS 1.1 protocol disabled.
- Server version information suppressed.
- Contact form uses HTTPS transport.

## Methodology

1. Reconnaissance and information gathering.
2. DNS and hosting boundary analysis.
3. HTTP security header inspection.
4. TLS configuration assessment.
5. Session cookie analysis.
6. Browser DOM and client-side form inspection.
7. Findings documentation and risk classification.

## Testing Limitations

Active scanning was stopped when upstream hosting firewall filtering was observed. Shared hosting infrastructure was treated separately from the in-scope application.

No critical or high-severity vulnerabilities were confirmed within the assessment scope.

## Assessment Report

See the complete three-page case study in the `report` directory:

**Web Application VAPT Case Study — LinkedIn Carousel.pdf**

## Authorization & Responsible Testing

Testing was conducted with written institutional authorization.

The assessment followed defined scope boundaries and emphasized responsible testing, operational restraint, and evidence-based reporting.

## Author

**Bilal Fairoos**

Cybersecurity Student | Web Application Security | VAPT | Purple Teaming

GitHub: https://github.com/fairoocm

LinkedIn: https://www.linkedin.com/in/bilal-fairoos-cm-2b5892436
