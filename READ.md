Appointify Web Platform Security Assessment
Vephla University – Department of Cybersecurity
Capstone Project · Team 3 · Academic Year 2025/2026

Phase 7 – Cybersecurity Review
This repository contains the comprehensive security testing documentation for the Appointify web platform.

Scope
- Authentication Security Testing
- Authorization & RBAC Validation
- XSS / HTML / NoSQL Injection Testing
- Data Exposure Analysis
- Business Logic Validation
- Infrastructure & Network Security
- TLS / SSL Review
- HTTP Security Header Assessment

Executive Summary
The Appointify platform demonstrates a strong security baseline. No critical vulnerabilities were successfully exploited. Major strengths include strong RBAC enforcement, XSS resistance, TLS 1.3 encryption, and strong booking logic validation.

High-Risk Findings
- No brute-force rate limiting
- No multi-factor authentication

Medium-Risk Findings
- Session timeout persistence
- Missing security headers
- Weak phone number validation
- Password reset email workflow issue

Repository Evidence
- `REPORT/` → Final PDF and DOCX report
- `EVIDENCE/videos/` → Silent screen recordings of test execution
- `EVIDENCE/screenshots/` → Burp Suite, browser, API, and terminal screenshots
- `SCANS/` → Nmap, Wireshark, and HTTP scan exports
- `APPENDIX/` → Evidence mapping appendices

Analyst:
- Muhammed Hazzan Olamilekan


Security Maturity Verdict
Moderate–Strong with targeted hardening required
