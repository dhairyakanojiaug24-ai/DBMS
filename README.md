# Assignment Management System

A simple web-based project to manage assignments,submissions, users, and grades. This system allows teachers to upload assignments, students to submit their work, and admins/teachers to track grades and manage all records.

---

## 🧪 Technologies Used

* **Frontend:** python
* **Database:** MySQL, XAMPP

---

## ▶️ How to Run the Project

1. Install XAMPP and start MySQL from XAMPP Control Panel.
2. Open this folder in VS Code.
3. In VS Code Terminal:
   - `python -m venv venv`
   - `venv\Scripts\activate`
   - `pip install -r requirements.txt`
4. Run `python scripts/create_schema.py`
5. Run `python scripts/seed_data.py`
6. Put a file named `sample_submission.pdf` in the project root (or the script will create a placeholder).
7. Run `python scripts/submit_demo.py`
8. Run `python scripts/list_pending.py` and `python scripts/late_submissions.py`

   ```
   ```

[http://localhost/your_project_folder](http://localhost/your_project_folder)



