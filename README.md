# SECMS-Salesforce-Project
## Automation Implemented

Automation is an important feature in the **Student Enrollment & Course Management System (SECMS)** because it helps reduce manual work and improves the efficiency of administrative processes. In this project, automation is implemented using **Salesforce Flow Builder**, which allows tasks and workflows to run automatically without requiring constant human involvement. By automating repetitive processes, the system becomes faster, more reliable, and easier to manage.

---

## Flow Automation

A **Salesforce Flow** is designed to automatically assign an instructor to a course based on the selected course category.

When a new **Course record** is created or when an existing course is updated, the flow is automatically triggered. The system then checks the **course category** and compares it with the **expertise field** available in the **Instructor object**.

After evaluating this information, the system identifies an instructor whose expertise matches the course category and assigns that instructor to the course.

This automation ensures that:
- Each course is handled by a **qualified instructor**
- Manual instructor assignment is **eliminated**
- The process becomes **faster and more accurate**
- Incorrect instructor assignments are **prevented**

---

## Example of Automation Logic

| Course Category | Assigned Instructor Expertise |
|----------------|-------------------------------|
| Technical | Technical Instructor |
| Language | Language Instructor |
| Non-Technical | Non-Technical Instructor |

---

### Example Scenario

- If a course is created under the **Technical** category, the system automatically assigns an instructor whose expertise is **Technical**.
- If the course category is **Language**, the system assigns a **Language Instructor**.
- If the course category is **Non-Technical**, the system assigns an instructor specialized in **Non-Technical subjects**.

---

## Benefits of Automation

- Reduces manual administrative work  
- Saves time for system administrators  
- Ensures accurate instructor allocation  
- Improves system efficiency and reliability  
- Maintains consistency in course management

---

Through this automated process, the **SECMS system** improves operational efficiency and ensures that courses are always managed by suitable instructors. This demonstrates how **Salesforce automation tools** can simplify complex administrative tasks in educational management systems.
