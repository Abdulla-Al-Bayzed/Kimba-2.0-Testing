# 🐞 Bug Report: Kimba Project

## 📌 Overview
This document contains **28 identified bugs** found during the manual testing of the **Kimba Project (Version 2.0)**.

---

## 🛠 Testing Environment
- **Operating System:** Windows 10  
- **Browser:** Google Chrome  
- **Testing Dates:** 13.06.2024 - 21.06.2024  
- **Total Testing Time:** 40 hours  

---

## 🔴 Defect Summary  
| **Severity** | **Number of Defects** |
|-------------|----------------------|
| Critical    | 1 (3.70%)             |
| Major      | 6 (22.22%)            |
| Average    | 15 (55.55%)           |
| Minor      | 6 (18.52%)            |
| **Total Defects** | **28** |  

---

## 🏷 Defects by Module  
| **Module**       | **Total Defects** | **Severity Breakdown** |
|----------------|--------------|------------------|
| Home          | 4            | 1 Major, 3 Average |
| File          | 11           | 1 Critical, 3 Major, 4 Average, 3 Minor |
| Edit          | 7            | 2 Major, 3 Average, 2 Minor |
| Options       | 4            | 1 Major, 2 Average, 1 Minor |
| Help          | 2            | 1 Major, 1 Average |

---

## 🔥 **Top Severity Issues**  

### 🔴 **Critical Issue (1 Bug)**
- **[QATC-849618] A folder is created instead of a zip file when creating a gallery.**  
  **Impact:** File export format is incorrect, which may cause compatibility issues.

### 🟠 **Major Issues (6 Bugs)**
1. **[QATC-849599] Help section displays "404 Not Found".**  
2. **[QATC-850208] Sharpness does not change when clicking on the slider.**  
3. **[QATC-850271] "Auto-Optimize Red-Eye-Reduction" button is not clickable.**  
4. **[QATC-850219] Drag-and-drop functionality is unresponsive.**  
5. **[QATC-850591] "Order by Random" is selected even when no picture is chosen.**  
6. **[QATC-850596] The application is not fully translated when the language is set to German.**  

### 🟡 **Average Issues (15 Bugs)**
7. **[QATC-850746] Pictures do not adjust automatically when the application is opened.**  
8. **[QATC-850702] File import sometimes fails without error messages.**  
9. **[QATC-850462] Undo/Redo history resets when switching modules.**  
10. **[QATC-850299] Cropped images sometimes revert to their original state.**  
11. **[QATC-850112] Volume slider has a delay in applying changes.**  
12. **[QATC-850233] Settings reset to default after restarting the application.**  
13. **[QATC-850405] UI overlaps in notification settings panel.**  
14. **[QATC-850128] Help menu loads slowly, causing unresponsiveness.**  
15. **[QATC-850189] Feedback submission fails without confirmation.**  

### 🟢 **Minor Issues (6 Bugs)**
16. **[QATC-850317] Typo in the error message: "Credntials" instead of "Credentials".**  
17. **[QATC-850321] Some icons in dark mode are not visible.**  
18. **[QATC-850328] FAQ page formatting issue (text alignment incorrect).**  
19. **[QATC-850335] Notification badge does not clear after viewing messages.**  
20. **[QATC-850344] Theme customization preview does not work properly.**  
21. **[QATC-850356] About section text truncates on smaller screens.**  

---

## 📌 Recommendations  
- **Fix Critical Bug First:** Ensure file export creates a zip instead of a folder.  
- **Improve UI/UX:** Resolve overlapping elements and text alignment issues.  
- **Enhance Stability:** Address settings and undo history reset problems.  

---

## 👥 QA Team  
- **Company:** a1qa  
- **QA Manager:** Dalia Dzhaafar  
- **QA Engineer:** Abdulla Al Bayzed  

---

📅 **Testing Dates:** 13.06.2024 - 21.06.2024  
⏳ **Total Testing Time:** 40 hours  

