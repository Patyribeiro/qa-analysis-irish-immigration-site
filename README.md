
# 🧪 QA Case Study – Irish Immigration Portal (INIS)

## 📌 1. Introduction

This project presents a real-world QA case study based on my experience using the Irish Immigration Portal (INIS) during a visa renewal process.

The goal was to identify inconsistencies in system behavior across different platforms (Desktop vs Mobile) and evaluate their impact on user experience.

---

## 🎯 2. Objective

- Validate system consistency across devices  
- Identify bugs affecting application status  
- Document issues with a professional QA approach  
- Propose improvements to enhance user experience  

---

## 🌐 3. Scope

The following features were tested:

- User login  
- "My Forms" dashboard  
- Application submission flow  
- Status visualization  
- Cross-platform consistency (Desktop vs Mobile)  

---

## 🧪 4. Test Environment

| Platform | Browser | Device |
|----------|--------|--------|
| Desktop  | Chrome | Windows |
| Mobile   | Chrome | Android |

---

## 🧾 5. Test Scenarios

| ID | Scenario | Description |
|----|---------|------------|
| TC001 | Login | User logs into the system |
| TC002 | View Forms | Access "My Forms" dashboard |
| TC003 | Submit Application | Submit renewal form |
| TC004 | Cross-platform | Compare Desktop vs Mobile behavior |

---

## 🐞 6. Bug Report

### 🔴 Bug Title:
Inconsistent application status between Desktop and Mobile

### 📍 Environment:
- Desktop: Chrome (Windows)  
- Mobile: Chrome (Android)  

### 🔁 Steps to Reproduce:
1. Log in to the INIS portal  
2. Navigate to "My Forms"  
3. Check application status  

### ✅ Expected Result:
The application status should be consistent across all devices.

### ❌ Actual Result:
- Desktop shows: No submitted forms  
- Mobile shows: Application successfully submitted  

---

## 📸 7. Evidence (Screenshots)

### 💻 Desktop View

![Desktop Screenshot 1](screenshots/desktop-1.png)  
![Desktop Screenshot 2](screenshots/desktop-2.png)  

👉 Observation:  
The system shows no submitted forms in the dashboard.

---

### 📱 Mobile View

![Mobile Screenshot 1](screenshots/mobile-1.png)  
![Mobile Screenshot 2](screenshots/mobile-2.png)  

👉 Observation:  
The system shows the application as submitted successfully.

---

## ⚠️ 8. Severity & Impact

- **Severity:** High  
- **Priority:** Critical  

### 🚨 Impact:
- Causes confusion about submission status  
- May lead users to resubmit applications  
- Risk of delays in visa processing  
- Reduces user trust in the system  

---

## 🧠 9. Analysis

This issue may be caused by:

- Data synchronization failure between frontend and backend  
- Caching issues across different devices  
- Inconsistent API response handling  

---

## 💡 10. Suggested Improvements

- Implement real-time synchronization across platforms  
- Display confirmation message after submission  
- Send automatic confirmation email to users  
- Ensure consistent API responses across devices  

---

## 📊 11. Test Results

| Test Case | Result |
|----------|--------|
| TC001 | Pass |
| TC002 | Fail |
| TC003 | Pass |
| TC004 | Fail |

---

## 📚 12. Lessons Learned

- Cross-platform testing is essential  
- Real-world testing improves QA skills  
- Clear feedback is critical for user experience  
- Small inconsistencies can have high impact  

---

## 🚀 13. Conclusion

This project demonstrates my ability to:

- Identify real-world issues  
- Perform structured QA analysis  
- Document bugs professionally  
- Evaluate user impact  

---

## 📎 14. Project Structure
