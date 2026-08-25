**Business Analyst (BA) documents** — BRD, FRD, and SRS — with a simple scenario to illustrate their purpose:

## 📘 **BRD – Business Requirements Document**

-   **About:** The BRD defines the **business vision, objectives, and needs** of a project. It answers _why_ the project is needed and _what_ the business expects as outcomes.
    
-   **Scenario Example:** For an **Online Learning Hub**, the BRD would state:
    
    -   Objective: Provide accessible training to 1,000 learners in 6 months.
        
    -   Scope: Web portal with course catalog, enrollment, and progress tracking.
        
    -   Stakeholders: Learners, trainers, IT team, sponsors.
        

## ⚙️ **FRD – Functional Requirements Document**

-   **About:** The FRD translates business needs into **functional system requirements**. It explains _how_ the system should behave to meet the BRD objectives.
    
-   **Scenario Example:** For the Learning Hub, the FRD would specify:
    
    -   Features: Registration, course search, enrollment, progress dashboard.
        
    -   Workflow: Learner signs up → browses catalog → enrolls → tracks progress.
        
    -   Validation Rules: Unique email required, enrollment limited to available seats.
        

## 💻 **SRS – Software Requirements Specification**

-   **About:** The SRS is the **technical blueprint** for developers and testers. It defines architecture, performance, and integration details.
    
-   **Scenario Example:** For the Learning Hub, the SRS would include:
    
    -   Architecture: Web app with backend database.
        
    -   Non‑Functional Requirements: 500 concurrent users, 99.9% uptime, encrypted login.
        
    -   Data Models: User table (ID, name, email, role), Course table (ID, title, description, capacity).
        
    -   Integration: Payment gateway, email notifications.
        

✨ **Summary** —

-   **BRD** = _Business vision_ (why and what).
    
-   **FRD** = _Functional detail_ (how it should work).
    
-   **SRS** = _Technical blueprint_ (how it will be built).
    

Together, they form the **core documentation flow** that ensures projects are **aligned, functional, and technically feasible**.

---

# 📊 Documents Flow Chart
Business Analyst documents — **BRD, FRD, and SRS**
```
 ┌─────────────────────────────┐
 │ BRD (Business Vision)       │
 │ - Objectives & Outcomes     │
 └───────────────┬─────────────┘
                 ↓
 ┌─────────────────────────────┐
 │ FRD (Functional Detail)     │
 │ - System Functions & Rules  │
 └───────────────┬─────────────┘
                 ↓
 ┌─────────────────────────────┐
 │ SRS (Technical Blueprint)   │
 │ - Architecture & Standards  │
 └───────────────┬─────────────┘
                 ↓
 ┌─────────────────────────────┐
 │ Use Case Diagram            │
 │ - Actors & Interactions     │
 └───────────────┬─────────────┘
                 ↓
 ┌─────────────────────────────┐
 │ User Story Template         │
 │ - Agile Requirements        │
 └───────────────┬─────────────┘
                 ↓
 ┌─────────────────────────────┐
 │ Traceability Matrix         │
 │ - Validation & Coverage     │
 └───────────────┬─────────────┘
                 ↺
       Back to BRD (Alignment)

```

— This chart shows the **continuous lifecycle** of BA documentation:

-   **BRD** defines the vision,
    
-   **FRD** translates it into functions,
    
-   **SRS** provides the technical blueprint,
    
-   **Use Case Diagram** visualizes interactions,
    
-   **User Story Template** drives Agile execution,
    
-   **Traceability Matrix** validates coverage and closes the loop.

---
