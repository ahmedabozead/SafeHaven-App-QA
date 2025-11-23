# Test Plan – SafeHaven Mobile App (Android)
**Version:** 1.0 | **November 2025**  
**Prepared by:** Ahmed Abozead – Manual QA Engineer  
**App Version:** v1.0.0 (Build 100)  
**Device:** Redmi Note 14 – Android 12

---

## 1. Introduction
This Test Plan defines the scope, approach, resources, and schedule for manual testing of **SafeHaven**, a smart home security application for managing and protecting IoT devices (cameras, smart lights, etc.).

**Goal:** Ensure the application is functionally correct, secure, stable, and user-friendly before production release.

---

## 2. Test Objectives
- Verify 100% of functional requirements
- Identify and document all defects with clear reproduction steps
- Validate security mechanisms (authentication, input validation)
- Ensure UI/UX consistency and usability
- Achieve ≥95% test coverage of critical flows

---

## 3. Scope

### In-Scope (11 Modules)
| # | Module                  |
|---|-------------------------|
| 1 | Welcome & Onboarding    |
| 2 | Registration            |
| 3 | Login (incl. OAuth)     |
| 4 | Home / Dashboard        |
| 5 | Connected Devices       |
| 6 | Add Device (IP & QR)    |
| 7 | Notifications           |
| 8 | Profile & Settings      |
| 9 | Support & Live Chat     |
|10 | About Us                |
|11 | Settings                |

### Out-of-Scope
- Performance/Load testing
- iOS compatibility
- Backend API testing
- Automation
- Penetration testing (beyond basic security)

---

## 4. Test Types & Strategy
| Type                  | Description                              | Priority |
|-----------------------|------------------------------------------|----------|
| Functional            | Feature verification                     | High     |
| UI/UX                 | Layout, usability, consistency           | High     |
| Negative & Validation | Invalid inputs, edge cases               | High     |
| Security              | Auth, password, brute-force protection   | Critical |
| Smoke                 | Critical path verification               | High     |
| Regression            | Re-test after bug fixes (Cycle 2)        | High     |

**Approach:** 100% Manual Black-Box Testing

---

## 5. Test Environment
**Hardware:** Redmi Note 14 (6GB RAM, 128GB, 6.43" AMOLED)  
**OS:** Android 12 – MIUI 13  
**App Build:** SafeHaven v1.0.0 (100)  
**Network:** Wi-Fi 100 Mbps  
**Test Data:** Valid + invalid accounts, dummy IoT devices

---

## 6. Tools
| Tool                  | Purpose                              |
|-----------------------|--------------------------------------|
| Microsoft Excel       | Test Cases & Bug Tracking            |
| Android Screenshots   | Visual evidence                      |
| Markdown + GitHub     | Documentation & repository           |
| WhatsApp / Gmail      | Team communication                   |

---

## 7. Test Deliverables
- Test Plan (this document)
- Test Cases Excel (88 TCs)
- Bug Report Excel (26 bugs + evidence)
- Test Summary Report
- Screenshots & Videos folder
- Regression Report (Cycle 2 – future)

---

## 8. Schedule (11 Days Total)
| Phase                | Duration | Dates           |
|----------------------|----------|-----------------|
| Test Planning        | 1 day    | 13 Nov          |
| Test Case Design     | 3 days   | 14–17 Nov       |
| Test Execution       | 2 days   | 18–20 Nov       |
| Bug Reporting        | 2 days   | 21–23 Nov       |
| Final Reporting      | 1 day    | 24 Nov          |

---

## 9. Entry & Exit Criteria
### Entry Criteria
- Stable build received
- Requirements finalized
- Test environment ready
- Test Plan approved

### Exit Criteria
- 100% execution of planned test cases
- Zero open Critical bugs
- Zero open High bugs in critical flows
- Pass rate ≥ 95% after regression
- Test Summary Report signed off

---

## 10. Risks & Mitigation
| Risk                          | Impact       | Mitigation                          |
|-------------------------------|--------------|-------------------------------------|
| Unstable build                | High         | Daily smoke test before execution   |
| OAuth integration failure     | Critical     | Priority testing + early reporting  |
| Security vulnerabilities      | Critical     | Intensive negative & security tests |
| Limited device coverage       | Medium       | Focus on risk-based testing         |

---

## 11. Approval
| Name              | Role             | Date        | Signature |
|-------------------|------------------|-------------|-----------|
| Ahmed Abozead     | QA Engineer      | Nov 2025    | Signed    |
| Development Lead  | Tech Lead        |             |           |
