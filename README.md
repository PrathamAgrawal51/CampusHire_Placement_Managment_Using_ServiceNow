# 🚀 CampusHire – Placement Management System (ServiceNow)

CampusHire is a lightweight placement management system built on **ServiceNow**.  
It allows **Students, Placement Officers, and Recruiters** to manage the campus hiring process end-to-end.

---

## 🎯 Features

- **Role-based Access**
  - `ch_student` → Apply for jobs, view eligibility.
  - `ch_officer` → Post jobs, view/manage applications, publish placement results.
  - `ch_recruiter` → Manage company jobs, shortlist candidates.

- **Core Tables**
  - **Company** – Stores recruiter companies.
  - **Job** – Job postings with eligibility rules (CGPA, Branch).
  - **Student** – Student records with branch, CGPA.
  - **Application** – Auto-generated when a student applies for a job.
  - **Placement Result** – Records selected students per company.

- **Automation**
  - Eligibility auto-check when applying.
  - Placement results auto-created when officer marks a student as *Selected*.

- **Reports & Dashboard**
  - Applications by Status (Donut Chart).
  - Selections per Company (Bar Chart).
  - Dashboard: *CampusHire Overview*.

---

## 🛠 Tech Stack

- **Platform**: ServiceNow (App Engine Studio)
- **Roles**: Student, Officer, Recruiter
- **Customization**: Tables, Forms, Business Rules, ACLs, Reports, Dashboard

---

## 📸 Screenshots

- `01_home_dashboard.png` – CampusHire Overview Dashboard  
- `02_student_view.png` – Student job application page  
- `03_recruiter_view.png` – Recruiter job posting page  
- `04_job_posting.png` – Job creation form  
- `05_application_flow.png` – Application list with eligibility status  
- `06_placement_result.png` – Placement result table  

---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow.git
   ```

2. Import the Update Set (if provided) into your ServiceNow instance:  
   - Navigate to **System Update Sets → Retrieved Update Sets → Import XML**.  
   - Commit the update set.  

3. Assign roles to test users:
   - `ch_student`
   - `ch_officer`
   - `ch_recruiter`

4. Create sample data:
   - A company + job
   - A few students (with CGPA/branch)
   - Test the flow by applying & verifying results.

---

## 🙌 Contributors

- Pratham Agrawal (Developer)

---

## 📄 License

MIT License – feel free to use/extend for learning purposes.
