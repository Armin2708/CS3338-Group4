# 🚀 **Smart Dashboard - Snapshots Overview**

## 📋 **Project Overview**
The **Smart Dashboard** is a web application designed to consolidate user and system errors, streamlining the process of error investigation for service desk staff and developers. This README covers the progress across four key snapshots, showcasing incremental feature implementations.

---

## 🟢 **Snapshot 1**

### **Objective**
Design a centralized dashboard to display errors, ensuring efficient error handling by consolidating user and system error information.

### **Goals**
1. Create a display for **user errors**, including:
   - Invalid or nonexistent data.
   - Access permission issues (e.g., incorrect username/password).
2. Create a display for **system errors**, highlighting critical network or server-side issues.
3. Implement a display for **error severity**, enabling service desk staff to prioritize issues effectively.

### **Features**
- A navigation dropdown menu-based file management system.
- Buttons for core functions:
  - Help, Next Page, Previous Page, Import More Pages, View File, and Search.
- Separate views for user and system errors, categorized by severity.

### **Technical Specifications**
- **Frameworks/Technologies:**
  - MVC ASP.NET, Bootstrap 5, Entity Framework.
  - Windows Authentication and HTTPS for secure communication.
- **Database Integration:**
  - SQL Server for case management integration.
  - Oracle for enterprise printing integration.

### **Design Constraints**
- Display up to **200 records per page** for optimal performance.
- Simplified UI to avoid overwhelming users with technical details.
- Workflow:
  - Pull data from the database.
  - Convert data into readable formats.
  - Display the formatted data on the dashboard.

---

## 🟡 **Snapshot 2**

### **Objective**
Introduce a functional pagination feature to improve navigation of large datasets within the dashboard.

### **Features**
- Allow users to:
  - Navigate between pages using "Next," "Previous," and specific page number buttons.
  - Adjust the number of error entries displayed (up to 200 per page).
- Enhance usability for handling large sets of error data efficiently.

### **Technical Details**
- Pagination is integrated into the error data views.
- Dynamic page updates are supported for seamless navigation.

---

## 🔵 **Snapshot 3**

### **Objective**
Enhance the front-end with a **side navigation system** and a **help button** to improve user productivity.

### **Features**

#### **Side Navigation**
- **What it Does:**
  - Displays options for Dashboard, User Errors, System Errors, Help, and Settings.
  - Highlights the active page dynamically.
  - Collapsible/expandable for optimized space usage.
- **Technologies:**
  - HTML5, CSS3, JavaScript, and Bootstrap 5.
- **Components:**
  - Nav Links: Icons and labels.
  - Hover Effects: Previews expanded content.

#### **Help Button**
- **What it Does:**
  - Displays contextual guidance, FAQs, and support links.
  - Fully accessible from any page.
- **Technologies:**
  - React components or Bootstrap modals for dynamic content.

---

## 🟣 **Snapshot 4**

### **Objective**
Incorporate advanced data filtering features for enhanced data accessibility and user productivity.

### **Features**

#### **Filtering System**
- **Dynamic Options:**
  - Dropdowns, date pickers, search fields, and checkboxes.
- **Visual Indicators:**
  - Display active filters and search results.
- **Reset Filters:**
  - Quickly reset to default views.

#### **Backend Integration**
- Processes filter parameters and returns filtered data.
- Role-specific filters ensure data visibility aligns with permissions.

### **Future Improvements**
1. **Windows Authentication:**
   - Authenticate users via their Windows credentials.
2. **Role-Based Views:**
   - Restrict non-admin users to limited error details.
3. **“More Errors” Button:**
   - Load additional error entries for large datasets.

---

## 🔍 **Testing Plan**
- Validate navigation, pagination, and filtering across devices and roles.
- Ensure error severity levels and categories display accurately.
- Test the security of backend API calls and user authentication.

---

## 🤝 **How to Contribute**
1. Clone the repository and create a feature branch.
2. Implement changes as per project standards.
3. Submit a pull request for review.

---

## 📧 **Contact**
For support, contact the team at **EMAIL** or refer to the Help section in the dashboard.

---

## 📚 **Resources**
- [Jira Board for Project Tracking](https://calstatela-cs3338.atlassian.net/jira/software/projects/SMAR/boards/68)

---
