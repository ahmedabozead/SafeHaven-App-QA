📱 SafeHaven App – Manual Testing Project
📌 Project Overview

SafeHaven is a smart home security application designed to protect and manage IoT devices such as cameras, lights, and other connected devices.
This project documents the full manual testing process conducted to ensure quality, stability, and user experience before production release.

Testing Type: Manual Functional & UI Testing
Platform: Android Mobile Application
Testing Duration: 11 Days (Nov 13 – Nov 24, 2025)
Testing Device: Redmi Note 14 (Android 12)

🎯 Testing Objectives
✅ Primary Goals

Verify all features work according to requirements

Identify and document defects with clear steps

Validate UI/UX consistency

Ensure proper input validation

Test navigation flow & error handling

Validate security features

✅ Success Criteria

Test coverage ≥ 90%

All Critical & High bugs documented

Clear reproduction steps

Evidence for all defects (screenshots)

Professional documentation

⏱️ Project Timeline
Phase	Duration	Dates	Status
Test Planning	1 Day	Nov 13, 2025	✅ Completed
Test Case Design	3 Days	Nov 14 – Nov 17, 2025	✅ Completed
Test Execution	2 Days	Nov 18 – Nov 20, 2025	✅ Completed
Bug Reporting	2 Days	Nov 21 – Nov 23, 2025	✅ Completed
Final Report	1 Day	Nov 24, 2025	✅ Completed
Total Duration	11 Days	Nov 13 – Nov 24	✅ 100%
📂 Testing Scope
✅ Modules Tested (11 Modules):
#	Module	Test Cases	Bugs	Pass Rate	Status
1	Welcome Page	5	1	80%	⚠️ Issues
2	Registration	8	2	75%	⚠️ Issues
3	Login	14	5	64%	❌ Critical
4	Home / Dashboard	6	0	100%	✅ Passed
5	Connected Devices	4	0	100%	✅ Passed
6	Notifications	4	4	0%	❌ Critical
7	Profile	12	2	83%	⚠️ Issues
8	Support	7	3	57%	⚠️ Issues
9	About Us	3	1	67%	⚠️ Issues
10	Add Device (IP / QR)	11	4	64%	❌ Critical
11	Settings	14	4	71%	⚠️ Issues
Total		88	26	70.5%	Medium Risk
📋 Testing Types Performed
Testing Type	Description	Coverage
Functional Testing	Verify core features	100%
UI / UX Testing	Layout & usability checks	95%
Positive Testing	Valid inputs	100%
Negative Testing	Invalid inputs	90%
Validation Testing	Input field validation	100%
Navigation Testing	Screen flow validation	100%
Integration Testing	Module interaction	85%
Smoke Testing	Critical flows	100%
📊 Test Execution Summary
Metric	Count	Percentage
Total Test Cases	88	100%
Executed	88	100%
Passed	62	70.5%
Failed	26	29.5%
Blocked	0	0%
Not Executed	0	0%

Coverage Metrics:
✅ Feature: 95%
✅ Modules: 100%
✅ UI: 90%
✅ Functional: 95%
✅ Requirements: 92%

🐛 Bug Summary
Bug Distribution by Severity
Severity	Open	Total	Percentage
Critical	5	5	19%
High	16	16	62%
Medium	5	5	19%
Low	0	0	0%
Total	26	26	100%
🔴 Open        | 26 bugs | 100% | ████████████████
🟡 In Progress | 0  bugs | 0%   | ░░░░░░░░░░░░░░
🟢 Resolved    | 0  bugs | 0%   | ░░░░░░░░░░░░░░
⚪ Closed      | 0  bugs | 0%   | ░░░░░░░░░░░░░░


All reported defects are currently in Open state awaiting development fixes.

🔥 Top Critical Issues
Bug ID	Module	Issue	Severity
BUG-LP-006	Login	No account lockout after failed attempts	🔴 Critical
BUG-PP-012	Profile	Password updated with wrong current password	🔴 Critical
BUG-LP-007	Login	OAuth Login not working	🟠 High
BUG-CDP-008	Notifications	No alert for new device	🟠 High
BUG-CDP-020	Add Device	Invalid IP accepted	🟠 High
🛠 Tools & Technologies
Category	Tool
Test Management	Microsoft Excel
Device	Redmi Note 14
Documentation	Markdown + Excel
Screenshots	Android Native
Communication	WhatsApp, Email
🚨 Quality Gate
❌ NOT READY FOR PRODUCTION

Blocking Issues:

No account lockout mechanism

OAuth login broken

Notification system not working

Invalid IP validation failure

✅ Recommendations:

Fix all Critical bugs

Fix all High bugs

Perform Regression Testing

Conduct Security Testing

📜 Version

Version: 1.0
Date: Nov 22, 2025
Author: Ahmed Abozead

✅ Final Status:
Testing Cycle: ✔ Completed  
Quality Gate: ❌ Not Ready  
Next Step: Regression Testing  
