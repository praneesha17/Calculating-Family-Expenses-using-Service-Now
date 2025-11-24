# 📘 Calculating Family Expenses Using ServiceNow

A ServiceNow-based expense management system that helps families track daily and household-level spending in real time.  
The project replaces manual bookkeeping with a centralized, automated, and scalable solution using ServiceNow tables, business rules, notifications, and reports.

---

## 🚀 Project Overview

The **Calculating Family Expenses Using ServiceNow** application allows users to:

- Record daily expenses made by each family member  
- Link them to a specific family-level expense record  
- Track spending against a budget with automatic alerts  
- Generate categorized spending reports for better decision-making  

This project demonstrates how ServiceNow’s low-code platform can solve real-world **non-IT use cases** effectively.

---

## 🎯 Purpose

Families often struggle to maintain organized expense logs, leading to overspending and poor financial visibility.  
This solution offers:

- A centralized expense tracking mechanism  
- Automatic numbering for record consistency  
- Budget alerts when spending exceeds limits  
- Detailed reporting for financial planning  
- Reduced manual effort and human error  

---

## 🧠 Ideation

### 🧾 Problem Statement
Tracking expenses manually is error-prone, scattered, and difficult to maintain.  
Most families lack an intuitive system to monitor daily purchases as well as overall budgets.

---

### 🧩 Empathy Map Summary

- **Says:** “I need an easy way to track expenses.”  
- **Thinks:** “Are we crossing our budget?”  
- **Does:** Manually logs or occasionally checks receipts.  
- **Feels:** Anxious about organization and spending.  

---

### 💡 Brainstorming Ideas

- Custom tables in ServiceNow  
- Auto-numbering for expense records  
- Alerts via Business Rules  
- Related lists for Family ↔ Daily expense linkage  
- Categorized reporting  

---

## 📊 Requirements

### Key Components

✔️ Family Expenses Table  
✔️ Daily Expenses Table  
✔️ Auto-numbering prefixes (MFE, DFE)  
✔️ Parent-child relationships  
✔️ Budget monitoring & alerts  
✔️ Reporting dashboard  

---

## 🔁 Data Flow

**User Inputs → Validation → Table Storage → Business Rules → Alerts/Reports**

---

## 🛠️ Technology Stack

- **ServiceNow Custom Tables & Forms**  
- **Business Rules (Glide API)**  
- **UI Policies**  
- **Notification Engine**  
- **Update Sets**  
- **ServiceNow Managed Database (MySQL equivalent)**  
- **Optional REST API integrations**  

---

## 🏗️ Solution Architecture

| Layer | Description |
|------|------------|
| **Data** | Family & Daily expense tables |
| **Logic** | Business rules, numbering logic |
| **UI** | Custom forms & related lists |
| **Configuration** | Update sets for portability |

---

## 🧩 Features

### ✔️ Tables

#### 🏠 Family Expenses Table
- Stores total budget and aggregated spending  
- Auto-generated ID (Prefix: **MFE**)  

#### 📅 Daily Expenses Table
- Individual expense entries  
- Linked to a parent Family record  
- Auto-generated ID (Prefix: **DFE**)  

---

### ✔️ Relationships

- Daily expense records appear in the **related list** of a Family expense entry

---

### ✔️ Business Rules

- Trigger on **Insert** and **Update**  
- Maintain data consistency  
- Enforce budget alerts  

---

### ✔️ Alerts

- Notify when spending **approaches or exceeds the budget**

---

### ✔️ Reporting

- Expense category analysis  
- Historical expenditure tracking  

---

## 📅 Project Planning & Execution

The implementation was divided into **3 sprints**:

| Sprint | Tasks | Story Points |
|------|------|-------------|
| **1** | Setup instance, create update set, implement tables | **9** |
| **2** | Configure relationships & business rules | **5** |
| **3** | Budget alerts & reporting | **6** |
  

---

## 🧩 Development Steps (Milestones)

1. **ServiceNow Instance Setup**
2. **Create Local Update Set — _Family Expenses_**
3. **Create Family Expenses Table** (Prefix: `MFE`)
4. **Create Daily Expenses Table** (Prefix: `DFE`)
5. **Define Parent–Child Relationship**
6. **Configure Related Lists**
7. **Implement Business Rules (Insert/Update triggers)**
8. **Test dynamic filtering & finalize relationships**

---

## 🧪 Testing

- Verified prefix auto-numbering  
- Checked relationship visibility  
- Tested business rule execution  
- Validated alert triggers  
- Ensured correct linkage across tables  
- Reviewed UI/UX in form views  

---

## 🏁 Results

- Accurate daily expense logs  
- Auto-numbered, unique record IDs  
- Automated consistency checks  
- Visual Daily → Family linkage  
- Centralized reports  
- Improved budgeting insight  

---

## 👍 Advantages

- Simple, unified expense tracking  
- Real-time budget monitoring  
- Scalable & customizable  
- Low-code development friendly  
- Real-life use case powered by ServiceNow  

---

## ⚠️ Limitations

- Requires ServiceNow familiarity  
- Needs a PDI or licensed environment  
- Some automation requires admin-level access  

---

## 🏆 Conclusion

The project demonstrates how ServiceNow can be used **beyond IT operations** to solve everyday problems.  
It streamlines household expense tracking, automates budget alerts, and provides meaningful insights — all within a flexible low-code platform.

---



## 📫 Contact

📧 **praneeshavoleti@gmail.com**

