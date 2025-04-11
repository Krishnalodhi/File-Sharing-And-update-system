# File-Sharing-And-update-system 

# 🎨 File Sharing & Update System for Engineering Drawings
###################### Drawit ############################

Drawit is a secure, role-based engineering drawing management system built with Flask and MySQL. It streamlines the sharing, versioning, and collaboration of technical drawing files within an organization.

---

## 🚀 Features

- 🔐 **OTP-based Registration & Login**
- 📤 **Drawing Upload System** with metadata (project, client, codes)
- 🗂️ Organized storage for:
  - Drawings
  - BOM (Bill of Materials)
  - Reference files
- 🔎 **Smart Search** by title, drafter ID, project code, etc.
- ✅ **Feedback & Review Workflow**
  - Request and respond to feedback
  - Track revision status
- 📈 **Personal Dashboard & Worklog**
  - View recent uploads, revisions, and feedback
- 📧 **Email integration** with Gmail for OTP communication

---

## 🛠️ Tech Stack

| Layer        | Tech                     |
|-------------|--------------------------|
| Backend      | Python, Flask            |
| Database     | MySQL                    |
| Auth         | Session-based + OTP Email |
| Email        | Flask-Mail (Gmail SMTP)  |
| Frontend     | HTML, Bootstrap 5        |
| File Storage | `static/files_upload/...`|

---



