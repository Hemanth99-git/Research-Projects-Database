# 📊 Research Projects Database

This project is an SQL-based database schema designed to manage and store data related to research projects, employees, and funding agencies. It models real-world relationships between entities involved in collaborative research environments such as universities, tech labs, or grant-based research organizations.

---

## 🗂️ Features

- Stores information about:
  - **Projects**: Including name, budget, duration, manager, and funding agency.
  - **Employees**: With SSN, name, salary, and project assignments.
  - **Funding Agencies**: Holding name and address.
- Supports:
  - Many-to-many relationship between employees and projects.
  - Unique project names within each agency.
  - Each project funded by a **single agency**.
  - Managers are also employees and can work on multiple projects.

![Screenshot 2025-06-13 145112](https://github.com/user-attachments/assets/81329af1-a550-4806-b3c9-d85655bccf7b)


![project -1](https://github.com/user-attachments/assets/a43581ab-78c6-4ecb-a6e4-e9f93bbf622a)




