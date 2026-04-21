# Project 1: Comprehensive Testing for E-commerce (Login & Search)

## 📋 Project Overview
- *Application Under Test:* Jumia Morocco (Demo)
- *Objective:* Verify core functionalities including user authentication and search filters.
- *Testing Type:* Manual Functional Testing.

---

## 📑 Test Scenarios

### 1. User Authentication (Login)
| Scenario ID | Test Scenario | Priority |
| :--- | :--- | :--- |
| TS_LOG_01 | Verify login with registered email and correct password | High |
| TS_LOG_02 | Verify login with unregistered email | Medium |
| TS_LOG_03 | Verify "Forgot Password" functionality | High |

### 2. Search & Filtering
| Scenario ID | Test Scenario | Priority |
| :--- | :--- | :--- |
| TS_SRCH_01 | Verify search results for a specific brand (e.g., Samsung) | High |
| TS_SRCH_02 | Verify price filter (Min/Max) updates results correctly | Medium |

---

## 🐛 Sample Bug Report
*Title:* Search results don't match the applied price filter.
*Severity:* Major
*Steps to Reproduce:*
1. Open Jumia.ma
2. Search for "Smartphone"
3. Apply price filter: 1000 DH - 2000 DH
4. *Actual Result:* Items with 3500 DH appear in results.
5. *Expected Result:* Only items between 1000-2000 DH should be visible.
