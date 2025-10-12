# Mobile Satisfaction Score Revamp – Project Overview

**Project Duration:** 13 Oct 2025 – 22 Nov 2025  
**Delivery Mode:** Agile – tracked via Azure DevOps (ADO)  
**Applications Involved:** Mobile Banking SDK (Android + iOS), Backend APIs (Java, OCP Deployment), Back Office Portal (React.js), Adobe Analytics Integration

## Team Composition
- 1 Android Developer
- 1 iOS Developer
- 1 React Developer
- 2 Java Backend Developers
- 2 QA Testers
- 1 Android New Joiner
- 1 React Deep Link Developer
- 1 Content Developer
- Architect, PM, Business Analyst (shared)

# Work Breakdown Structure

| # | Phase | Key Deliverables | Timeline | Owner(s) | Acceptance Criteria |
|---|---|---|---|---|---|
| 1 | **Requirements & Design** | BRD review; 7 journeys + logout flow; HLD/LLD; Adobe Analytics tagging matrix | 13–17 Oct | Architect + All | Design docs approved and signed off |
| 2 | **Backend Development** | API contract updates; schema changes; Adobe Analytics backend integration; OCP setup | 20–31 Oct | Java Devs | All APIs tested and deployed on OCP DEV |
| 3 | **Android SDK Revamp** | Popup revamp (7 journeys); logout reuse; Adobe Analytics integration | 20 Oct – 6 Nov | Android Dev + New Joiner | Popup and logout reuse work; analytics data validated |
| 4 | **iOS SDK Revamp** | Popup revamp (7 journeys); logout reuse; analytics tracking | 20 Oct – 6 Nov | iOS Dev | iOS build validated with analytics reporting |
| 5 | **React Back Office** | Add logout feedback tracking and Adobe analytics dashboard | 27 Oct – 6 Nov | React Dev + Deep Link Dev | Dashboard updated and analytics validated |
| 6 | **Testing & QA** | SIT, UAT, OAT across SDKs, backend, and portal | 10–21 Nov | QA Team | SIT/UAT/OAT passed with sign-offs |
| 7 | **Governance & Release** | Architecture/SIA approval; release note; rollback; ADO closure | 19–22 Nov | Architect + PM | Release deployed to PROD; SIA approved |
| 8 | **Project Management** | Sprint tracking; documentation; progress updates | 13 Oct – 22 Nov | PM | All ADO tasks linked; weekly reports submitted |

# Effort Summary

| Role | Effort (Days) | Effort (Hours) | Key Outputs |
|------|----------------|----------------|-------------|
| Android Developer | 15 | 120 | SDK popup revamp + logout reuse |
| iOS Developer | 15 | 120 | iOS popup revamp + analytics |
| React Developer | 5 | 40 | Back-office enhancement |
| Java Backend Devs (x2) | 20 | 160 | API + DB + OCP deployments |
| QA Testers (x2) | 10 | 80 | SIT, UAT, OAT validation |
| PM + Architect | 5 | 40 | Design review + release management |

# Acceptance Criteria Summary

### Functional
- Feedback popup revamp functional across 7 journeys on both platforms
- Logout reuse validated without regressions
- Adobe Analytics events captured (open, submit, close, logout)
- Back-office dashboard updated with logout score

### Technical
- API backward compatible with existing payloads
- OCP deployment successful in all non-prod environments
- SIT/UAT/OAT passed without critical defects

### Governance
- Architect & SIA approvals complete
- ADO work items closed with test evidence
- Release documentation and rollback plan uploaded

# Daily Risk & Productivity Tracker

| # | Date | Resource / Role | Planned Tasks | Actual Progress | Productivity % | Risk / Impediment | Category | Severity | Mitigation Plan | Owner | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 13-Oct | Android Developer | Review SDK architecture, setup environment | Completed | 100% | None | - | - | Continue next module | PM | Closed |
| 2 | 13-Oct | iOS Developer | Setup Xcode project and SDK link | Completed | 100% | None | - | - | Proceed to popup revamp task | PM | Closed |
| 3 | 13-Oct | Java Backend Dev 1 | Update feedback API swagger | In Progress | 80% | API dependency from UI team | Dependency | Medium | Align with UI mock API | Tech Lead | Open |
| 4 | 13-Oct | React Developer | Prepare analytics tagging spec | Completed | 100% | None | - | - | Submit for review | PM | Closed |
| 5 | 14-Oct | QA Tester 1 | SIT test case design | In Progress | 90% | Missing logout scenarios | Functional | Low | Add logout test cases | QA Lead | Open |
| 6 | 15-Oct | Android New Joiner | Review onboarding & SDK | Completed | 100% | Ramp-up phase | Resource | Low | Assign minor bug fixes | Android Lead | Closed |
| 7 | 16-Oct | Java Backend Dev 2 | Implement DB migration | Delayed | 50% | DB env access issue | Environment | High | Escalate to DevOps | PM | Open |
| 8 | 17-Oct | React Deep Link Dev | Review deep link handling | In Progress | 75% | Awaiting API confirmation | Dependency | Medium | Backend to finalize payload | Tech Lead | Open |
| 9 | 18-Oct | Content Developer | Update UX text for 7 journeys | Completed | 100% | None | - | - | Push updated JSONs | PM | Closed |
| 10 | 18-Oct | QA Tester 2 | Prepare regression suite | In Progress | 85% | SDK build delay | Schedule | Medium | Android build ETA 19th | QA Lead | Open |

## Risk Severity Legend
| Severity | Definition | Example |
|---------|------------|---------|
| Low | Minor delay or low impact risk | Missing test cases |
| Medium | Moderate risk with limited impact | API dependency or UI delay |
| High | Critical delivery blocker | Environment unavailability, DB issues |

## Monitoring & Reporting
- PM to update tracker daily in Confluence or link to Excel version
- Use conditional formatting for *Severity (H/M/L)*
- Include charts (Pivot tables) for: productivity trend by role, risks by category, open/closed task ratio

*Prepared for Confluence paste. Last updated: 11 Oct 2025.*
