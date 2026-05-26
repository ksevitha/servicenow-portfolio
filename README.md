# servicenow-portfolio
ServiceNow development projects, labs and notes | CSA | PDI | Flow Designer
# 🔧 ServiceNow Portfolio

<div align="center">

[![ServiceNow](https://img.shields.io/badge/ServiceNow-00C2FF?style=for-the-badge&logo=servicenow&logoColor=white)](https://servicenow.com)
[![CSA](https://img.shields.io/badge/CSA-Certified-green?style=for-the-badge&logoColor=white)](https://nowlearning.servicenow.com)
[![PDI](https://img.shields.io/badge/PDI-dev395038-blue?style=for-the-badge&logoColor=white)](https://servicenow.com)
[![ITIL](https://img.shields.io/badge/ITIL-Foundation-orange?style=for-the-badge&logoColor=white)](https://peoplecert.org)

*ServiceNow development projects, labs and hands-on builds*

</div>

---

## 👩‍💻 About This Portfolio

Hi! I'm **Krishna Sevitha**, a Technical Support Engineer at **MassMutual India** transitioning to **ServiceNow Developer**.

This repo documents all my **hands-on ServiceNow development work** — custom applications, labs, configurations and experiments on my Personal Developer Instance (PDI: dev395038).

```yaml
current_role:  Technical Support Engineer @ MassMutual India
experience:    2.5 years Enterprise ITSM
pdi:           dev395038.service-now.com
certifications:
  - ServiceNow CSA (June 2026)
  - ITIL Foundation (June 2026)
  - ServiceNow CAD (Target: Q3 2026)
```

---

## 🚀 Projects Built

---

### 1️⃣ IT Asset Tracker Application
> Complete custom ServiceNow application built independently from scratch

**What I built:**
- Custom table `u_it_asset` extending Task
- Fields: Asset Name, Asset Type, Asset Status, Serial Number, Department, Purchase Date
- Choice fields with custom values (Laptop, Monitor, Phone, Accessory)
- Form & List view configuration
- Application Menu with multiple modules
- Custom role `it_asset_user`
- ACL rules (read, write, create, delete)
- Tested with user impersonation

**Key concepts demonstrated:**
```
✅ Table creation & inheritance
✅ Field configuration (String, Choice, Date, Reference)
✅ Form Builder & List Layout
✅ Application Menus & Modules
✅ Role-based security (ACL)
✅ Impersonation testing
```

---

### 2️⃣ HHD Configuration Tracker
> Hardware device tracking application with data import

**What I built:**
- Custom table `u_hhd_configuration` extending Task
- Import Set with Transform Map
- Field mapping (u_name → Device Name, u_asset_tag → Serial Number)
- Coalesce field to prevent duplicates
- 20 records imported from Excel
- CMDB CI relationships

**Key concepts demonstrated:**
```
✅ Import Sets & Transform Maps
✅ Field mapping & Coalesce
✅ Data migration from Excel
✅ CMDB & CI Relationships
✅ Dependency Map visualization
```

---

### 3️⃣ Knowledge Base Management
> KB article creation, approval workflow and user criteria

**What I built:**
- Imported Word document as KB article
- Configured approval workflow (Bernard Laboy approver)
- Published article to Service Portal
- Created User Criteria (HHD Users Only)
- Tested portal visibility

**Key concepts demonstrated:**
```
✅ KB article import from Word
✅ Approval workflows
✅ User Criteria configuration
✅ Service Portal integration
✅ Access restriction testing
```

---

### 4️⃣ Infinity HHD Service Catalog Item
> Complete service catalog item with variables and pricing

**What I built:**
- Created catalog item using Catalog Builder
- Added variables (Device Model, Justification, Assigned To)
- Configured price modifiers per choice
- Stage sets for request tracking
- Flow Designer automation

**Key concepts demonstrated:**
```
✅ Catalog Builder
✅ Variables & Variable Sets
✅ Price modifiers
✅ Service Catalog flows
✅ Request fulfillment
```

---

### 5️⃣ MassMutual Stage Notification Flow
> Real-world automation eliminating 10-12 daily status calls

**What I built:**
- Flow triggered on Request status change
- Email notifications at every stage:
  - Submitted → User notified
  - In Progress → User notified
  - Completed → User notified
- High urgency detection → Manager notified
- Slack integration for team channels

**Business impact:**
```
Before: 10-12 status check calls daily ❌
After:  0 calls needed — auto notifications ✅
Time saved: ~60 mins/day agent time!
```

**Key concepts demonstrated:**
```
✅ Flow Designer
✅ Triggers & Conditions
✅ Email Spoke
✅ Slack Spoke
✅ Business process automation
```

---

## 📁 Repository Structure

```
servicenow-portfolio/
│
├── 📋 IT-Asset-Tracker/
│   ├── README.md
│   ├── table-schema.md
│   └── screenshots/
│
├── 🖥️ HHD-Configuration/
│   ├── README.md
│   ├── import-set-process.md
│   └── transform-map-config.md
│
├── 📚 Knowledge-Management/
│   ├── README.md
│   └── user-criteria-setup.md
│
├── 🛒 Service-Catalog/
│   ├── README.md
│   └── catalog-item-config.md
│
├── 🔄 Flow-Designer/
│   ├── README.md
│   └── stage-notification-flow.md
│
└── 📝 Study-Notes/
    ├── module-1-2-notes.md
    ├── module-3-4-notes.md
    └── exam-prep.md
```

---

## 🛠️ Skills Demonstrated

| Skill | Level | Projects |
|-------|-------|---------|
| Table Configuration | ⭐⭐⭐⭐ | IT Asset, HHD Config |
| ACL & Security | ⭐⭐⭐⭐ | IT Asset Tracker |
| Import Sets | ⭐⭐⭐⭐ | HHD Configuration |
| Service Catalog | ⭐⭐⭐ | Infinity HHD Item |
| Flow Designer | ⭐⭐⭐ | Stage Notifications |
| Knowledge Management | ⭐⭐⭐ | KB Articles |
| CMDB | ⭐⭐⭐ | CI Relationships |

---

## 📊 CSA Exam Progress

```
Domain 1: Platform Overview (7%)      ✅ Complete
Domain 2: Instance Configuration (10%) ✅ Complete
Domain 3: Configuring Apps (20%)      🔄 In Progress
Domain 4: Self Service & Auto (20%)   🔄 In Progress
Domain 5: Database & Security (30%)   ✅ Complete
Domain 6: Data Migration (13%)        ⏳ Upcoming

Overall: ~67% covered
Exam target: June 2026
```

---

## 🔗 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/k-sevitha)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ksevitha)

*Open to ServiceNow Developer opportunities in Hyderabad!*
*Target: 10 LPA | Available: July 2026*

</div>

---

<div align="center">

⭐ *Star this repo if you find it helpful!* ⭐

</div>
