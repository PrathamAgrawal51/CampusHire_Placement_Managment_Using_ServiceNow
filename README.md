# 🚀 CampusHire – Placement Management System (ServiceNow)

CampusHire is a lightweight placement management system built on **ServiceNow**.  
It allows **Students, Placement Officers, and Recruiters** to manage the campus hiring process end-to-end.**

Name: Pratham Agrawal

![CampusHire-Pratham](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/Pratham-CampusHire.png)

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

### 1. CampusHire Home Dashboard
![Dashboard](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/1_Home_Dashboard.png)

### 2. Student Job Application Page
![Apply Job](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/2_Student_Job_Application.png)

### 3. Officer/Recruiter View
![Officer View](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/3_Officer_Nav_Menu.png)

### 4. Job creation form
![Job creation](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/4_Job_Form.png)

### 5. Application list with eligibility status
![Application list](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/5_Application_List.png)

### 6. Placement Result Table
![Placement Result](https://github.com/PrathamAgrawal51/CampusHire_Placement_Managment_Using_ServiceNow/blob/b798e1e4167ac19b3c4a7d53101dac632f62d67e/Screenshots/6_Placement_Result.png)

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
