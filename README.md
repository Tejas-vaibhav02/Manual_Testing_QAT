# Manual Testing Project - Restful Booker Platform

## 📋 Project Overview

This repository contains comprehensive manual testing documentation for the **Restful Booker Platform**, a hotel booking and reservation management system. This project demonstrates manual testing skills including functional testing, date logic validation, business rule verification, and responsive design testing for a real-world booking application.

**Application Under Test:** [Restful Booker Platform](https://automationintesting.online/)

**Testing Duration:** 6 days (15-Jan-2026 to 20-Jan-2026)

**Project Type:** Manual Testing (Functional, Integration, Business Logic, UI/UX)

---

## 🎯 Testing Objectives

- Validate hotel booking workflows from date selection through confirmation
- Verify room availability tracking and calendar functionality
- Test booking creation, retrieval, and cancellation processes
- Validate contact form functionality for guest communications
- Ensure responsive design across desktop, tablet, and mobile devices
- Identify defects affecting core booking operations and data integrity

---

## 🔍 Testing Scope

### In Scope
✅ Hotel information display and presentation  
✅ Booking calendar and date selection logic  
✅ Room availability checking and updates  
✅ Booking creation workflow with validation  
✅ Booking retrieval and cancellation  
✅ Contact form functionality  
✅ Responsive design testing (Desktop, Tablet, Mobile)  
✅ Date range validation and business rules  

### Out of Scope
❌ Payment processing integration  
❌ Backend database testing  
❌ Security penetration testing  
❌ Performance and load testing  
❌ Email delivery verification  
❌ API testing  

---

## 📊 Test Execution Summary

| Metric | Count |
|--------|-------|
| **Total Test Cases** | 40 |
| **Passed** | 30 |
| **Failed** | 10 |
| **Blocked** | 0 |
| **Pass Rate** | 75% |

---

## 🐛 Defect Summary

| Severity | Count | Description |
|----------|-------|-------------|
| **Critical** | 4 | Date validation failures, booking reliability issues, availability sync problems |
| **Major** | 6 | Email validation gaps, calculation errors, mobile usability issues |
| **Medium** | 2 | UI inconsistencies, navigation issues |
| **Total Defects** | 12 | All defects documented with reproduction steps and screenshots |

---

## 🔑 Key Findings

### Critical Issues Identified
1. **Date Range Validation Failure** - System allows check-out dates before check-in dates
2. **Booking Creation Intermittent Failures** - Unreliable booking submission process
3. **Availability Not Updating** - Calendar doesn't reflect new bookings immediately
4. **Cancelled Bookings Remain Blocked** - Dates don't return to available status after cancellation

### Major Issues Identified
- Night count calculation errors for certain date ranges
- Email validation not enforced during booking creation
- Mobile date picker has unusably small touch targets
- Form layout overlaps on mobile viewports (360-400px width)

---

## 🛠️ Tools & Technologies Used

- **Browsers:** Chrome, Firefox, Edge (latest versions)
- **Testing Type:** Manual Functional Testing
- **Documentation:** Markdown, Excel/Google Sheets
- **Screenshot Tools:** Browser native tools, Snipping Tool
- **Developer Tools:** Browser DevTools for responsive testing and console monitoring

---

## 📝 Test Deliverables

1. **Test Plan** - Comprehensive strategy defining scope, approach, and criteria
2. **Test Scenarios** - 40 high-level scenarios covering all functional areas
3. **Test Cases** - 40 detailed test cases with step-by-step execution instructions
4. **Requirements Traceability Matrix (RTM)** - Mapping requirements to test cases
5. **Bug Report** - 12 defects documented with severity, steps to reproduce, and evidence
6. **Test Summary Report** - Executive summary with statistics, observations, and recommendations
7. **Screenshot Evidence** - Visual documentation of testing activities and defects

---

## 🎓 Learning Outcomes

This project provided hands-on experience with:
- Testing stateful applications where availability changes based on bookings
- Complex date logic validation and business rule enforcement
- Integration testing across interconnected features
- Identifying critical data integrity issues in reservation systems
- Mobile-first responsive design testing
- Professional test documentation and reporting standards

---

## 👤 About Me

**Name:** Tejas Vaibhav V  
**Role:** Manual Testing Professional  
**Email:** tejasvaibhav56@gmail.com  

---

## 📄 License

This project is created for educational and portfolio purposes.

---

## 🙏 Acknowledgments

- Application Under Test: [Restful Booker Platform](https://automationintesting.online/) by Mark Winteringham (Automation in Testing)
- Testing methodology based on industry best practices and ISTQB standards
- Project structure inspired by professional QA documentation frameworks

---

**Last Updated:** January 2026
