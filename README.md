# SafeHaven App – Manual QA Project
**88 Test Cases | 26 Bugs | 11 Days | Nov 2025**

## Project Overview
Full manual testing cycle for **SafeHaven**, an Android smart home security app that manages and protects IoT devices (cameras, smart lights, etc.).

**Tester:** Ahmed Abozead  
**Duration:** 11 days (13 – 24 Nov 2025)  
**Device:** Redmi Note 14 – Android 12  
**Type:** Black-box Manual Testing

---

## Testing Objectives (All Achieved)
- 100% functional verification
- Security & negative scenario testing
- UI/UX consistency validation
- Clear, reproducible bug reports with evidence

---

## Project Timeline
| Phase              | Duration | Dates             | Status    |
|--------------------|----------|-------------------|-----------|
| Test Planning      | 1 day    | 13 Nov            | Done      |
| Test Case Design   | 3 days   | 14–17 Nov         | Done      |
| Test Execution     | 2 days   | 18–20 Nov         | Done      |
| Bug Reporting      | 2 days   | 21–23 Nov         | Done      |
| Final Reporting    | 1 day    | 24 Nov            | Done      |
| **Total**          | **11 days** | **13–24 Nov** | **100%** |

---

## Modules Tested
| Module              | TCs | Bugs | Pass Rate | Status      |
|---------------------|-----|------|-----------|-------------|
| Login               | 14  | 5    | 64%       | Critical    |
| Notifications       | 4   | 4    | 0%        | Critical    |
| Add Device (IP/QR)  | 11  | 4    | 64%       | Critical    |
| Settings            | 14  | 4    | 71%       | Warning     |
| Profile             | 12  | 2    | 83%       | Warning     |
| Support             | 7   | 3    | 57%       | Warning     |
| Registration        | 8   | 2    | 75%       | Warning     |
| Welcome / About     | 8   | 2    | 75%       | Warning     |
| Home & Devices      | 10  | 0    | 100%      | Passed      |
| **Total**           | **88** | **26** | **70.5%** | **Medium Risk** |

---

## Execution Summary
| Metric           | Value     |
|------------------|-----------|
| Total TCs        | 88        |
| Passed           | 62 (70.5%)|
| Failed           | 26 (29.5%)|
| Coverage         | 95%       |

---

## Bug Summary
| Severity | Count | %     |
|----------|-------|-------|
| Critical | 5     | 19%   |
| High     | 16    | 62%   |
| Medium   | 5     | 19%   |
| **Total**| **26**| **100%** (All Open)

### Critical Blockers
| ID           | Module        | Issue                                  | Severity  |
|--------------|---------------|----------------------------------------|-----------|
| BUG-LP-006   | Login         | No lockout → Brute force possible      | Critical  |
| BUG-PP-012   | Profile       | Change password without correct old one| Critical  |
| BUG-LP-007   | Login         | Google/Facebook login broken           | High      |
| BUG-CDP-008  | Notifications | No alert on new device                 | High      |
| BUG-CDP-020  | Add Device    | Accepts any invalid IP                 | High      |

---

## Quality Gate
**NOT READY FOR PRODUCTION**  
**Must fix 5 Critical + 16 High bugs before release**

### Immediate Recommendations
1. Add account lockout & rate limiting
2. Fix OAuth integration
3. Implement proper password validation
4. Fix notification system
5. Reject invalid IP formats
6. Full regression cycle after fixes

---

## Tools Used
- Microsoft Excel 2021 (Test Cases + Bug Tracking)
- Redmi Note 14 (Real device)
- Android native screenshots + AZ Screen Recorder
- Markdown for documentation

---

## Quick Links
- [88 Test Cases (Excel)](test-cases/test_case_safehaven-app.xlsx)
- [26 Bugs Report (Excel)](bug-reports/Bug-Report-safehaven-app.xlsx)
- [Screenshots & Videos](bug-reports/evidence/)
- [Test Plan](docs/Test_Plan.md) • [Strategy](docs/Test_Strategy.md)

---

## Final Words
This is **production-grade QA documentation** used exactly like this in real companies.

**Next Step:** Cycle 2 – Regression Testing after developer fixes

**Made with zero tolerance for broken flows and security holes**

**Ahmed Abozead** • Manual QA Engineer  
Email: ahmednb34963@gmail.com  
GitHub: https://github.com/ahmedabozead  
Updated: November 24, 2025

**Thank you for reviewing! Ready for collaboration or job offers**
