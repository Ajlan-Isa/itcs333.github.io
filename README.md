# ITCS333 – Internet Software Development (Group 44)

## 🧩 Course Project – 2025 / 2026 (First Semester)
This repository contains our team’s **course project** for ITCS333: *Internet Software Development* at the **University of Bahrain**.  
It includes all five tasks divided among group members.

---

## 👥 Group Members

| Task | Student Name | Student ID | Status |
|------|---------------|------------|--------|
| 1 – Admin Portal & User Management | **Ajlan Isa Ajlan Ramadhan** | **202303872** | ✅ Completed |
| 2 – Course Resources | *(Write Member 2 Name)* | *(Student ID)* | 🔜 In Progress |
| 3 – Weekly Breakdown | *(Write Member 3 Name)* | *(Student ID)* | 🔜 Planned |
| 4 – Assignments | *(Write Member 4 Name)* | *(Student ID)* | 🔜 Planned |
| 5 – Discussion Board | *(Write Member 5 Name)* | *(Student ID)* | 🔜 Planned |

---

## 🗂️ Project Structure

```
itcs333.github.io/
│
├── img/                 → images and favicons for the main course page  
├── md/                  → instructor’s project documentation  
├── pdf/                 → course outline (ITCS333_CS.pdf)  
│
├── task1/               → Task 1: Admin Portal (Ajlan Isa Ajlan Ramadhan)  
│   ├── admin/           → CRUD pages for students  
│   ├── includes/        → database connection file  
│   ├── index.html       → homepage/login  
│   ├── login.php        → login handler  
│   ├── logout.php       → logout handler  
│   ├── script.js        → form validation and interactivity  
│   └── style.css        → CSS styling  
│
├── index.html           → instructor’s main course page  
├── weeks.js  
├── weeks.json  
└── site.webmanifest
```

---

## ⚙️ How to Run Locally

1. **Start PHP server:**
   ```bash
   php -S localhost:8000
   ```

2. **Open in your browser:**
   ```
   http://localhost:8000/task1/index.html
   ```

3. **Database Setup**
   - Database name: `itcs333`
   - Import the `users` table into phpMyAdmin (from your SQL export).
   - Admin login: `admin@itcs333.com`
   - Password: (the hashed password created earlier)

---

## 🏁 Task Progress

✅ **Task 1:** Admin Portal & User Management – Completed by *Ajlan Isa Ajlan Ramadhan*  
🔜 **Task 2–5:** To be implemented by other group members.

---

## 📅 Submission Details

- **Course:** ITCS333 – Internet Software Development  
- **Instructor:** Dr. Abdullah Khalifa AlDoseri  
- **Course Coordinator:** Abdulla Ebrahim Subah  
- **Group:** 44  
- **Final Deadline:** November 29, 2025  

---

### 📝 Notes
- This repository is based on the original starter files provided by the instructor.  
- Each member must complete their assigned task folder (`task2`, `task3`, etc.) and push updates regularly.  
- Database credentials are intentionally minimal for security reasons.