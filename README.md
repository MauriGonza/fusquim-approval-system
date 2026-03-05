# 🏭 FAS — Fusquim Approval System

> Web-based invoice approval system developed for Grupo Heisecke / FUSQUIM (pharmaceutical industry).  
> Built with multi-role authentication, two-level approval workflow and GxP / FDA 21 CFR Part 11 compliance.

🟡 **Status: Functional prototype in development**

---

## 📋 Overview

FAS digitizes and controls the invoice approval process between external vendors and internal departments at FUSQUIM. Every action is logged with timestamps to meet GxP traceability requirements.

---

## 👥 User Roles

| Role | Access |
|---|---|
| **Vendor** | Submit invoices, view own history |
| **Assistant** | Review pending invoices, pre-approve or reject |
| **Approver** | Final approval or rejection of pre-approved invoices |
| **Admin** | Full access: audit logs, user management, error monitoring |

---

## ⚙️ Features

- 🔐 Multi-role authentication with password security policies
- 📄 Invoice submission with PDF upload and preview
- ✅ Two-level approval workflow (Assistant → Approver)
- 📋 Full audit logs with timestamps — exportable to Excel
- 👤 User management with role assignment and password reset
- ❌ Rejection with mandatory reason
- 🔗 SAP integration
- 📊 Error monitoring (SAP stamp errors)

---

## 🏗️ Approval Flow
```
Vendor submits invoice
        ↓
Assistant reviews → Pre-approve or Reject
        ↓
Approver reviews → Final Approve or Reject
        ↓
System logs action with timestamp (GxP compliance)
        ↓
Vendor notified of final status
```

---

## 🛠️ Stack

| Technology | Purpose |
|---|---|
| Python | Backend |
| SQL Server | Database |
| HTML / CSS / JS | Frontend |
| SAP | ERP Integration |
| GxP / FDA 21 CFR Part 11 | Regulatory compliance framework |

---
## 📋 Compliance

Designed to meet:
- ✅ **FDA 21 CFR Part 11** — Electronic records and signatures
- ✅ **EU Annex 11** — Computerised systems
- ✅ **GxP Data Integrity** — Audit trail, access control, traceability

---

## 👨‍💻 Author

**Mauricio González**  
IT Systems Engineer · AI Automation · Grupo Heisecke  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/gonzlezmauri)
